# [Company Name] Configuration Management Policy

## 1. Purpose of Policy
This Policy establishes the basis for implementing Configuration Management control practices for protecting information systems and data within [Company Name] [System Name].

Configuration Management (CM) comprises a collection of activities focused on establishing and maintaining the integrity of products and systems, through control of the processes for initializing, changing, and monitoring the configurations of those products and systems.  

## 2. Scope of Policy
This policy applies to all users, systems, networks, components, services and processes in or accessing the [System Name]. This includes cloud infrastructure components, leveraged services and other elements used to deliver [System Name].

This policy is written to include the following
* Baseline Configuration
* Configuration Change Control
* Security Impact Analysis
* Access Restrictions for Change
* Configuration Settings
* Least Functionality
* Information System Component Inventory
* Configuration Management Plan

Please see the [Company Name] [Governance Policy](https://github.com/ScaleSec/compliance-docs/blob/P%26P-master/Policy%20Templates/Gov-Policy.md#governance-policy) for further information on Management Commitment, Compliance and Enforcement, Review & Update processes, and Penalties.

#### 3. Roles and Responsibilities
|Roles                 | Responsibilities                                                                        |
|----------------------|-----------------------------------------------------------------------------------------|
|Development Operations| Maintains baseline configuration management of information systems and networks for [Company Name] |
|Security Operations   | Reviews configuration settings implemented on the system per established baseline configurations|
|Senior Director       | Ensuring the Policy is approved, implemented and communicated.|
|Director of Compliance| Owner of the Policy. Ensuring the Policy meets the compliance requirements.|

## 4. Policy
The access and use of Information Technology (IT) resources shall be in compliance with applicable Federal Information Processing Standards (FIPS) and National Institute of Standards and Technology (NIST) Special Publications, International Organization for Standards (ISO) and [Company Name] policies and standards

### 4.1 Baseline Configuration
* [Company Name] develops and maintains documentation on the baseline configuration of the information system to include such things as, but not limited to:
  * Network topology;
  * System architecture;
  * Application, Web and Server components
  * Software standards
* [Company Name] reviews baseline configuration settings on a continual basis and provide annual updates as required due to federal mandates and compliance standards.
* [Company Name] retains any and all necessary baseline configuration as deemed necessary to support rollback functions and incident response.
* [Company Name] develops and maintains a list of software programs/applications that are not authorized to execute on the information system, and employs an allow-all, deny-by-exception authorization policy to identify software allowed to execute on the information system.

### 4.3 Configuration Change Control
* [Company Name] documents changes to the baseline configuration in the following manner:
  1. Determines the types of changes to the information system that are configuration controlled
  2. Changes require security impact analyses conducted on all configuration-controlled changes
  3. Maintain documentation for approved configuration-controlled changes
  4. Provides record retention for review of configuration-controlled changes at a minimum of 1 year
  5. Coordinates and provides oversight for configuration change control activities through tracking and monitoring systems that evaluates configuration changes  through a continuous development lifecycle
* [Company Name] tests, validates, and documents changes to the information system before implementing the changes on an operational system.

### 4.4 Security Impact Analysis
* [Company Name] conducts a thorough security analysis of the proposed change prior to the configuration change being implemented within an operational system. Proposed and defined major changes may include:
  * an increase in the sensitivity or criticality of a system
  * an increase in threat level
  * policy change
  * a change in operating system (base platform)
  * a change to security relevant software
  * installations and upgrades
  * An increase in interconnection with other systems outside the accreditation boundary
  * Significant changes in the security requirements that apply to the system

### 4.5 Access Restriction for Change
* [Company Name] ensures only pre-defined authorized users are allowed to make any changes to either the physical or logical environment that:
  * Defines approval process for access; and
  * Defines and documents access roles;
  * Retains records for express purpose for auditing purposes.

### 4.6 Configuration Settings
* [Company Name] documents the baseline configuration settings such that:
 * Mandatory configuration settings for information technology products utilized within the information system using best practices, federally approved configuration checklists,  hardening guides and standard compliance settings that reflect the most restrictive mode consistent with operational requirements
 * Implements the configuration setting within the information systems and components
 * Identifies, documents, and approves exceptions from the mandatory configuration setting
 * Monitors and controls changes to the configuration setting in accordance with [Company Name] policies and procedures.
* [Company Name] incorporates a detection of unauthorized, security-relevant configuration changes into [Company Name] incident response capability to ensure that such detected events are tracked, monitored, corrected, and available for historical purposes.

### 4.7 Least Functionality
*  [Company Name] only grants access to information in a manner that provides only essential capabilities and specifically required  or restricts the use of the functions, ports, protocols, and/or services based on organizational policy and security requirements
* [Company Name] conducts on-going and monthly reporting audit of information system which identifies and eliminates unnecessary functions, ports, protocols, and/or services.  

### 4.8 Information System Component Inventory
* [Company Name] develops, documents, and maintains inventory of information system components that:
 * Accurately reflects the current information system;
 * Is consistent with the authorization boundary of the information system;
 * Is at the level of granularity deemed necessary for tracking and reporting;
 * Includes [timeframe] archival of information system; and
 * Is available for review and audit by designated officials.
* [Company Name] updates inventory of information system whenever installations, removals, and other changes are made.
* [Company Name] verifies all components within the authorized boundary of the information system are either inventoried as part of the system or recognized by another system as a component within that system.

### 4.9 Configuration Management Plan
* [Company Name] develops a configuration management plan that:
 * Addresses roles, responsibilities, and configuration management processes and procedures;
 * Defines the configuration items for the information system and when in the system development life cycle the configuration items are placed under configuration management; and
 * Establishes the means for identifying configuration items throughout the system development life cycle and a process for managing the configuration of the configuration items.
