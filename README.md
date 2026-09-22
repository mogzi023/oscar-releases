# OSCAR — releases

Download links and the update manifest for OSCAR, a thеаtre recording tool
built by Blue-i.

**The source lives elsewhere and is private.** This repository holds only the
signed, notarised disk images and `latest.json`, which is what OSCAR's
Settings → About → Check for updates reads.

- Latest build: see [Releases](../../releases)
- `latest.json` — version, download URL and SHA-256 of the current build

Builds are signed with a Blue-i Developer ID and notarised by Apple. OSCAR
refuses to install an update that is not signed by the same developer as the
running copy, so a disk image from anywhere else will be rejected.
