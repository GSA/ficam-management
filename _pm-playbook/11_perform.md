---
layout: default
title: Measure and Report Performance
permalink: /pm-playbook/perform/
collection: pm-playbook
---
---

Assigning performance measurements to your agency‘s ICAM program provides decision makers and stakeholders with a useful tool to monitor progress, determine program effectiveness, and identify areas that need more funding or process improvement.
Performance reporting for ICAM programs has traditionally focused on external reporting requirements (e.g., OMB HSPD-12 implementation status reports).

* [Leverage Peformance Reporting](#leverage-performance-reporting)
* [Include Agency ICAM Metrics](#include-agency-icam-metrics)

### Leverage Performance Reporting

Determine how to use performance reporting to improve alignment with your ICAM segment architecture to drive progress on ICAM programs internal to the agency.

### Include Agency ICAM Metrics

Incorporate relevant metrics into your Exhibit 300 business case submissions for any ICAM investment as a mean of tracking important information and showing investment results and value to your agency.  

#### ICAM-specific FY18 FISMA Reporting Metrics

The April-release FY18 CIO FISMA Metrics contains several metrics applicable to ICAM to ensure that departments and agencies safeguard their system, networks, and facilities with appropriate cybersecurity defense. These metrics serve as an existing foundation for agency reporting requirements and performance measurement:

| <center> Section Protect-Subsection </center> | <center> Metric </center> |
|:---------------------------------------------:|---------------------------|
| **Unprivileged Network Users** | **2.4.1.** Number of users with network accounts.<sup>1</sup> (Exclude privileged network accounts and non-user accounts.) <br><br> **2.4.2.** Number of users (from 2.4.1.) that are required to authenticate to the network through the machine-based or user-based enforcement of a two-factor PIV credential<sup>2</sup> or other NIST 800-63 r3 Identity Assurance Level (IAL)3/Authenticator Assurance Level (AAL) 3/Federated Assurance Level (FAL) 3 credential.<sup>3</sup> <br><br> **2.4.3.** Number of users (from 2.4.1) that use a username and password as their primary method for network authentication. Please describe compensating controls for limiting these users’ access in the comments field. <br><br> **2.4.4.** Number of users (from 2.4.1) covered by a centralized dynamic access management solution that controls and monitors users’ access. [(NIST SP 800-53r4 AC-2(6))](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r4.pdf){:target="_blank"} |
| **Privileged Network Users** | **2.5.1** Number of users with network accounts. (Exclude unprivileged network accounts and non-user accounts.) <br><br> **2.5.2.** Number of users (from 2.5.1) that are required to authenticate to the network through the machine-based or user-based enforcement of a two-factor PIV credential<sup>2</sup> or other NIST 800-63 r3 Identity Assurance Level (IAL)3/Authenticator Assurance Level (AAL) 3/Federated Assurance Level (FAL) 3 credential.<sup>3</sup> <br><br> **2.5.3.** Number of users (from 2.5.1) that use a username and password as their primary method for network authentication. Please describe compensating controls for limiting these users’ access in the comments field. <br><br> **2.5.4.** Number of users (from 2.5.1) covered by a centralized dynamic access management solution that controls and monitors users’ access. [(NIST SP 800-53r4 AC-2(6))](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r4.pdf){:target="_blank"} <br><br> **2.5.5.** Frequency with which privileged user privileges are reviewed, according to agency policy.|
| **Network and Local System Accounts** | **2.6.1.** Number of users with privileged local system accounts.<sup>4</sup> <br><br>**2.6.2.** Number of users with privileged local system accounts (from 2.6.1) are accessible through the Agency’s network in which the privileged user is required to authenticate to the network through the machine-based or user-based enforcement of a two-factor PIV credential or other NIST 800-63 r3 IAL3/AAL3/FAL3 credential. <br><br> **2.7.** Number of High Value Asset (HVA) systems<sup>5</sup> that require all government and contractor users (100% privileged and unprivileged) to authenticate through the machine-based or user-based enforcement of a two-factor PIV credential or other NIST 800-63 r3 IAL3/AAL3 credential. <br><br> **2.7.1** Number of HVA systems assessed by DHS, a third-party, or independent entity (per M-17-09) that determined machine-based or user-based enforcement of a two-factor PIV credential (as described in 2.7.) is not required due to mitigating security capabilities.|

{% include alert-warning.html heading = "Implementation Tip" content="It is important to make leadership and management feel ownership and accountability for the success of their agency’s ICAM program. One way to accomplish this is to tie any outcomes and accomplishments of the ICAM program specifically to the responsible individual’s yearly performance plan." %}

{% include alert-info.html heading = "Additional Guidance" content="The GSA FICAM Program has developed guidance for the April-release FY18 CIO FISMA ICAM-related Metrics to help agencies gather and report ICAM metrics. The guidance can be accessed by clicking on the button below." %}

 <a href="/ficam-management/img/Draft_April-release FY18 FISMA ICAM Metrics Guidance_20180504.docx"> <button>Download the FY18 ICAM FISMA Metrics Guidance</button> </a>

---
<sup> 1 </sup> An unprivileged network account is any account that is not a privileged network account.

<sup> 2 </sup> For a person with one or more unprivileged network accounts, the person should be counted in the total only if a two-factor PIV Credential is necessary to authenticate to all network accounts. The enforcement of authentication may be accomplished via either user-based or machine-based configuration settings.

<sup> 3 </sup> For additional information, refer to [NIST SP 800-63.](https://pages.nist.gov/800-63-3/){:target="_blank"}

<sup> 4 </sup> Do not report privileged local system accounts that are not accessible on the network.

<sup> 5 </sup> HVA as defined in [M-17-09. ](https://www.whitehouse.gov/sites/whitehouse.gov/files/omb/memoranda/2017/m-17-09.pdf){:target="_blank"}  OMB will leverage existing data sources for the denominator of HVA related metrics.
