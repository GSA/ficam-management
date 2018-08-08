---
layout: default
title: Establish ICAM Privacy Requirements
permalink: /pm-playbook/privacy-require/
collection: pm-playbook
---
---

All Federal agencies and programs that collect, retain, or use personal information are required to complete and maintain program documents to support these activities.

<blockquote>
<h3><p><i> "Federal information is a strategic asset subject to risks that must be managed to minimize harm; Protecting an individual’s privacy is of utmost importance. The Federal Government shall consider and protect an individual’s privacy throughout the information life cycle; While security and privacy are independent and separate disciplines, they are closely related, and it is essential for agencies to take a coordinated approach to identifying and managing security and privacy risks and complying with applicable requirements.” </i></p></h3>
<center> - OMB Circular A-130 </center>
</blockquote>

OMB Circular A-130 – Appendices I and II, provide requirements and guidance on how agencies can coordinate information security and privacy programs to interact cohesively. The policy gives agency heads the ultimate responsibility of meeeting the requirements of this Circular in protecting federal information resources and managing PII. Agency ICAM leaders should coordinate with their Senior Agency Official for Privacy (SAOP) and privacy office to review and implement privacy principles, procedures, and guidelines. To learn more about the processes you should complete so your agency can meet key privacy requirements, view [OMB Circular A-130](https://www.whitehouse.gov/sites/whitehouse.gov/files/omb/circulars/A130/a130revised.pdf){:target="blank"}.

* [Apply the Fair Information Practice Principles (FIPPS)](#apply-the-fair-information-practice-principles-fipps)
* [Complete a System of Records Notice (SORN)](#complete-a-system-of-records-notice-sorn)
* [Conduct a Privacy Impact Assessment (PIA)](#conduct-a-privacy-impact-assessment-pia)
* [Establish Redress Procedures](#establish-redress-procedures)
* [Establish a Risk Assessment Process](#establish-a-risk-assessment-process)
* [Apply specific NIST 800-53 rev4 (Appendix J) Privacy Controls](#apply-nist-800-53-rev4-appendix-j-privacy-controls)


### Apply the Fair Information Practice Principles (FIPPS)

ICAM programs involve the collecting, storing, sharing, and maintenance of PII. As such, your agency must implement solutions that actively support privacy protections and the widely-recognized FIPPs. Under the Privacy Act, which is based on FIPPs, your agency is required to have certain processes and procedures governing the use of PII in place. You should first assess those processes and procedures and determine whether the implementation of an ICAM program constitutes a new use of PII that requires adjustment of existing processes and procedures.

The table below provides a description of each of the FIPPs and gives practical implementation considerations for applying them within an ICAM program.

#### - FIPPS Implementation Considerations

| <center> FIPPS </center> | <center> Description </center> | <center> ICAM Considerations |
|----------------|--------------------------------|--------------------|
| **Access and Amendment** | Provide individuals with appropriate access to PII and appropriate opportunity to correct or amend PII. | Your agency should allow an individual ease of access to their PII as well as provide redress mechanisms in accordance with the Privacy Act that allow people to report and correct information that is inaccurate, lost, or compromised and damages resulting from incorrect authentication or unauthorized access. Redress mechanisms help enhance confidence in the program and promote individual participation |
| **Accountability** | Be accountable for complying with these principles, providing training to all employees and contractors who use PII. Agencies are also responsible for monitoring, auditing, and documenting the actual use of PII to demonstrate compliance with these principles and all applicable privacy protection requirements. | ICAM implementers should establish accountability measures to ensure that each of the FIPPs are appropriately applied and effectively protect users’ privacy. Such measures can include ICAM program audits and reviews by agency privacy and security officials. Agencies should address accountability for specific requirements, such as the M-07-16 requirement for annual certification of training for employees who handle PII. Clear accountability will promote confidence in ICAM programs. |
| **Authority** | Only create, collect, use, process, store, maintain, disseminate, or disclose PII that your agency has the authority to do so. The authority should also be identified in the appropriate notice. | Your agency should identify a specific authority for creating, collecting, using, processing, storing, maintaining, disseminating, or disclosing PII. |
| **Minimization** | Only collect PII that is directly relevant and necessary to accomplish the specified purpose(s) and only retain PII for as long as is necessary to fulfill the specified purpose(s). | Your agency should only collect the information necessary to carry out ICAM business functions. Wherever possible, your agency should use assertions of an individual’s identity in lieu of identifying data elements. For example, if an application has an age limitation, the program should ask for proof of age rather than the exact birth date. You should also determine how long specific categories of information associated with ICAM processes will be retained and implement procedures for destruction of the information at the end of the retention period. |
| **Data Quality and Integrity** | Ensure that PII is accurate, relevant, timely, and complete. | You agency should identify and implement means to ensure that PII is accurate, relevant, timely, and complete, including providing mechanisms for individuals to correct inaccuracies in their information. |
| **Individual Participation** | Involve the individual in the process of using PII. As practicable, your agency should seek individual consent for the collection, use, dissemination, and maintenance of PII. Your agency should also provide mechanisms for appropriate access, correction, and redress regarding use of PII. | If your agency interacts with the public face-to-face and/or engages by paper/telephone you must recognize that there will be people who will not feel comfortable adopting technological processes. Your agency should continue to offer physical alternatives for processes that are not inherently technology-based. <br><br> Your agency should also provide redress mechanisms in accordance with the Privacy Act that allow people to report and correct information that is inaccurate, lost, or compromised and damages resulting from incorrect authentication or unauthorized access. Redress mechanisms help enhance confidence in the program and promote individual participation |
| **Purpose Specification and Use Limitation** | Use PII solely for the purpose(s) specified in the notice. Sharing PII should be for a purpose compatible with the purpose for which the PII was collected. | The Privacy Act generally requires that once an individual consents to the collection of his information for a specific, stated purpose, that information can only be used for that purpose. This is particularly important to remember when considering the sharing of information between programs. If the programs have different purposes, such sharing will likely not be permissible without additional consent from the user. You should carefully consider this limitation when crafting your agency’s privacy ICAM program notices |
| **Security** | Protect PII (in all media) through appropriate security safeguards against risks such as loss, unauthorized access or use, destruction, modification, or unintended or inappropriate disclosure. | Your agency must ensure the security of information at all stages (collection, transmission, storage, destruction) in accordance with various legal and policy requirements (e.g., FISMA and OMB M-07-16). Examples of techniques for securing data are: <br><br> • Encryption <br> • Strong authentication procedures <br> • Time out functionality <br> • Minimum security controls to make information unusable by unauthorized individuals. |
| **Transparency** | Be transparent with respect to the information they collect and share, and provide notice to the individual regarding collection, use, dissemination, and maintenance of PII. | A foundational principle in federal privacy law is that people have the right to know what information the government collects and retains about them and, to a great extent, the right to control how that information is being used. When building ICAM programs consider this principle and ensure the following prior to each occurrence of information collection and/or transmission: <br><br> • The user is clearly informed what information elements will be collected <br> • The user understands who will receive the information <br> • The user is clearly informed of how the information will be used <br> • The user must affirmatively choose to participate before any information is transmitted |


### Complete a System of Records Notice (SORN)

A notice published by an agency in the Federal Register to notify the public of a system of record, a group of any records under the control of any agency from which information is retrieved by the name of an individual or by some identifying number, symbol, or other identifier assigned to the individual. The SORN includes basic information about the system, including system name, categories of individuals covered by the system, and categories of records in the system and addresses the policies and practices for storing, retrieving, accessing, retaining, and disposing of records in the system.

### Conduct a Privacy Impact Assessment (PIA)

The process used to evaluate the potential ramifications to the protection of privacy within IT systems. The resulting document includes information related to the data in the system, access to the data, attributes of the data, and maintenance of administrative controls for protecting it. An agency must complete a PIA whenever a new system is being introduced or an existing system is substantially modified.

### Establish Redress Procedures

Procedures to allow an individual to review his record in an IT system upon request and permit the individual to request amendment of a record pertaining to him. In addition to enabling an agency to meet the requirements of the Privacy Act of 1974, redress procedures also help enhance transparency, raise the awareness of the mission, and promote user confidence.

### Establish a Risk Assessment Process

To manage and maintain privacy risks, it is important that your agency establish a risk assessment process. Review the guidance below to gain a better idea of what is involved in the risk assessment process.

#### - NIST 800-63 Rev3 - Digital Identity Guidelines

Digital Identity Guidelines for privacy requirements and considerations to help mitigate potential associated privacy risks. The four volume set of guidelines combines risk management for security and privacy with mission needs by having agencies select assurance levels for individual functions being performed.

| **Volume** | **Guidance Name** | **Location in Document** |
| [NIST 800-63-3](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-63-3.pdf){:target="blank"}  | Digital Identity Guidelines |
| [NIST 800-63-3A](https://doi.org/10.6028/NIST.SP.800-63a){:target="blank"} | Enrollment and Identity Proofing Requirements | Section 8 |
| [NIST 800-63-3B](https://doi.org/10.6028/NIST.SP.800-63b){:target="blank"} | Authentication and Lifecycle Management | Section 9 |
| [NIST 800-63-3C](https://doi.org/10.6028/NIST.SP.800-63c){:target="blank"} | Federation and Assertions | Section 9 |


#### - NISTIR 8062 – An Introduction to Privacy Engineering and Risk Management in Federal Systems

Publication introduces privacy engineering objectives and a privacy risk model developed to help agencies “conduct more consistent privacy risk assessments based on the likelihood that an operation performed by a system would create a problem for individuals when processing PII” and the impact that the problem would have on those individuals. The publication also aligns itself well to the updated OMB Circular A-130 and its privacy requirements/guidance. Please click [here](https://nvlpubs.nist.gov/nistpubs/ir/2017/NIST.IR.8062.pdf){:target="blank"} to view the full guidance.


### Apply NIST 800-53 rev4 (Appendix J) Privacy Controls

Privacy controls developed to help organization leaders determine the best ways to incorporate effective privacy protections and practices for programs and/or systems that collect, use, maintain, share, or dispose of PII.

Specific privacy controls that address processes and procedures for consent, individual access, redress, and complaint management can be found in [NIST SP 800-53 Revision 4 - Appendix J](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r4.pdf){:target="_blank"}

{% include alert-warning.html heading = "Privacy Tip" content="We encourage ICAM implementers to provide redress mechanisms even when not required by the Privacy Act. Allowing users to file complaints and comments regarding an ICAM program and rectify this if their information is inaccurate, lost, or compromised will promote confidence in their interaction with the government." %}
