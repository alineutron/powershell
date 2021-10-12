## Powershell extension to switch between kubernetes clusters

Recently i had this problem where i want to switch between cluster in kubernetes cli. Its quite easy to do it but i was doing it so often that i needed an extension to do it. So here is an extension that you could use in your powershell which will help you switch contexts in kubernetes cli.

###  Step1:
you need to open the powershell profile which is located here 
Documents\PowerShell\Microsoft.PowerShell_profile.ps1

### Step2: 
in the end of the file paste the code from 'Powershellext' file

### step3:
Open windows terminal and type

```
kubectlx (Hit tab)
```

You will see your available contexts and if you hit enter after selecting your available context you will be switched to that.
