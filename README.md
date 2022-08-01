# sysmon

See https://docs.microsoft.com/en-us/sysinternals/downloads/sysmon

Example Configs

* https://github.com/SwiftOnSecurity/sysmon-config/
* https://github.com/olafhartong/sysmon-modular

## Install / Command Line

Install sysmon and add a config file
```
sysmon64 -i [<configfile>]
```

Update Configuration
```
sysmon64 -c [<configfile>]
```

Dump Existing Config
```
sysmon64 -c
```