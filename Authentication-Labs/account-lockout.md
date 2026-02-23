### Account Lockout Investigation

**Scenario**
User unable to log in after repeated failed attempts.

**Investigation**
Reviewed Security logs in Event Viewer and filtered failed logon events (4625). Identified repeated authentication failures.

**Root Cause**
Multiple incorrect password attempts.

**Resolution**
Reset credentials and verified successful login.

**Tools**
Event Viewer
PowerShell

**Skills**
Authentication troubleshooting
Log analysis
