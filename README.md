# PowerShell Script for Microsoft Teams Client Deployment

Install-MicrosoftTeams.ps1 is a PowerShell script for automating the deployment of the Microsoft Teams desktop client for Windows.

### Instructions

1. Download the Teams client installer from [Microsoft](https://teams.microsoft.com/downloads).
2. Run the script and specify the **-SourcePath** for the installer.

#### Example:

```
.\Install-MicrosoftTeams.ps1 -Source \\mgmt\Installs\MicrosoftTeams
```

Using the example command above, the script will look in \\mgmt\installs\MicrosoftTeams for the Teams_Windows_x64.exe file, and launch a silent installation of the Teams client.

### Credits

Written by: 

- Paul Cunningham, [Blog](http://practical365.com) | [GitHub](https://github.com/cunninghamp) | [Twitter](https://twitter.com/paulcunningham) 

For more Office 365 tips, tutorials, and news check out [Practical 365](http://practical365.com).
