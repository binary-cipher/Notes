# Notes

## EDR Queries

### SentinelOne Queries
##### Find encoded powershell
```ProcessCmd Contains "powershell" AND ProcessCmd Contains "-enc"```
