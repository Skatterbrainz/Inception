# My GitHub Updates

Randomized Random Randomness Randomly Randomized

# 2026-11-22

- [GistMover 1.0.0](https://github.com/Skatterbrainz/GistMover/)
  - Updated launcher shell script
  - Created AppImage release 1.0
- [OSQuery 2.2.0](https://github.com/Skatterbrainz/OSquery/)
  - Added -Verbose to show queries across all functions
  - Added Get-OsQueryUptime
  - Updated Get-OsQueryInstalledPackages to query all package tables as single response
  - Added Get-OsQueryPackageSources to return all apt and yum sources
  - Added Get-OsQuerySystemDUnits
  - Added Get-OsQueryChromeExtensions
  - Added Get-OsQueryFirefoxAddOns
  - Added Get-OsQueryMounts
  - Added Get-OsQueryUSBDevices
- [Helium 1.8.0](https://github.com/Skatterbrainz/Helium/)
  - Updated: Publish-GalleryUpdate to read from environment variables or secrets: PSGALLERY, PSGALLERY_API or PSAPIKEY

# 2026-11-20

- [LinuxTools PowerShell module 1.5.0](https://github.com/Skatterbrainz/LinuxTools/)
  - updated to 1.5.0 with added features to support KDE, RHEL, Fedora, Rocky.
  - Added Get-UpdateHistory to query apt, dnf, yum, flatpak, snap
  - See the README for more
- [Helium PowerShell module 1.8.0](https://github.com/Skatterbrainz/Helium/)
  - Added -SecretName parameter to Publish-GalleryUpdate to leverage secret management for API key
  - Renamed Set-TLS12 to Set-TLS and added parameter support for 1.2 and 1.3 (1.2 is the default)
