![Microsoft Cloud Workshops](https://github.com/Microsoft/MCW-Template-Cloud-Workshop/raw/main/Media/ms-cloud-workshop.png "Microsoft Cloud Workshops")

<div class="MCWHeader1">
Building an infrastructure migration strategy
</div>

<div class="MCWHeader2">
Whiteboard design session student guide
</div>

<div class="MCWHeader3">
July 2021
</div>

Information in this document, including URLs and other Internet Web site references, is subject to change without notice. Unless otherwise noted, the example companies, organizations, products, domain names, e-mail addresses, logos, people, places, and events depicted herein are fictitious, and no association with any real company, organization, product, domain name, e-mail address, logo, person, place or event is intended or should be inferred. Complying with all applicable copyright laws is the responsibility of the user. Without limiting the rights under copyright, no part of this document may be reproduced, stored in or introduced into a retrieval system, or transmitted in any form or by any means (electronic, mechanical, photocopying, recording, or otherwise), or for any purpose, without the express written permission of Microsoft Corporation.

Microsoft may have patents, patent applications, trademarks, copyrights, or other intellectual property rights covering subject matter in this document. Except as expressly provided in any written license agreement from Microsoft, the furnishing of this document does not give you any license to these patents, trademarks, copyrights, or other intellectual property.

The names of manufacturers, products, or URLs are provided for informational purposes only and Microsoft makes no representations and warranties, either expressed, implied, or statutory, regarding these manufacturers or the use of the products with any Microsoft technologies. The inclusion of a manufacturer or product does not imply endorsement of Microsoft of the manufacturer or product. Links may be provided to third party sites. Such sites are not under the control of Microsoft and Microsoft is not responsible for the contents of any linked site or any link contained in a linked site, or any changes or updates to such sites. Microsoft is not responsible for webcasting or any other form of transmission received from any linked site. Microsoft is providing these links to you only as a convenience, and the inclusion of any link does not imply endorsement of Microsoft of the site or the products contained therein.

© 2021 Microsoft Corporation. All rights reserved.

Microsoft and the trademarks listed at https://www.microsoft.com/en-us/legal/intellectualproperty/Trademarks/Usage/General.aspx are trademarks of the Microsoft group of companies. All other trademarks are property of their respective owners.

**Contents**

<!-- TOC -->

- [Building an infrastructure migration strategy whiteboard design session student guide](#building-an-infrastructure-migration-strategy-whiteboard-design-session-student-guide)
  - [Abstract and learning objectives](#abstract-and-learning-objectives)
  - [Step 1: Review the customer case study](#step-1-review-the-customer-case-study)
    - [Customer situation](#customer-situation)
    - [Customer needs](#customer-needs)
    - [Customer objections](#customer-objections)
    - [Common scenarios](#common-scenarios)
  - [Step 2: Assemble and orchestrate resources](#step-2-assemble-and-orchestrate-resources)
  - [Step 3: Envision pitch](#step-3-envision-pitch)
  - [Step 4: Whiteboard design and presentation](#step-4-whiteboard-design-and-presentation)
  - [Step 5: Validate - Present the solution](#step-5-validate---present-the-solution)
  - [Part 1 - Wrap-up](#part-1---wrap-up)
  - [Step 6: Business case](#step-6-business-case)
  - [Step 7: Identify engagement with an AMMP partner](#step-7-identify-engagement-with-an-ammp-partner)
  - [Step 8:  Outline what will make a successful migration](#step-8--outline-what-will-make-a-successful-migration)
  - [Step 9: Business case - Present the solution](#step-9-business-case---present-the-solution)
  - [Part 2 - Wrap-up](#part-2---wrap-up)
  - [Additional references](#additional-references)

<!-- /TOC -->

# Building an infrastructure migration strategy whiteboard design session student guide

## Abstract and learning objectives

In this whiteboard design session, you will understand the business need and compelling event leading to a migration and modernization. The compelling event can be defined by financial criteria, regional business drivers, sustainability, security and compliance need or the timing for new products and services the customers is launching.  Position customer needs first in all activities. Be knowledgeable about Cloud industry terms like Gartner 5Rs. 

At the end of the workshop, you will understand how to communicate the Azure Cloud Adoption Framework with the customer and build a holistic business case for apps, infrastructure, and data.  You will know how to engage a solution assessment with an AMMP partner to assist the customer in their migration.  You will understand how to address customer objections, such as response to AWS and Google competitive pressure.

Key success criteria will include: 

*   Communicate the business value and overall benefit to the customer
*   Identify the approach within the Cloud Adoption Framework that includes the strategy, plan, and readiness of workloads
*   Understand and communicate how Azure will address their healthcare compliance needs
*   Provide cost estimates for the proposed migration workloads
*   Move the customer through the process of validation and commitment to the proposal and business case presented

Within the process of completing this session, you will use the Azure Cloud Adoption Framework to develop a business case that will outline the strategy, plan, and readiness of workloads to Azure.  You will communicate the tools that can assist the customer with partner engagement by familiarizing them with the AMMP program.  You will communicate with the customer how moving workloads to Azure can optimize the operations and maintain compliance within their healthcare organization.  As part of the optimization, you should review the customer's licensing position, understand their cost model, and determine their overall strategy for their users, applications, and data.  


## Step 1: Review the customer case study

**Outcome**

Analyze your customer's needs.

Timeframe: 15 minutes

Directions: With all participants in the session, the facilitator/SME presents an overview of the customer case study along with technical tips.

1. Meet your table participants and trainer.

2. Read all of the directions for steps 1-3 in the student guide.

3. As a table team, review the following customer case study.

### Customer situation

Contoso Health is a health provider network that has grown organically and through the acquisition of other smaller healthcare organizations. Over the years, Contoso Health has seen not only its business grow, but also its on-premises presence in their private datacenter. Today, Contoso Health has over 500 servers in their datacenter that are maintained by a lean infrastructure and application support team.

Contoso Health has a longstanding relationship with Microsoft and is a current enterprise customer with an established Enterprise Agreement. Your team represents the migration project team for Contoso Health. You have been tasked with evaluating the processes and tooling and programs that can be used to assess, test, and eventually migrate the workloads to Microsoft Azure and coordinate the use of Microsoft CSP partners, where necessary.

To validate that Microsoft Azure will be able to accommodate Contoso Health's existing servers and applications, a collection of servers has been identified by IT leadership and the business which are representative of Contoso's on-premises estate. While these servers are representative of the current on-premises estate, they are also an existing production system that is critical to the business.

### Customer needs

Limiting risk while maintaining compliance. While the applications selected for this migration effort are representative of Contoso Health's on-premises estate, the are also production systems.
Extend in a stable way. Without access to the source code, the applications cannot be easily modified and are considered stable today. Stability during and after the migration is critical and cannot come at the cost of modernization.

IT leadership's goals for this initial migration to Azure include:

1. Validate the migration of workloads hosted on legacy Linux and Windows operating systems including Windows Server 2008 R2, and Windows Server 2012 R2 as well as systems hosted on Microsoft SQL Server 2008 R2, to take advantage of the additional time offered for vendor support.
  
2. Modernize systems to improve availability and resiliency where possible within the timelines needed for rapid migration. While the overarching goal is to re-host existing systems, where meaningful improvements can be made, they should be.
  
3. Investigate the potential modernization of application components by evaluating and eventually transitioning to platform services where possible after issues around vendor support have been addressed.
  
4. Educate the business and Contoso Health's management on the processes and tooling that can be used to eventually move the remaining servers to Microsoft Azure, drastically reducing their on-premises presence.
   
5. Identify opportunities to optimize operational efficiency and decrease capital expenditures on IT infrastructure.

While each workload will undeniably be different due to different technologies and dependencies, the discovery in this exercise will help to instill a set of practices that can be used to move the remainder of Contoso Health's on-premises estate into Microsoft Azure reliably and predictably.

### Customer objections

1. Contoso Health has a current Enterprise Agreement for all of their Windows Server software that includes Software Assurance.  If they migrate any of their workloads to Azure, they do not have to pay for additional Windows Server licensing.
   
2. The customer currently has servers that are under-utilized most of the year, but need additional capacity during cold weather months due to a rise is health issues.  Contoso does not want to pay extra for server performance that is not used.
   
3. Contoso has servers that run workloads that require a consistent performance level. They are concerned that moving these servers will cost more in Azure.
   
4. Contoso IT staff has limited experience with server migrations and no cloud experience.  It is unlikely that they can handle this type of project along with their current mission-critical application support requirements.

5. Contoso is also discussing their migration to cloud with AWS and Google.  They want to know how Microsoft is any different in services and support.


### Common scenarios

![Diagram representing the workflow of the Cloud Adoption Framework, moving from Define strategy to plan to ready to adopt, with manage and govern part of the continuous process.](images/caf.png "Cloud Adoption Framework for Azure")

## Step 2: Assemble and orchestrate resources

**Outcome**

Design a solution and prepare to present the solution to the target customer audience in a 15-minute chalk-talk format.

Timeframe: 15 minutes

Directions:  With all participants at your table, answer the following questions and list the answers on a whiteboard:

1. Who should you present this solution to? Who is your target customer audience? Who are the decision makers?
2. What internal or external technical and business experts would also be needed in a real-world presentation to decision makers?

   
## Step 3: Envision pitch

**Outcome**

Determine the positioning statement based on the Microsoft Migration and Modernization value proposition.

Timeframe: 30-45 minutes

Directions:  With all participants at your table, answer the following questions and list the answers on a whiteboard:

1. How will you tie the business needs of Contoso to a positioning statement and value proposition to migrate to Azure?


## Step 4: Whiteboard design and presentation 

**Outcome**

Design a solution and prepare to present the solution that incorporates the CAF/Landing zone to prepare them for migration to the target customer audience in a 15-minute PowerPoint format.

Timeframe: 90-120 minutes

Directions:  With all participants at your table, answer the following questions and list the answers on a whiteboard:

1. Create a PowerPoint presentation that presents the value proposition of utilizing the Cloud Adoption Framework for migrating and creating Contoso's first Landing Zone in Azure. 


## Step 5: Validate - Present the solution

**Outcome**

Present a solution to the target customer audience in a 15-minute PowerPoint presentation format.  

Validate the value proposition with the customer needs.  Identify the first Landing Zone for migration to Azure.

Timeframe: 30 minutes (15 minutes per team presentation)

**Presentation**

Directions:

1. Pair with another table.

2. One table is the Microsoft team and the other table is the customer.

3. The Microsoft team presents their proposed solution to the customer.

4. The customer makes one of the objections from the list of objections.

5. The Microsoft team responds to the objection.

6. The customer team gives feedback to the Microsoft team.

7. Tables switch roles and repeat Steps 2-6.

## Part 1 - Wrap-up

Timeframe: 15 minutes

Directions: Tables reconvene with the larger group to hear the facilitator/SME share the preferred solution for the case study.


## Step 6: Business case

**Outcome**

Build a business case for licensing optimization gained from an Azure migration.  Provide the economic and operational benefits to quantify, educate, and guide the customer through Cloud Economics best practices.

Timeframe: 60-90 minutes

Directions:  With all participants at your table, answer the following questions and list the answers on a whiteboard:

1. How can you address Contoso's business needs for economic and operational efficiency?
2. What opportunities are available to optimize licensing and lower overall costs to Contoso?


## Step 7: Identify engagement with an AMMP partner

Timeframe: 15 minutes

Directions:  With all participants at your table, answer the following questions and list the answers on a whiteboard:

1. How can Microsoft assist Contoso in identifying and introducing an AMMP partner?
2. What objection does utilizing an AMMP partner address?
   

## Step 8:  Outline what will make a successful migration

**Outcome**

Expand on the previous whiteboard design based on Cloud Adoption Framework for Azure and outline a successful migration to a Landing Zone.

Timeframe: 60-90 minutes

Directions:  With all participants at your table, answer the following questions and list the answers on a whiteboard:

1. What criteria of success can you show Contoso that outlines a successful first step to migration?
2. What is the best practice for choosing a workload to be a part of the first Landing Zone?
3. Create a PowerPoint presentation that establishes the Business Case.  This should address all of the customer needs and objections.


## Step 9: Business case - Present the solution

**Outcome**

Present a solution to the target customer audience in a 15-minute PowerPoint presentation format.

The presentation should outline the Business Case, success criteria for a successful migration, and address all customer needs and objections.

Timeframe: 30 minutes (15 minutes per team presentation)

**Presentation**

Directions:

1. Pair with another table.

2. One table is the Microsoft team and the other table is the customer.

3. The Microsoft team presents their proposed solution to the customer.

4. The customer makes one of the objections from the list of objections.

5. The Microsoft team responds to the objection.

6. The customer team gives feedback to the Microsoft team.

7. Tables switch roles and repeat Steps 2-6.

## Part 2 - Wrap-up

Timeframe: 15 minutes

Directions: Tables reconvene with the larger group to hear the facilitator/SME share the preferred solution for the case study.


## Additional references

- [Microsoft Cloud Workshops](https://microsoftcloudworkshop.com/index.html)
- [Azure Cloud Adoption Framework](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/)
- [Azure Well-architected Framework](https://docs.microsoft.com/en-us/azure/architecture/framework/)
- [Azure Migration Program - AMP](https://www.microsoft.com/azure/partners/amp)




