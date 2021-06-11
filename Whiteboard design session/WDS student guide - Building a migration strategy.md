


#  Building a holistic migration strategy with Infrastructure, Apps, Data & AI

Contoso Health is a health provider network that has grown organically and through the acquisition of other smaller healthcare organizations. Over the years, Contoso Health has seen not only its business grow, but also its on-premises presence in their private datacenter. Today, Contoso Health has over 500 servers in their datacenter that are maintained by a lean infrastructure and application support team.

During a recent audit of their on-premises datacenter, several alarming findings were called out. The audit report found that many business-critical workloads for Contoso Health are running on aging infrastructure that is rapidly approaching its end of support date, and in some cases, already past that date. These discoveries apply to both physical hardware and software such as operating systems and include workloads running on Windows Server 2008 R2. Contoso Health also leverages virtualization within their datacenter, using Hyper-V as a hypervisor for many workloads. Even virtualized systems were found to be out of support or nearing the end of support during the audit. This is a matter of serious concern and Contoso Health's management wants to take steps to mitigate the risk they are facing with immediate effect to bring themselves back into a supported state.

Contoso Health has a longstanding relationship with Microsoft and is a current enterprise customer with an established Enterprise Agreement. Your team represents the migration project team for Contoso Health. You have been tasked with evaluating the processes and tooling that can be used to assess, test, and eventually migrate the workloads to Microsoft Azure.

Public cloud computing is still a new concept to Contoso Health's infrastructure and application support teams. While their existing applications are known to run on-premises, moving to a public cloud infrastructure is inherently complex due to the number of existing servers, applications, and the lack of knowledge around what it will take to move everything to Microsoft Azure. Also, Contoso Health does not have access to the source code for many of its applications. This introduces risk as applications that are not well documented and cannot be updated to accommodate new platforms are migrated to the cloud.

To validate that Microsoft Azure will be able to accommodate Contoso Health's existing servers and applications, a collection of servers has been identified by IT leadership and the business which are representative of Contoso's on-premises estate. While these servers are representative of the current on-premises estate, they are also an existing production system that is critical to the business.

Business drivers for this effort include:

Limiting risk. While the applications selected for this migration effort are representative of Contoso Health's on-premises estate, the are also production systems.
Extend in a stable way. Without access to the source code, the applications cannot be easily modified and are considered stable today. Stability during and after the migration is critical and cannot come at the cost of modernization.
IT leadership's goals for this initial migration to Azure include:

- Validate the migration of workloads hosted on legacy Windows operating systems including Windows Server 2008 R2, and Windows Server 2012 R2, as well as systems hosted on Microsoft SQL Server 2008 R2, to take advantage of the additional time offered for vendor support.
- Modernize systems to improve availability and resiliency where possible within the timelines needed for rapid migration. While the overarching goal is to rehost existing systems, where meaningful improvements can be made, they should be.
- Investigate the potential modernization of application components by evaluating and eventually transitioning to platform services where possible after issues around vendor support have been addressed.
- Educate the business and Contoso Health's management on the processes and tooling that can be used to eventually move the remaining servers to Microsoft Azure, drastically reducing their on-premises presence.

While each workload will undeniably be different due to different technologies and dependencies, the discovery in this exercise will help to instill a set of practices that can be used to move the remainder of Contoso Health's on-premises estate into Microsoft Azure reliably and predictably.
