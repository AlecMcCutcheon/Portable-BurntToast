# Portable BurntToast (WIP)

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/5c96b736ff1b45d98666160ab37dcad5)](https://www.codacy.com/manual/Windos/BurntToast?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Windos/BurntToast&amp;utm_campaign=Badge_Grade)
[![codecov](https://codecov.io/gh/Windos/BurntToast/branch/main/graph/badge.svg)](https://codecov.io/gh/Windos/BurntToast)
[![Build Status](https://dev.azure.com/windosnz/BurntToast/_apis/build/status/Windos.BurntToast-Build?branchName=main)](https://dev.azure.com/windosnz/BurntToast/_build/latest?definitionId=2&branchName=main)
[![PowerShell Gallery Version](https://img.shields.io/powershellgallery/v/BurntToast.svg)](https://www.powershellgallery.com/packages/BurntToast)
[![PowerShell Gallery Downloads](https://img.shields.io/powershellgallery/dt/BurntToast.svg)](https://www.powershellgallery.com/packages/BurntToast)
[![Open Issues](https://img.shields.io/github/issues-raw/Windos/BurntToast.svg)](https://github.com/Windos/BurntToast/issues)

![BurntToast Logo Banner](/Media/BurntToast-Wide.png)

A script version of Burnt Toast Notifications that you get temp import into your PS session without installing

## Use the following One-liner to Temp Run in session:

```powershell
iex ((New-Object System.Net.WebClient).DownloadString("https://raw.githubusercontent.com/AlecMcCutcheon/Portable-BurntToast/main/Portable-BurntToast.ps1"))
```

See the [PowerShell Gallery](http://www.powershellgallery.com/packages/BurntToast/) for the complete details and instructions.

## Examples

### [Default Toast](/Examples/Example01/)

```powershell
New-BurntToastNotification
```

![BurntToast Notification Example Default](/Examples/Example01/Example1-Default.png)

### [Customized Toast](/Examples/Example02/)

```powershell
New-BurntToastNotification -AppLogo C:\smile.jpg -Text "Don't forget to smile!",
                                                       'Your script ran successfully, celebrate!'
```

![BurntToast Notification Example Custom](/Examples/Example02/Example2-Custom.png)

### [Alarm Clock](/Examples/Example03/)

```powershell
New-BurntToastNotification -Text 'WAKE UP!' -Sound 'Alarm2' -SnoozeAndDismiss
```

![BurntToast Notification Example Alarm](/Examples/Example03/Example3-Alarm.png)

## Contributors

- [Windos](https://github.com/Windos)
- [jeremytbrun](https://github.com/jeremytbrun)
- [KelvinTegelaar](https://github.com/KelvinTegelaar)
- [steviecoaster](https://github.com/steviecoaster)
- [glennsarti](https://github.com/glennsarti)
- [UniverseCitiz3n](https://github.com/UniverseCitiz3n)
- [cedarbaum](https://github.com/cedarbaum)

## License

- See [LICENSE](LICENSE) file

## Image Credit

The [default image](/Media/BurntToast.png) for BurntToast Notifications is a photo taken by [Craig Sunter](https://www.flickr.com/photos/16210667@N02/17230428864)
