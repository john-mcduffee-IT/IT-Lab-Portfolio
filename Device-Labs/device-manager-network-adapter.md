### Device Manager — Disabled Network Adapter

**Scenario**
User reported loss of internet connectivity.

**Investigation**
Reviewed Device Manager and confirmed network adapter disabled. Verified status using PowerShell.

**Root Cause**
Network adapter disabled.

**Resolution**
Re-enabled adapter and confirmed connectivity restored.

**Tools**
Device Manager
Get-NetAdapter

**Skills**
Driver troubleshooting
Hardware diagnostics
