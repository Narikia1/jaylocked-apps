# JayLocked downloads

JayLocked keeps photos, videos, documents and logins behind their own passcode, on iPhone, iPad, Mac, Android and
Windows. It is part of the JayApps family by Narikia.

**Get it at [jaylocked.narikia.com](https://jaylocked.narikia.com).** The website always links to the latest release
here.

`SHA256SUMS.txt` in each release lets you check a download is the file we published:
`shasum -a 256 -c SHA256SUMS.txt` on Mac, or `Get-FileHash JayLocked-Setup.exe` on Windows.

The Windows installer also carries a signed record of where it was built. With GitHub's command-line tool,
`gh attestation verify JayLocked-Setup.exe -R Narikia1/jaylocked-apps` confirms the file came out of this
repository's Windows workflow and was not changed afterwards.

## What is in this repository

Only the release workflow and the published files. The Windows workflow builds and tests JayLocked on a real
Windows machine and keeps the installer, its SHA-256 and its test evidence as artifacts of the run for 14 days.
