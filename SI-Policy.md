# [Company Name] System and Information Integrity Policy

## 1. Purpose of Policy
This Policy establishes the basis for implementing System and Information Integrity control practices for protecting information systems and data within [Company Name] [System Name].

Systems and information integrity is the assurance that data and information systems being accessed,  have neither been tampered with altered or compromised through system errors, malicious attacks and unauthorized access during operation and transmission.  The purpose of this policy is to ensure that [Company Name] establishes requirements for a comprehensive program for developing, implementing and maintaining relevant information to support system and information integrity objectives and security posture of the organization.

## 2. Scope of Policy
This policy applies to all users, systems, networks, components, services and processes in or accessing the [System Name]. This includes cloud infrastructure components, leveraged services and other elements used to deliver [System Name].

This policy is written to include the following:
* Flaw Remediation
* Malicious Code Protection
* Information system monitoring
* Security Alerts and Advisories
* Security Function Verification
* Software, Firmware and Information Integrity
* Spam Protection
* Information Input Validation
* Error Handling
* Information Handling and Retention
* Memory Protection

Please see the [Company Name] Governance Policy for further information on Management Commitment, Compliance and Enforcement, Review & Update processes, and Penalties.

## 3. Roles and Responsibilities
|Roles                  |Responsibilities
|-----------------------|---------------------------------------------------------------------------------------------------------|
|Development Operations | Maintain system integrity and protect all network and application services from potential threats to [System Name]
|Security Operations    | Monitors system integrity and threats to all [System Name] and networks and provide assistance to DevOps for Flaw remediation actions |
|Senior Director        | Ensuring the Policy is approved, implemented and communicated.|
|Director of Compliance | Owner of the Policy. Ensuring the Policy meets the compliance requirements.|

## 4. Policy
The access and use of Information Technology (IT) resources shall be in compliance with applicable Federal Information Processing Standards (FIPS) and National Institute of Standards and Technology (NIST) Special Publications, International Organization for Standards (ISO) and [Company Name] policies and standards.

### 4.1 Flaw Remediation
* [Company Name] shall identify information systems containing software affected by recently announced software flaws and reports this information to designated organizational officials with information security responsibilities (e.g., senior information security officers, information system security managers, information systems security officers).
* [Company Name] shall promptly install security-relevant software updates (e.g., patches, service packs, and hot fixes)  discovered during security assessments, continuous monitoring, incident response activities, or information system error handling, are also addressed expeditiously.
* [Company Name] must use resources such as the Common Weakness Enumeration (CWE) or Common Vulnerabilities and Exposures (CVE) databases in remediating flaws discovered within its information systems.
* Flaw remediation must be incorporated into the configuration management process, with the intention of tracking and verifying of required/anticipated remediation actions.

### 4.2 Malicious Code Protection
* [Company Name] shall employ malicious code protection mechanisms at information system entry and exit points on the network to detect and eradicate malicious code that is:
 * Transported by electronic mail, electronic mail attachments, web accesses, removable media, or other common means or inserted through the exploitation of information system vulnerabilities.
* Update malicious code protection mechanisms (including signature definitions) whenever new releases are available in accordance with organizational configuration management policy and procedures.
* Implement secure coding practices, configuration management and control, trusted procurement processes, and monitoring practices for additional malicious code protection
* All malicious code protection mechanisms must be configured to:
 * Perform periodic scans of information systems and real-time scans of files from external sources as the files are downloaded, opened, or executed in accordance with organizational security policy
 * Block malicious code, quarantine malicious code, and send alerts to administrator in response to malicious code detection
* Address the receipt of false positives during malicious code detection and eradication and the resulting potential impact on the availability of the information system.
* [Company Name] shall centrally manage virus protection mechanisms that automatically update malicious code protection mechanisms (including signature definitions) and prevent non-privileged users from circumventing malicious code protection capabilities.

### 4.3 Information System Monitoring
* [Company Name] must monitor information systems to detect attacks and indicators of potential attacks of unauthorized local, network, and remote connections in accordance with continuous monitoring and incident response requirements
* Identify unauthorized use of the information system through deployed intrusion detection systems, intrusion prevention systems, malicious code protection software, scanning tools, audit record monitoring software and network monitoring software
* Deploy monitoring devices strategically within the information system to collect organization-determined essential information and at ad hoc locations within the system to track specific types of transactions of interest to the organization
* Protects information obtained from intrusion-monitoring tools from unauthorized access, modification, and deletion
* Heighten the level of information system monitoring activity whenever there is an indication of increased risk to organizational operations and assets, individuals, other organizations, or the Nation based on law enforcement information, intelligence information, or other credible sources of information
* Obtains legal opinion with regard to information system monitoring activities in accordance with applicable federal laws, Executive Orders, directives, policies, or regulations; and
* Provides all information system monitoring information to senior information security officers, information system security managers, and information systems security officers as needed and on a continual basis.

### 4.4 Security Alerts, Advisories and Directives
* [Company Name] shall receive information system security alerts/advisories on a regular basis from the US-Cert and other sources such as the National Vulnerability database (NVD)
* Generate internal security alerts, advisories, and directives as deemed necessary and disseminate to senior information security officers, information system security managers, and information systems security officers, systems owners, incident response teams and external agencies including Department of Homeland Security (DHS), and OPM
* Implements an appropriate action in response to security directives in accordance with established time frames, or notifies the issuing organization of the degree of noncompliance.
* [Company Name] shall employ automated mechanisms to make security alert and advisory information available throughout the organization as appropriate.

### 4.5 Security Function Verification
* All information systems must verify the correct operation of transitional states which include system startup, restart, shutdown, and abort functions
* Performs verification of system startup, restart, shutdown, and abort functions upon command by approved users with appropriate privileges in real time
* Notifies senior information security officers, information system security managers, and information systems security officers of failed security verification tests and shuts down or restarts the information system when anomalies are discovered.

### 4.6 Software, Firmware and Information integrity
* [Company Name] will employ integrity verification applications on its information systems to look for evidence of information tampering, errors, and omissions.
* [Company Name] must employ good software engineering practices with regard to commercial off-the-shelf integrity mechanisms (e.g., parity checks, cyclical redundancy checks, cryptographic hashes).
* [Company Name] shall use tools to automatically monitor the integrity of the information systems it hosts and incorporate the detection of unauthorized access, system changes, communications or elevation of information system privileges into the organizational incident response capability.

### 5.7 Spam Protection
* [Company Name] shall employ spam protection mechanisms at information system entry and exit points on the network to detect and take action on unsolicited messages transported by electronic mail, electronic mail attachments, web accesses, or other common means.
* [Company Name] should provide the capability to automatically updates spam protection mechanisms (including signature definitions) when new releases are available in accordance with organizational configuration management policy and procedures.

### 4.8 Information Input Validation
* [Company Name] shall restrict the information input to the information system to authorized personnel only and check information system inputs (e.g., character set, length, numerical range, acceptable values) for accuracy, completeness and validity.

### 4.9 Error Handling
* All information systems must provide the capability to generate error messages that provide information necessary for corrective actions without revealing sensitive or potentially harmful information in error logs and administrative messages that could be exploited by adversaries.

### 4.10 Information Handling and Retention
* [Company Name] shall handle and retains both information within and output from its information systems in accordance with organizational policy and operational requirements.

### 4.11 Memory Protection
* All information systems must implement forms of data execution prevention and address space layout randomization to protect its memory from unauthorized code execution.
