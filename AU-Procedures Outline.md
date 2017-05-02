# [Company Name] AU Procedures Outline
## 1. Purpose of Procedures
Procedures are designed to support the requirements from the [Company Name] Policies.  Procedures ensure actions are consistent across the whole team, ensure all steps are completed, and are used as training material for new members.

## 2. Scope of Procedures
These Procedures are to be used in support of the [System Name].

This procedure is written to include the following:
* Audit Events
* Content of Audit Records
* Response to Audit Processing Failures
* Audit Review, Analysis, and Reporting
* Audit Reduction and Report Generation
* Protections of Audit Information
* Audit Record Retention
* Audit Generation

Please see the [Company Name] Audit and Accountability Policy for further information on the policy requirements.

## 3. Procedures
### 3.1.	Audit Events
#### 3.1.1.	Events to be identified within the server logs
* Successful and unsuccessful account logon events
* Account management events
* Object access
* Policy change
* Privilege functions
* Process tracking
* System events

#### 3.1.2.	For Web applications
* All administrator activity
* Authentication checks
* Authorization checks
* Data deletions
* Data access
* Data changes
* Permission changes

#### 3.1.3.	CloudTrail
#### 3.1.4.	[System Name] Component Audit Events
#### 3.1.5.	Coordination
### 3.2.	Content of Audit Records
#### 3.2.1.	Audit records contain information that establishes:
* What type of event occurred
* When the event occurred
* Where the event occurred
* Source of the event
* Outcome of the event
* Identity of any individuals or subjects associated with the event

#### 3.2.2.	Audit record types
* Session, connection, transaction, or activity duration
* For client-server transactions, the number of bytes received and bytes sent
* Additional informational messages to diagnose or identify the event
* Characteristics that describe or identify the object or resource being acted upon

### 3.3.	Response to Audit Processing Failures
Audit processing failures are identified and alerted through the following support tools:
* [Tool Name]
* [Second Tool Name]
If the audit storage capacity has been reached, [Company Name] will stop aggregating the specific event and audit logs from streaming to the [Tool Name] and send out an alert through automated mechanisms [examples] to immediately alert processing failures.

In the event that a local log file capacity is reached, older log entries are removed automatically to allow new entries to be posted, as logs are forwarded to the [Tool Name] centralized log collection tool. Alerts of an audit processing issue or failure are sent to [Team Name] to remediate the issue, which includes:
* Placing the device in a separate isolated subnet
* Disconnecting the device from the network
* Shut down the corresponding application
* Shut down the device

### 3.4.	Audit Review, Analysis, and Reporting
The [Company Name] Security Operations team monitors and reviews audit logs via [Audit Tool] for unapproved and unusual activities on a continual basis. Reporting rules have been developed to look for, identify, and report potentially inappropriate or unusual activity to be reviewed regularly within the audit tools dashboard as well as regular reports that are automatically generated on a weekly basis. Findings are reported to the ISSO.

The [Audit Tool] User Guide is located at:


#### 3.4.1.	Reporting -Periodic reports include but are not limited to the following:
#### 3.4.1.1.	Daily
* Operating System crashes
* Newly installed services
* Execution of privileged functions
* Execution of privileged services
* Account management events
* Account Authentication events
* Two-Factor Authentication events
* AV/Malware management events
* Backup events
* Web application events

#### 3.4.1.2.	Weekly
* Newly installed services
* Operating System time changes
* Object access and permission events
* AV/Malware update events
* Account Authentication events
* Two-Factor Authentication events
* Web application events

#### 3.4.1.3.	Monthly reports
* Vulnerability summary
* POA&M Updates (open, closed, and inventory)
* Asset verification

### 3.5.	Audit Reduction and Report Generation
### 3.6.	Protections of Audit Information
### 3.7.	Audit Record Retention
#### 3.7.1.	90 days online
#### 3.7.2.	Nara
##### 3.7.2.1.	Information technology operations and maintenance records – Keep a minimum of 3 years after agreement, control measures, procedures, project, activity, or transaction is obsolete, completed, terminated, or superseded
##### 3.7.2.2.	System access records – Keep a minimum of 6 years after a password is altered or user account is terminated.

### 3.8.	Audit Generation
