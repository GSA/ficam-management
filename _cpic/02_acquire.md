---
layout: default
navtitle: Acquire ICAM Products and Services
title: Acquire ICAM Products and Services
collection: cpic
permalink: cpic/acquire/
---

When planning to acquire Identity, Credential, and Access Management (ICAM) products and services, your agency must comply with specified regulations and policies, mainly the Federal Acquisition Regulation (FAR). The FAR sets the rules governing the federal acquisition process and includes several clauses particularly relevant to your agency's ICAM program. Agencies must comply with HSPD-12 and FIPS 201 for contractors who require routine logical or physical access and include language to this effect in applicable solicitations and contracts.

Agencies should purchase only approved products and services in support of their HSPD-12 implementations. The FIPS 201 Evaluation Program was developed to organize and define a standard approval process for these products and services. All required NIST validation and GSA testing must be met to be an approved product or service for HSPD-12 purchases. You can find approved products and services, which have been demonstrated to meet NIST validation and GSA testing and have been qualified by the Evaluation Program, on the FIPS 201 [Approved Products List](https://www.idmanagement.gov/approved-products-list/){:target="_blank"}.

## Evaluate Factors to Estimate Solution Cost

After you choose a solution, you can estimate costs. The following tables include common characteristics that you should examine not only to determine expenses but also to compare the potential cost savings of various solutions.

### PACS Evaluation Factors

| <center> Evaluation Factor </center> | <center> Description </center> |
|:-------------------------------------|--------------------------------|
| **Facility Size** | The number of users requiring access to a facility impacts the level of administrative effort needed to provision user accounts and manage access privileges. |
| **PACS Service Level** | Determine whether you should explore enterprise-level solutions. For example, an agency hosting a server for its bureaus and components can provide cost savings and better efficiency. |
| **Population Analysis** | Examine user populations (for example, employees, contractors, and federal and non-federal facility tenants) to determine the types of groups requiring access. Consider complex user populations when you decide which PACS solution to implement. Also, consider the ability to scale as modernization continues, and your user base changes over time. |
| **Number of PACS** | The number of physical access control systems (PACS) within an agency often dictates implementation time and can significantly affect implementation cost, depending on the resources' connection requirements. |
| **Type of PACS** | The type of PACS varies based on the vendors, platforms, operating systems, products, and databases that are in use across your organization. These variables impact the complexity of integrating resources with the PACS infrastructure and require different integration processes. |
| **Existing PACS Investments** | Your agency may have investments in place that can provide physical access services consistent with the modernized ICAM segment architecture. You should use those investments when possible, as they can help achieve a modernized PACS state without requiring significant investment from the organization. |
| **Credentials Supported** | Examine the types of credentials that the PACS must support (including PIV-I) and incorporate any costs associated with validating acceptable credentials. |
| **Protection Areas** | Consider the number or combination of protection areas (Limited, Exclusion, or Controlled) when determining program costs. For example, a high number of exclusion protection areas may increase costs due to the added level of access control required to protect those areas. |

### LACS Evaluation Factors

Logical access control system (LACS) projects give your agency the potential for significant ROI in the form of cost avoidance, reallocation of resources, productivity gains, and reduced administrative burden. To realize these benefits, when you plan a new or modify an existing LACS investment, you should assess your agency's organizational structure, identity stores, access control processes, and IT resources.

| <center> Evaluation Factor </center> | <center> Description </center> |
|:-------------------------------------|--------------------------------|
| **Organizational Size** | The number and type of users requiring access to agency IT resources, as well as the turnover rate of users, significantly impacts the level of administrative effort required to provision user accounts and manage access privileges. |
| **Cost Effectiveness** | Evaluate the ROI that your agency would gain compared to the upfront investment costs when planning for a LACS investment. |
| **Complexity of User Population** | Organizations with complex user and role management requirements should consider LACS solutions that offer services in these areas. You can take advantage of user management complexity to streamline existing processes or areas that could otherwise significantly increase implementation costs. <br><br> The availability of user repositories can also impact implementation costs. |
| **Number of IT Resources** | The number of IT resources within an agency often dictates implementation time and can significantly affect implementation cost, depending on the resources' connection requirements. |
| **Type of IT Resources** | The type of IT resources varies based on the platforms, operating systems, products, and databases that are in use across the organization. These variances impact the complexity of integrating resources with the LACS infrastructure and require different integration processes. |
| **Complexity of Integrating with IT Resources** | Resource integration complexity is a combination of several factors, including the age of the resource, underlying infrastructure, operating requirements, and user base. These factors indicate how complex it can be to integrate some resources into the modernized LACS infrastructure. Large numbers of complex resources (including mainframe applications) can rapidly increase overall implementation costs. At a high level, the complexity and cost associated with common application types can be grouped as follows: <br><br> •	Web-based applications – low to moderate complexity <br><br> •	Client/server applications – moderate to high complexity <br><br> •	Distributed applications – varied complexity <br><br> •	Mainframe/legacy applications – high to very high complexity |
| **Business Goals/Drivers** | Internal agency policies, business needs, and required compliance with external federal policies and regulations drive requirements for LACS solutions. Some solutions, while inexpensive, may not always create long term cost savings and may prevent the organization from meeting certain business goals. |
| **Workflow Requirements** | Examine the complexity of manual and semi-manual workflows used to provision user accounts and access privileges to IT resources. The number and complexity of an agency's workflows impact the schedule and labor costs associated with implementing some LACS solutions. |
| **Organizational IT Infrastructure** | Some platforms and operating environments, particularly ones that leverage legacy products, may require additional support or custom configuration to achieve the maximum benefit from LACS solutions. This includes potential costs associated with networking LACS components and high-availability components. Environments that use non-standard operating systems may require additional investment to integrate into a modernized LACS infrastructure. |
| **Vendor Product Compatibility and Interoperability with Existing Infrastructure** | If your agency is considering a commercial off-the-shelf (COTS) identity and access management (IAM) product suite, you should assess the integration approach of these products for interoperability, and find the best fit for your agency. You should also investigate the availability of enterprise software licenses, as these can significantly lower acquisition costs and influence your agency's make or buy decision. |

{% include alert-success.html heading = "Lesson Learned" content="To drive adoption of its enterprise LACS and participation in pilot implementations, USDA offered to fund the initial LACS integration costs for a subset of agency applications that were candidates for early adoption. Doing so increased participation since the department could demonstrate technical interoperability using real-world examples." %}

## Determine Funding for ICAM Solution

You may find challenges in funding and implementing the investment when equipment and services will likely be purchased centrally. Here are some approaches that other agencies have taken to fund their PACS and LACS improvement efforts:

- **Incorporate costs into existing investments.** You don't need a separate investment for an implementation like an enterprise PACS solution. You can include the costs for PACS modernization into an existing business case.
- **Investment business case.** Create a new investment request to fund the implementation at the enterprise level. This business case should include details of how the proposed investment would support the agency's mission.
- **Working capital fund.** Use a fund that can provide financing to agencies without annual appropriation by Congress for operations that generate receipts. This funding method works well for an agency that offers an enterprise PACS as a centralized service and has a fee structure for the users across the agency's bureaus or components.

In addition to determining funding needs and obtaining funding, a key aspect of PACS implementation planning is outlining the life cycle activities associated with the modernization effort and determining the project schedule.

### Cost-Saving Tips

Any product that uses cryptographic processes with the PIV credential must comply with FIPS 140 and be approved by a NIST-validated laboratory. You should seek out manufacturers that provide architectures that minimize the cost of FIPS 140 by producing components in very high volume, or by amortizing the cost into common components, such as multi-door controllers.

When you write solicitations and contracts, where applicable, include language requiring PIV credentials where you provide encryption and digital signature services. This language supplements the existing FAR requirements for contractors to use PIV credentials. This approach promotes governmentwide consistency in security services and offers greater ROI in leveraging your agency's existing PIV infrastructure.

## Review the Approved Products List

The [FIPS 201 APL](https://www.idmanagement.gov/approved-products-list/){:target="_blank"} is a list of HSPD-12 related products and services that have been tested through procedures approved by the National Institute of Standards and Technology (NIST). You can use multiple GSA Schedules to purchase a resource that's included on the APL. When you purchase products and services for HSPD-12 implementation, you must follow OMB Memorandum M-19-17 and use the FIPS 201 Evaluation Program APL. The APL is continuously updated with approved products and technologies. It's your responsibility to stay current on these changes and incorporate them into your planning during regular technology refresh cycles as part of the capital planning and budget process. Find a complete inventory of government certified and approved services and product listings on [IDManagement.gov](https://www.idmanagement.gov){:target="_blank"}.

{% include alert-info.html heading="Implementation Tip" content="Before you purchase a product listed on the HSPD-12 APL, determine if the product is appropriate for the risk level and design of your agency's ICAM solution. A given product on the APL may not be interoperable or appropriate for your agency's implementation. You must properly integrate and configure purchased products to be interoperable with other ICAM programs and services." %}

## Identify Contract Vehicles for ICAM Products and Services

In addition to the requirements governing federal acquisitions, there are other resources to support ICAM program acquisition include GSA Schedules and the [PACS Customer Ordering Guide](https://www.gsa.gov/cdnstatic/General_Supplies__Services/Guide_to_PACS_v2%2006-12-2018.pdf){:target="_blank"}.

GSA Schedules are purchasing vehicles for a broad range of products and services. The resources available on the GSA Schedules have pre-approved vendors and pre-negotiated rates. You are not required to use GSA Schedules for acquisition, but they provide quick, flexible, and cost-effective procurement solutions and assist in compliance by including approved products. Here are some examples of common GSA Schedules:

> ### IT Schedule 70

> [IT Schedule 70](https://www.gsa.gov/technology/technology-purchasing-programs/it-schedule-70){:target="_blank"} is part of the Multiple Award Schedule (MAS) program and gives agencies direct access to commercial experts who can address the needs of the government IT community through a series of Special Item Numbers (SINs). These SINs cover most of the general-purpose commercial IT hardware, software, and services.
 
> - Refer to SINs 132-60 through 152-62, to find procurement needs for your agency's ICAM program. These schedules include electronic credentials, PKI services, and HSPD-12 products and services.
> - If your agency uses an acquisition vehicle other than GSA IT Schedule 70, your agency will take responsibility for ensuring compliance with applicable federal standards and requirements.

> ### IT Schedule 84

> [IT Schedule 84](https://www.gsa.gov/buying-selling/purchasing-programs/gsa-schedules/list-of-gsa-schedules/schedule-84security-fire-law-enforcement){:target="_blank"} offers PACS-related security solutions for law enforcement, security, facility management, fire, rescue, clothing, marine craft, and emergency and disaster response.

You can purchase resources from both schedules to meet your ICAM implementation needs. For example, you could buy new credential readers for access control points from Schedule 84 and services from the system integrator from Schedule 70.

## Benefits

- **More competitive rates and potentially lower costs.** Regardless of the method used to access Schedules 70 and 84, GSA has already negotiated fair and reasonable prices for these products and services.
- **Shorter procurement time.** GSA Schedules offer streamlined procurement, as opposed to agency-negotiated contracts, which can be cumbersome and costly. Tools such as eBuy and GSA Advantage are available to assist in ordering from both Schedules.
- **Reduced complexity and effort required to perform due diligence.** If you purchase products not included on the GSA APL, you are responsible for ensuring that the products meet all applicable federal standards and requirements, ensuring the products conform to applicable federal standards, and maintaining a written plan to ensure ongoing conformance for the life cycle of the components.
- **Elimination of non-compliance with standards and requirements.** If your agency doesn't use  the GSA Schedules and the APL, you run the risk of potential non-compliance if your conformance processes are incomplete or do not keep pace with changes within the GSA Evaluation Program.
