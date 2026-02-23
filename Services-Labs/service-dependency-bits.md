### Service Dependency Failure — BITS

**Scenario**
Windows Update service failed to start.

**Investigation**
Reviewed service dependencies and identified BITS service stopped.

**Root Cause**
Dependency service stopped.

**Resolution**
Started BITS service and then restarted Windows Update.

**Tools**
Services console

**Skills**
Dependency troubleshooting
Root cause analysis
