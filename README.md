# SQLRunAsAddendum 7.0.20.1
SCOM - SQL Server RunAs Addendum - Management Pack

https://kevinholman.com/2016/08/25/sql-mp-run-as-accounts-no-longer-required/

* Version 7.0.20.1
Changed frequency of Healthservice SID is Enabled Monitor from 60 seconds to 43200 seconds.
Added On-Demand recalculate capability to Healthservice SID is Enabled Monitor
* Version 7.0.20.0
Added SQL TcpPorts to configuration scripts to enable connecting to secured SQL environments
* Version 7.0.15.2
Updated SQL 2012+ script to remove ALTER ANY DATABASE right, and add SELECT on sql db mirroring tables to fix discovery error when using older MP's
* Version 7.0.15.1
Fixed MP dependencies to support SCOM 2012R2
* Version 7.0.15.0
Added support for the SQL Version Agnostic MP for SQL 2012 and later.
Dropped support for SQL 2008 (can still use the older RunAs addendump MP's for that version
* Version 7.0.0.0
Added support for SQL 2017+ and simplified monitor and task names.
* Version 6.7.31.0
Disabled Monitor for SysAdmin role check by default
Updated SQL Low Priv configuration tasks to be more reliable
* Version 6.7.7.2
Updated addendum views to fall under regular SQL presentation views
* Version 6.7.7.1
Bug fixes for LOW PRIV script task to support offline DB's, read only, always ON, etc.
* Version 6.7.2.0
Added support for SQL 2016
Added additional monitors to check for ability to connect to SQL and sysadmin role check
Removed any alerting by default.
Added new task to configure Healthservice login for LOW PRIV to SQL
Added folders, and state views to ease configuration and running tasks
* Version 6.6.4.0 – Original release of the addendum MP’s
