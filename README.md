# Sebek-sTerminal

`Windows Terminal command prompt setup using nerd fonts & additional pluguing like oh-my-posh and others`

##1. Install Hack font
##2. Install [PowerShell](https://www.microsoft.com/store/productId/9MZ1SNWT0N5D) from the Windows Store
##3. Run `iwr -useb get.scoop.sh | iex`
##4. Run `winget install -e --id Git.Git` to install [Git for Windows](https://git-scm.com/downloads)
##5. Run `scoop install neovim`
##6. Run `Install-Module posh-git -Scope CurrentUser -Force`
##7. Run `Install-Module oh-my-posh -Scope CurrentUser -Force`
##8. Run `mkdir .config/powershell`
##9. Run `cp .\user_profile.ps1 .\.config\powershell\user_profile.ps1`
##10. Run `cp .\settings.json ~\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\` and paste `$env:USERPROFILE\.config\powershell\user_profile.ps1`
##11. Make sure path User\Documents\PowerShell\ exist (if not create one)
##12. Run `nvim $PROFILE.CurrentUserCurrentHost` and paste `. $env:USERPROFILE\.config\powershell\user_profile.ps1`use`:wqa` to save changes
##13. Run `Install-Module -Name Terminal-Icons -Repository PSGallery -Force`
##14. Run `Import-Module Terminal-Icons`
##15. Run `Install-Module -Name z -Force`
##16. Run `Install-Module -Name PSReadLine -AllowPrerelease -Scope CurrentUser -Force -SkipPublisherCheck`
##17. Run `Set-PSReadlineoption -PredictionSource History`
##18. Run `Set-PSReadlineoption -PredictionView ListView`
