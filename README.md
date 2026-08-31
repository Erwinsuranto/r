# r

# 
```



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
