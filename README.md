# MAUI Template iOS Installer

GitHub Pages installer repository for the OneLane .NET MAUI template. `./.ol/ol.cmd template publish maui` in the parent repo builds the signed IPA, updates `ipa/maui-install.ipa`, regenerates `manifest.plist` and `release.json`, pushes this repo, and verifies the exact public release.

The OTA install is valid only for UDIDs included in the package's Ad Hoc provisioning profile.
