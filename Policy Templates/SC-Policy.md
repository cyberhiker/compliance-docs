# [Company Name] Systems and Communications Protection Policy

## 1. Purpose of Policy
This Policy establishes the basis for implementing Systems and Communications Protection control practices for protecting information systems and data within [Company Name] [System Name].

System Communication protection is the process of implementing protective measures both logically and physically to ensure consistent, uninterrupted, and tamper resistant availability of communication channels and data are provided to information systems and users who require access to the data. The purpose of this policy is to establish the basis for implementing system and communications practices for protecting information systems and data within [Company Name] systems, products and networks.

## 2. Scope of Policy
This policy applies to all users, systems, networks, components, services and processes in or accessing the [System Name]. This includes cloud infrastructure components, leveraged services and other elements used to deliver [System Name].

This policy is written to include the following
* Application Partitioning
* Information in Shared Resources
* Denial of Service Protection
* Resource Availability
* Boundary Protection
* Transmission Confidentiality and Integrity
* Network Disconnect
* Cryptographic Key Establishment and Management
* Use of Cryptography
* Collaborative Computing Devices
* Public Key Infrastructure Certificates
* Mobile Code
* Voice Over Internet Protocol
* Secure Name / Address Resolution Service  (Authoritative Source)
* Secure Name / Address Resolution Service (Recursive or Caching Resolver)
* Architecture and Provisioning for Name Address Resolution Service
* Session Authenticity
* Protection of Information at Rest
* Process Isolation

Please see the [Company Name] [Governance Policy](https://github.com/ScaleSec/compliance-docs/blob/P%26P-master/Policy%20Templates/Gov-Policy.md#governance-policy) for further information on Management Commitment, Compliance and Enforcement, Review & Update processes, and Penalties.

## 3. Roles and Responsibilities
|Roles                  | Responsibilities                                                                                     |
|-----------------------|------------------------------------------------------------------------------------------------------|
|DevOps                 | Ensure the safety and security of data on network and the equipment used to run the network infrastructure. |
|Senior Director        | Ensuring the Policy is approved, implemented and communicated.|
|Director of Compliance | Owner of the Policy. Ensuring the Policy meets the compliance requirements.|

## 4. Policy
The access and use of Information Technology (IT) resources shall be in compliance with applicable Federal Information Processing Standards (FIPS) and National Institute of Standards and Technology (NIST) Special Publications, International Organization for Standards (ISO) and [Company Name] policies and standards.

### 4.1 Application Partitioning
* [System Name] separates user functionality (including user interface services) from information system management functionality and implement separate authentication methods for privileged user access
* [System Name] uses logical separation through the use of routers, domains, virtualization, network addresses
* [System Name] uses of multi-factor authentication and Role based access controls.
* [Company Name] partitions its information systems into components residing in separate logical domains (or environments) as deemed necessary.

### 4.2 Information Shared Resources
* [System Name] prevents unauthorized and unintended information transfer via shared system resources.

### 4.3 Denial of Service Protection
* [System Name] protects against or limits the effects of denial of service (DoS) attacks including, but not limited to, Buffer Overflow attacks, Smurf attacks, PING of DEATH attacks, Teardrop attacks, SYN attacks; virus-induced DoS.
* [System Name] restricts the ability of users to launch denial of service attacks against other information systems or networks
* [System Name] has the capability to manage excess capacity, bandwidth, or other redundancy to limit the effects of information flooding types of denial service attacks
* [Company Name] uses a combination of intrusion detection/prevention systems, firewalls, gateways, network/security operation centers, harden configuration settings, antivirus, malware mechanisms to assist in denial of service protection

### 4.4 Resource Availability
* [System Name] protects the availability of resources by allocating [organization-defined resources] by [Selection (one or more); priority; quota; [organization-defined security safeguards]].

### 4.5 Boundary Protection
* [System Name] monitors and controls communications at the external boundary of the information system and at key internal boundaries within the system.
* [Company Name] connects to external networks or information systems only through managed interfaces consisting of boundary protection devices arranged in accordance with approved security architecture.
* [Company Name] logically allocates publicly accessible information system components to separate sub-networks with separate logical network interfaces
* [System Name] prevents public access into the organizations internal networks except as appropriately mediated by managed interfaces employing boundary protection devices.
* [Company Name] limits the number of access points to the information system to allow for more comprehensive monitoring of inbound and outbound communications and network traffic.
* [System Name] denies network traffic at managed interfaces by default and allows network traffic by exception (i.e., deny all, permit by exception).
* [System Name] prevents remote devices that have established a non-remote connection with the system from communicating outside of that communications path with resources in external networks.

### 4.6 Transmission Confidentiality and Integrity
* [System Name] protects the confidentiality and integrity of transmitted information.
* [Company Name] employs cryptographic mechanisms to prevent unauthorized disclosure of information during transmission unless otherwise protected by alternative physical measures.

### 4.7 Network Disconnect
* [System Name] terminates the network connection associated with a communications session at the end of the session or after 20 minutes of inactivity.

### 4.8 Cryptographic Key Establishment and Management
* [System Name] employs automated mechanisms with supporting procedures or manual procedures for cryptographic key establishment and key management.
* [Company Name] defines key management requirements in accordance with applicable federal laws, Executive Orders, directives, regulations, policies, standards, and guidance, specifying appropriate options, levels, and parameters.
* [Company Name] manages trust stores to ensure that only approved trust anchors are in such trust stores. This includes certificates with visibility external to organizational information systems and certificates related to the internal operations of

### 4.9 Use of Cryptography
* [System Name] implements required cryptographic protections using cryptographic modules that comply with applicable federal laws, Executive Orders, directives, policies, regulations, standards, and guidance.
* The information system implements applicable NSA-approved cryptography, provision of digital signatures and FIPS-validated cryptography in accordance with applicable federal laws, Executive Orders, directives, policies, regulations, and standards.

### 4.10 Public Access Protections
* For publicly available systems, [System Name] protects the integrity of the information and applications.

### 4.11 Collaborative Computing Devices
* [System Name] prohibits remote activation of collaborative computing mechanisms (e.g., video and audio conferencing) and provides an explicit indication of use to the local users (e.g., use of camera or microphone).

### 4.12 Public Key Infrastructure Certificates
* [Company Name] develops and implements a certificate policy and certification practice statement for the issuance of public key certificates used in the information systems.

### 4.13 Mobile Code
* [Company Name] establishes usage restrictions and implementation guidance for mobile code technologies based on the potential to cause damage to the information system if used maliciously.
* [Company Name] documents, monitors, and controls the use of mobile code within the information system.

### 4.14 Voice over Internet Protocol
* [Company Name] establishes usage restrictions and implementation guidance for Voice over Internet Protocol (VoIP) technologies based on the potential to cause damage to the information system if used maliciously.
* [Company Name] authorizes, monitors, and controls the use of VoIP within the information system if applicable.

### 4.15 Secure Name / Address Resolution Service (Authoritative Source)
* [Company Name] provides additional data origin authentication and integrity verification artifacts along with the authoritative name resolution data any system returns in response to external name/address resolution queries.
* [Company Name] provides the means to indicate the security status of child zones and (if the child supports secure resolution services) to enable verification of a chain of trust among parent and child domains, when operating as part of a distributed, hierarchical namespace.
* [Company Name] leverages approved DNS services provided by authorized cloud infrastructure providers as needed for its information systems.

### 4.16 Architecture and Provisioning for Name / Address Resolution Service
* [Company Name] implements name/address resolution using domain name system (DNS) servers that are fault-tolerant and implement internal/external role separation.
* [Company Name] eliminates single points of failure and enhance redundancy, by implementing multiple authoritative domain name system (DNS) servers or by leveraging approved DNS services from a third party.
* DNS servers with an internal role only process name/address resolution requests from within the organization (i.e., internal clients). DNS servers with an external role only process name/address resolution information requests from clients external to the organization (i.e., on the external networks including the Internet).
* The set of clients that can access an authoritative DNS server in a particular role is specified by the [Company Name].

### 4.17 Session Authenticity
* [System Name] protects the authenticity of communications sessions.

### 4.18 Protection of Information at Rest
* [System Name] protects the confidentiality and integrity of information at rest by employing cryptographic mechanisms to prevent unauthorized disclosure and modification of information at rest unless otherwise protected by alternative physical measures.

### 4.19 Process Isolation
* [System Name] maintains a separate execution domain for each executing process.
