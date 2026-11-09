# Security policy

## Reporting a vulnerability

Please **don't** open a public issue for security problems. Use GitHub's
private reporting instead: **Security → Report a vulnerability** on this
repository.

Include the FORGEPOINT version, your Windows version and steps to reproduce.

## Verifying downloads

Only download FORGEPOINT from the official website
(<https://maggotzyt.github.io/forgepoint/>) or this repository's
[`downloads`](downloads) folder. Every release includes `SHA256SUMS.txt`; check your file
with:

```powershell
Get-FileHash .\FORGEPOINT-Setup-x64.exe -Algorithm SHA256
```

## Supported versions

Only the latest release receives fixes.
