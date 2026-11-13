# Standalone worksheet · S__

**Target IP / hostname:**  
**OS / role:**  
**Panel objectives:**  
**Current identity and access:**  
**Next action / stop condition:**  

## Service inventory

| Port / protocol | Service and version evidence | Auth / exposed surface | Next test | Evidence ID |
| --- | --- | --- | --- | --- |
| | | | | |

For web services, record scheme, port, vhost, URL, method, parameter, auth state and response difference. For SMB/FTP/NFS, record share or export, access identity, permissions and the exact path of a useful artifact. For SSH or management services, record the identity and authentication method that was actually verified.

## Leads

| ID | Observation | Hypothesis and prerequisite | Test | Result / evidence | Next decision |
| --- | --- | --- | --- | --- | --- |
| L01 | | | | | |

When pausing, write the specific assumption that failed and what new evidence would justify reopening the lead.

## Initial access

- **Entry point and root cause:**
- **Prerequisite / identity:**
- **Exploit reference or manual technique:**
- **Exact commands and relevant output:**
- **Shell context (host, user, privileges):**
- **Evidence IDs and proof status:**

## Privilege escalation

| Surface | Evidence to record |
| --- | --- |
| Linux | Identity and groups, sudo policy, SUID/capabilities, scheduled jobs, services, file ownership and writable dependencies |
| Windows | Identity, groups, token privileges and integrity, service and task configuration, writable paths and ACLs |
| Both | Privileged execution context, what can be influenced, trigger, resulting identity |

- **Misconfiguration and affected path:**
- **Required rights and trigger:**
- **Exact commands and relevant output:**
- **Resulting shell context:**
- **Evidence IDs and proof status:**

## Replay log

Repeat this block for each material step.

### S__-STEP__

- **Runs on / as:**
- **Input or prior step:**
- **Command or request:**
- **Observed output:**
- **Why it matters:**
- **Evidence ID:**
