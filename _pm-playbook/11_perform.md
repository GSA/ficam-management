---
layout: default
title: Measure and Report Performance
permalink: /pm-playbook/perform/
collection: pm-playbook
---
---

Assigning performance measurements to your agency‘s ICAM program provides decision makers and stakeholders with a useful tool to monitor progress, determine program effectiveness, and identify areas that need more funding or process improvement.
Performance reporting for ICAM programs has traditionally focused on external reporting requirements (e.g., OMB HSPD-12 implementation status reports).

* [Performance Measurement](#performance-measurement)
* [Government-wide ICAM Metrics](#government-wide-icam-metrics)

### Performance Measurement

M-18-XY identifies two key performance measurements that will help agencies in establishing effective ICAM governance. The two performance measurements are:

* Outline enterprise-level performance expectations for cybersecurity and privacy risk management through each user’s lifecycle, including changes in the user’s access privileges;
* Develop a mechanism to streamline and automate enterprise-level performance reporting. This mechanism should align with existing and planned reporting and analytics structures and tools, such as the CDM dashboards and FISMA reporting.

In addition to the performance measurements that your agency is required to measure, we have included below a list of best practices/recommendations that will help your agency build a more holistic ICAM program with the intended purpose of providing meaningful data at the agency-level. Please keep in mind that this list is not exhaustive nor is it a requirement. The recommended metrics are meant to accomplish the following goals:

* Reduce the time needed for agencies to prepare external reports;
* Provide meaningful, synchronized data points for government-wide leadership, agency leadership, and program managers; and
*	Represent comprehensive, genericized measurements that cover transactions between the Federal Government and its employees, contractors, business partners, and citizens.

#### Recommended Metrics

| <center> Metric </center> | <center> Calculation </center> |
|---------------------------------------------|---------------------------|
| **1. Data Minimization** | Percent (%) of IT resources that consume and retain the minimum set of user attributes necessary to manage their access to respective IT resources |
| **2. Credential Revocation** | A.	Average time to revoke credentials from employees <br> B.	Average time to revoke credentials from contractors <br> C.	Average time to revoke credentials from all other credential holders |
| **3. Secure Authentication** | A.	Percent (%) of IT resources enforcing authentication with the appropriate credential for unprivileged users <br> B.	Percent (%) of IT resources enforcing authentication with the appropriate credential for privileged users |
| **4. User Account Recertification** | A.	Percent (%) of unprivileged user accounts and associated access permissions that were recertified within the agency-defined timeframe <br> B.	Percent (%) of privileged user accounts and associated access permissions that were recertified within the agency-defined timeframe |
| **5. Access Revocation** | Average time to revoke access permissions |
| **6. Freshness of Identity Data** | A.	Does your agency have automated processes to propagate changes to core identity attributes? <br> B.	Percent (%) of IT resources that leverage an automated process to use core enterprise identity attributes |
| **7. Data Protection** | A.	Percent (%) of agency IT resources with accounts containing Personally Identifiable Information (PII)  that is encrypted with federally approved encryption methods <br> B.	Percent (%) of agency IT resources that encrypt PII, with federally approved encryption methods, during transmission |
| **8. Credential Issuance** | A.	Average time to issue credentials to employees <br> B.	Average time to issue credentials to contractors |
| **9. Federated PIV/PKI Credentials** | Percent (%) of IT resources, which require authentication,  that are enabled to accept PIV/PKI credentials from other federal agencies |
| **10. Federated Third-Party Credentials** | Percent (%) of public-facing IT resources, which require authentication, that accept approved third-party credentials |
| **11. Physical Security** | Percent (%) of agency physical access points that require electronic PIV card authentication for internal employees and contractors whose official duties require routine access |
| **12. Automated Provisioning** | A.	Does your agency have an automated capability to provision and de-provision access permissions? <br> B.	Percent (%) of applications that leverage an automated workflow to provision and de-provision access permissions to protected IT resources |
| **13. Access Policies Review** | Does your agency have a process in place to review and update digital access policies based on audit and monitoring information? |
| **14. Government-wide Alignment** | Does your agency have a process in place to review your agency’s policies and procedures to determine whether they align with government-wide requirements? |

### Government-wide ICAM Metrics

The [FY 2018 CIO FISMA Metrics](https://www.dhs.gov/sites/default/files/publications/FY 2018 CIO FISMA Metrics_V2.0.1_final.pdf){:target="_blank"} (effective FY 2018 Quarter 3) contain several metrics applicable to ICAM to ensure that departments and agencies safeguard their system, networks, and facilities with appropriate cybersecurity defense. These metrics serve as an existing foundation for agency reporting requirements and performance measurement:

| <center> Section Protect-Subsection </center> | <center> Metric </center> |
|:---------------------------------------------:|---------------------------|
| **Unprivileged Network Users** | **2.4.1.** Number of users with network accounts. (Exclude privileged network accounts and non-user accounts.) <br><br> **2.4.2.** Number of users (from 2.4.1.) that are required to authenticate to the network through the machine-based or user-based enforcement of a two-factor PIV credential or other NIST 800-63 r3 Identity Assurance Level (IAL)3/Authenticator Assurance Level (AAL) 3/Federated Assurance Level (FAL) 3 credential. <br><br> **2.4.3.** Number of users (from 2.4.1) that use a username and password as their primary method for network authentication. Please describe compensating controls for limiting these users’ access in the comments field. <br><br> **2.4.4.** Number of users (from 2.4.1) covered by a centralized dynamic access management solution that controls and monitors users’ access. [(NIST SP 800-53r4 AC-2(6))](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r4.pdf){:target="_blank"} |
| **Privileged Network Users** | **2.5.1** Number of users with network accounts. (Exclude unprivileged network accounts and non-user accounts.) <br><br> **2.5.2.** Number of users (from 2.5.1) that are required to authenticate to the network through the machine-based or user-based enforcement of a two-factor PIV credential or other NIST 800-63 r3 Identity Assurance Level (IAL)3/Authenticator Assurance Level (AAL) 3/Federated Assurance Level (FAL) 3 credential.<br><br> **2.5.3.** Number of users (from 2.5.1) that use a username and password as their primary method for network authentication. Please describe compensating controls for limiting these users’ access in the comments field. <br><br> **2.5.4.** Number of users (from 2.5.1) covered by a centralized dynamic access management solution that controls and monitors users’ access. [(NIST SP 800-53r4 AC-2(6))](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r4.pdf){:target="_blank"} <br><br> **2.5.5.** Frequency with which privileged user privileges are reviewed, according to agency policy.|
| **Network and Local System Accounts** | **2.6.1.** Number of users with privileged local system accounts.<br><br>**2.6.2.** Number of users with privileged local system accounts (from 2.6.1) are accessible through the Agency’s network in which the privileged user is required to authenticate to the network through the machine-based or user-based enforcement of a two-factor PIV credential or other NIST 800-63 r3 IAL3/AAL3/FAL3 credential. <br><br> **2.7.** Number of High Value Asset (HVA) systems that require all government and contractor users (100% privileged and unprivileged) to authenticate through the machine-based or user-based enforcement of a two-factor PIV credential or other NIST 800-63 r3 IAL3/AAL3 credential. <br><br> **2.7.1** Number of HVA systems assessed by DHS, a third-party, or independent entity (per M-17-09) that determined machine-based or user-based enforcement of a two-factor PIV credential (as described in 2.7.) is not required due to mitigating security capabilities.|

{% include alert-warning.html heading = "Implementation Tips" content="It is important to make leadership and management feel ownership and accountability for the success of their agency’s ICAM program. One way to accomplish this is to tie any outcomes and accomplishments of the ICAM program specifically to the responsible individual’s yearly performance plan. " %}

{% include alert-warning.html heading = "Implementation Tips" content="Incorporate relevant metrics into your Exhibit 300 business case submissions for any ICAM investment as a mean of tracking important information and showing investment results and value to your agency.  " %}

{% include alert-info.html heading = "Additional Guidance" content="The GSA FICAM Program has developed guidance for the April-release FY18 CIO FISMA ICAM-related Metrics to help agencies gather and report ICAM metrics. The guidance can be accessed by clicking on the button below." %}

 <a href="/ficam-management/img/Draft_April-release FY18 FISMA ICAM Metrics Guidance_20180504.docx"> <button>Download the FY18 ICAM FISMA Metrics Guidance</button> </a>
