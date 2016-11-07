# [Company] Access control Policy

## 1. Purpose of Policy
Access to [Company] computing resources is granted in a manner that carefully balances restrictions designed to prevent unauthorized access against the need to provide unhindered access to informational assets.

This Policy establishes the basis for implementing secure access control practices for protecting information systems and data within [Company] systems, products and networks.

The purpose of this policy is to ensure that [Company] establishes requirements for a comprehensive program for developing, implementing and maintaining relevant information to support system and information integrity objectives and security posture of the organization

## 2. Scope of Policy
This policy applies to all users, systems, networks, components, services and processes in or accessing the [Company] Production environment, and all services, applications and products in General Availability.  This includes cloud infrastructure components, leveraged services and other elements used to deliver [Company] products and services.

Please see the [Company] Governance Policy for further information on Management Commitment, Compliance and Enforcement, Review & Update processes, and Penalties.

## 3. Roles and Responsibilities
|Roles                    | Responsibilities
|-------------------------|------------------------------------------------------------------------------------------------------|
|Security Operations      |Monitor access to the infrastructure and information systems. Review and enforce access controls.|
|Development Operations   |Implement access controls within information systems and network.|
|Senior Director          |Ensuring the Policy is approved, implemented and communicated.|
|Director of Compliance   |Owner of the Policy. Ensuring the Policy meets the compliance requirements.|

## 4. Policy
The access and use of Information Technology (IT) resources shall be in compliance with applicable Federal Information Processing Standards (FIPS) and National Institute of Standards and Technology (NIST) Special Publications, International Organization for Standards (ISO) and [Company] policies and standards.

### 4.1 Access Management
* All users are required to have unique system accounts created for use on [Company] information systems including individual, group, system, application accounts.
* [Company] establishes conditions for group membership based on business needs and roles.
* [Company] identifies authorized users of the information system and specify access privileges.
* Appropriate approvals are required for requests to establish user and system accounts on [Company] information systems.
* [Company] establishes, maintains, and fully documents procedures to establish, activate, modify, review, disable, and remove accounts.
   * Specifically authorizing and monitoring the use of guest/anonymous and temporary accounts if necessary
* Notification is submitted to account managers when temporary accounts are no longer required and when information system users are terminated, transferred, or information system usage or need-to-know/need-to-share changes
* [Company] requires deactivation of temporary accounts that are no longer required, accounts of terminated or transferred users
* All Access must be granted based on: (i) a valid access authorization; (ii) intended system usage; and (iii) other attributes as required by the [Company] missions/business functions
* All system accounts will be reviewed at a minimum on an annual basis with periodic reviews when necessary for auditing purposes.

### 4.2 Access Enforcement
* [Company] enforces approved authorizations for logical access to its information systems in accordance with all applicable Federal, and [Company] policies.
* [Company] provides access enforcement through the use of access control lists, access control matrices, cryptography) to control access between users (or processes acting on behalf of users) and objects (e.g., devices, files, records, processes, programs, domains) in the information system.
* [Company] employs access enforcement mechanisms at the application level, when necessary, to provide increased information security for the organization

### 4.3 Information Flow enforcement
* [Company] enforces approved authorizations for controlling the flow of information within its information systems and between interconnected systems in accordance with applicable federal laws and [Company] policies and procedures.
* [Company] uses flow control restrictions to include: keeping export controlled information from being transmitted in the clear to the Internet, blocking outside traffic that claims to be from within the organization and not passing any web requests to the Internet that are not from the internal web proxy.  
* [Company] uses boundary protection devices (e.g., proxies, gateways, guards, encrypted tunnels, firewalls, and routers) that employ rule sets or establish configuration settings that restrict information system services, provide a packet-filtering capability based on header information, or message-filtering capability based on content (e.g., using key word searches or document characteristics.

### 4.4 Separation of Duties
* [Company] separates duties of individuals as necessary, to prevent malevolent activity without collusion;
* [Company] documents separation of duties; and  implements separation of duties through assigned information system access authorizations
* [Company] uses separation of duties to include:
* Mission functions and distinct information system support functions are divided among different individuals/roles
* Different individuals perform information system support functions (e.g., system management, systems programming, configuration management, quality assurance and testing, network security)
* Security personnel who administer access control functions do not administer audit functions
Different administrator accounts for different roles.
* [Company] uses automated mechanisms to assist in the control and auditing of separation of duties functions within its information systems.
* When a conflict of separation of duties is identified, compensating controls shall be established and employed

### 4.5 Least Privilege
* [Company] employs the concept of least privilege, allowing only authorized accesses for users (and processes acting on behalf of users) which are necessary to accomplish assigned tasks in accordance with organizational missions and business functions.
Approvals are granted by an appropriate approval process and be restricted to those authorized to access by state or federal laws.
* [Company] requires that users of information system accounts, or roles, with administrator or root access to information systems, use non-privileged accounts, or roles, when accessing other system functions, and if feasible, audits any use of privileged accounts, or roles, for such functions.
* [Company] controls and restricts physical and logical access to diagnostic and configuration ports, restricts access to operating systems, restricts access the use of utility programs that might be capable of overriding system and application controls, restricts access and connection times to the minimum necessary to accomplish a task, and restricts access to program source code.

### 4.6 Unsuccessful Login attempts
* [Company] enforces a limit of three (3) consecutive invalid login attempts by a user during a 15 minute time period
* [Company] information systems automatically locks the account/node until released by an administrator according to [Assignment: organization-defined delay algorithm] when the maximum number of unsuccessful attempts is exceeded.

### 4.7 System Use Notification
* All [Company] information system logins display an approved system use notification message or banner before granting access to the system that provides privacy and security notices consistent with applicable federal laws, Executive Orders, directives, policies, regulations, standards, and guidance and states that: (i) users are accessing a U.S. Government information system; (ii) system usage may be monitored, recorded, and subject to audit; (iii) unauthorized use of the system is prohibited and subject to criminal and civil penalties; and (iv) use of the system indicates consent to monitoring and recording;
* All [Company] information systems retain the notification message or banner on the screen until users take explicit actions to log on to or further access the information system.

### 4.8 Session Lock
* [Company] information systems prevents further access to the system by initiating a session lock after a period of 20 minutes or less of inactivity or upon receiving a request from a user
* [Company] information systems retain the session lock until the user reestablishes access using established identification and authentication procedures.

### 4.9 Permitted Actions without Identification and Authorization
* [Company] permits actions to be performed without identification and authentication only to the extent necessary to accomplish  mission/business objectives. This would include when individuals access public websites or other publicly accessible federal information systems

### 4.10 Remote Access
* [Company] shall define, document and enforce requirements, usage restrictions and implementation guidance for each allowed remote access method.
* All remote and Virtual Private Network (VPN) access shall require multi-factor authentication.
* Access shall be authorized before a connection may be established.
* [Company] must monitor for unauthorized remote access and shall take appropriate action if unauthorized access is discovered.
* Remote access must employ cryptography to protect session confidentiality and integrity.
* Remote access must be routed through a limited number of managed access control points.
* Privileged commands and access to security-relevant information via remote access shall only be permitted by designated [Company] Staff.

### 4.11 Wireless Access
* [Company] shall define, document and enforce requirements, usage restrictions and implementation guidance for wireless access.
* Wireless access shall be authorized before a connection may be established.
* [Company] shall monitor for unauthorized wireless access and shall take appropriate action if unauthorized access is discovered.
Wireless access shall employ cryptography to protect session confidentiality and integrity.

### 4.12 Use of External information systems
* The organization establishes terms and conditions, consistent with any trust relationships established with other organizations owning, operating, and/or maintaining external information systems, allowing authorized individuals to:
 * Access the information system from the external information systems
 * Process, store, and/or transmit organization-controlled information using the external information systems.

### 4.13 Publicly Accessible content
* [Company] must designate individuals authorized to post information onto an organizational information system that is publicly accessible
* [Company] must train authorized individuals to ensure that publicly accessible information does not contain nonpublic information
* [Company] must review the proposed content of publicly accessible information for nonpublic information prior to posting onto the information system
* [Company] must review the content on the publicly accessible organizational information system for nonpublic information at least quarterly
* [Company] must remove nonpublic information from the publicly accessible organizational information system, if discovered.

