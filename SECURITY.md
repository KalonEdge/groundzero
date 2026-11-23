# Security policy

## Supported versions

Security fixes go into the latest release. GroundZero updates itself, or choose
**GroundZero › Check for Updates…** to update now.

## Reporting a vulnerability

Please report security issues privately, through
[GitHub's private vulnerability reporting](https://github.com/KalonEdge/groundzero/security/advisories/new),
not in a public issue.

Include what you found, the version of GroundZero and macOS, and the steps to reproduce it. We will
acknowledge your report, keep you informed while we work on a fix, and credit you in the release
notes if you would like.

## How GroundZero protects you

- **Offline by design.** Reading, search and answers run on your Mac. GroundZero goes online only to
  check for updates, to load the Kiwix archive catalog when you browse it, and for downloads you
  start. It sends no questions, reading history or identifiers.
- **Verified updates.** An update is installed only if its size and SHA-256 match the release
  manifest, and the app inside is signed with our Developer ID and notarized by Apple. Anything else
  is refused.
- **Verified Kalon install.** When GroundZero installs Kalon for you, it checks the download's
  checksum and Kalon's Developer ID signature before opening it.
- **Signed and notarized releases.** Every release is signed with the KalonEdge Developer ID under
  the hardened runtime and notarized by Apple.
