# r




# 
```

```
# 
```

```
# 
```
iptables -L FORWARD -n -v
```
# 
```
iptables -t nat -L PREROUTING -n -v
```
# 
```
Get-NetFirewallRule -DisplayGroup "Remote Desktop" | Where-Object Enabled -eq "True" | Get-NetFirewallPortFilter | Select-Object Protocol, LocalPort
```
# 
```
Get-NetFirewallProfile | Select-Object Name, Enabled, DefaultInboundAction
```
# 
```
Test-NetConnection 4.151.152.18 -Port 3389
```
# 
```
Get-NetFirewallRule -DisplayGroup "Remote Desktop" | Enable-NetFirewallRule
```
# 
```
Test-NetConnection 4.151.152.18 -Port 3389
```
# 
```
Get-NetFirewallRule -DisplayGroup "Remote Desktop" | Enable-NetFirewallRule
```
# 
```
Get-NetFirewallRule -DisplayGroup "Remote Desktop" | Select-Object DisplayName, Enabled, Profile
```
