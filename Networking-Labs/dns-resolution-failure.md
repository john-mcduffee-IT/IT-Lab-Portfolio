### DNS Resolution Failure

**Scenario**
User could reach external IP addresses but websites would not load.

**Investigation**
Tested connectivity to IP vs domain. Used nslookup and reviewed DNS configuration.

**Root Cause**
Incorrect DNS configuration.

**Resolution**
Reset DNS settings to automatic and flushed DNS cache.

**Tools**
ping
nslookup
ipconfig /flushdns

**Skills**
DNS troubleshooting
Networking fundamentals
