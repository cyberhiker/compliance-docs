# [Company Name] Identification and Authentication Policy

## 1. Purpose of Policy
This Policy establishes the basis for implementing Identification and Authentication control practices for protecting information systems and data within [Company Name] [System Name].

Access to [Company Name] computing resources is granted in a manner that carefully balances restrictions designed to prevent unauthorized access against the need to provide unhindered access to informational assets.

## 2. Scope of Policy
This policy applies to all users, systems, networks, components, services and processes in or accessing the [System Name]. This includes cloud infrastructure components, leveraged services and other elements used to deliver [System Name].

This policy is written to include the following:
* Identification and Authentication (Organizational Users)
* Device Identification and Authentication
* Identifier Management
* Authenticator Management
* Authenticator Feedback
* Cryptographic Module Authentication
* Identification and Authentication (Non-organizational Users)

Please see the [Company Name] Governance Policy for further information on Management Commitment, Compliance and Enforcement, Review & Update processes, and Penalties.

## 3. Roles and Responsibilities
|Roles                           | Responsibilities|
|--------------------------------|--------------------------------------|
|Development Operations          | Implement and ensure the security of identity and authentication for [System Name].|
|Security Operations             | Monitor and ensure all identity and authentication mechanisms implemented within the [Company Name] environment meet security requirements|
|[Company Name] Information Security Office | Provide recommendations, guidance on the identity and authentication management within the [Company Name] organization|
|Senior Director        | Ensuring the Policy is approved, implemented and communicated.|
|Director of Compliance | Owner of the Policy. Ensuring the Policy meets the compliance requirements.|

## 4. Policy
The access and use of Information Technology (IT) resources shall be in compliance with applicable Federal Information Processing Standards (FIPS) and National Institute of Standards and Technology (NIST) Special Publications, and [Company Name] policies and standards.

### 4.1 Identification and Authentication (Organizational Users)
* All users are required to have unique system accounts created for use on [System Name] including individual, group, system, application accounts
* [Company Name] establishes conditions for group membership based on business needs and roles
* [Company Name] identifies authorized users of the information system and specify access privileges
* All Access must be granted based on: (i) a valid access authorization; (ii) intended system usage; and (iii) other attributes as required by the [Company Name] missions/business functions
* All system accounts are reviewed at a minimum on an annual basis with periodic reviews when necessary for auditing purposes.

### 4.2 Device Identification and Authentication
* [Company Name] defines the specific and/or types of devices for which identification and authentication is required before establishing a connection to the information system
* [System Name] uniquely identifies and authenticates the organization-defined devices before establishing a connection to the information system.
* [Company Name] uses either shared known information (e.g., Media Access Control [MAC] or Transmission Control Protocol/Internet Protocol [TCP/IP] addresses) for identification or an organizational authentication solution (e.g., IEEE 802.1x and Extensible Authentication Protocol [EAP], Kerberos, Secure Shell (SSH) to identify and authenticate devices on local and/or wide area networks.

### 4.3 Identifier Management
* [Company Name] manages information system identifiers for users and devices by:
 * Receiving authorization from a designated organizational official to assign a user or device identifier.
 * Selecting an identifier that uniquely identifies an individual or device.
 * Assigning the user identifier to the intended party or the device identifier to the intended device.
 * Preventing reuse of user or device identifiers.
 * Disabling the user identifier after ninety (90) days of inactivity for general user accounts and thirty (30) days for administrator level accounts.

### 4.4 Authenticator Management
* [Company Name] manages information system authenticators (e.g., tokens, PKI certificates, biometrics, passwords, and key cards) by:
* Verifying, as part of the initial authenticator distribution, the identity of the individual, group, role, or device receiving the authenticator
* Establishing initial authenticator content for authenticators defined by the [Company Name]
 * Minimum length 20 characters
 * At least  1 upper case character
 * At least  1 lower case character
 * At least  1 digit
 * At least  1 special character
* Ensuring that authenticators have sufficient strength of mechanism for their intended use
* Establishing and implementing administrative procedures for initial authenticator distribution, for lost/compromised or damaged authenticators, and for revoking authenticators
* Changing default content of authenticators prior to information system installation
* Establishing minimum and maximum lifetime restrictions and reuse conditions for authenticators
* Changing/refreshing authenticators every sixty (60) days for user accounts every ninety (90) days for administrative accounts
* Protecting authenticator content from unauthorized disclosure and modification
* Requiring individuals to take, and having devices implement, specific security safeguards to protect authenticators
* Changing authenticators for group/role accounts when membership to those accounts changes

### 4.5 Authenticator Feedback
* [System Name] ensures to provide feedback to a user during an attempted authentication and that feedback does not compromise the authentication mechanism.

### 4.6 Cryptographic Module Authentication
* [Company Name] ensures information systems implements mechanisms for authentication to a cryptographic module that meet the requirements of applicable federal laws, Executive Orders, directives, policies, regulations, standards, and guidance for such authentication

### 4.7 Identifier Lockout
* [Company Name] enforces a limit of five (5) consecutive invalid login attempts by a user during a sixty minute (60) time period
* [System Name] automatically locks the account/node until released by an administrator; delays next login prompt according to five (5) minutes when the maximum number of unsuccessful attempts is exceeded

### 4.8 Identification and Authentication (Non-Organizational Users)
* [System Name] uniquely identifies and authenticates non-organizational users (or processes acting on behalf of non-organizational users).
* Non-organizational users include all information system users other than [Company Name] users explicitly covered by 4.1. Users are uniquely identified and authenticated for all accesses other than those accesses explicitly identified and documented by [Company Name].
