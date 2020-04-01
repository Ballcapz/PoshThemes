# My Excellent Theme

This is a theme for oh-my-posh on powershell.

### Prerequisites
1. Posh-git
2. Oh-my-posh


## Install
1. Find your Theme settings folder location by running
```ps1
$ThemeSettings.MyThemesLocation
# default -> ~\Documents\WindowsPowerShell\PoshThemes
```
2. Clone the repo such that the `my-excellent-theme.psm1` file is inside the directory you found in step 1<br/>
The directory structure should look like this:
```ps1
~\Documents\WindowsPowerShell\PoshThemes\my-excellent-theme.psm1
```

3. At the powershell prompt run
```ps1
Set-Theme my-excellent-theme
```

This will set up your terminal to look like this

![My excellent theme prompt](my-excellent-theme.JPG)