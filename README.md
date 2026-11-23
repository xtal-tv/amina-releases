# Amina for Mac: releases

This repository holds only the finished Amina app for testers, as GitHub releases. There is no code here.
(The code lives in a private repository.)

**Testers:** use the download link in your invite email. After you install Amina once, she updates herself from
here: when a new version is ready she asks to restart, and keeps everything.

**Each release has:**
- `Amina-<version>-arm64.dmg`: the installer (Apple Silicon Macs, macOS 13 or newer). Open it and drag Amina to
  Applications.
- `Amina-<version>-arm64-mac.zip` and `latest-mac.yml`: what the app's updater reads. Leave them in place.

Every build is signed by Understory Interactive LLC and notarized by Apple.

**Questions or problems:** hello@heyamina.com, or "Send feedback" in Amina's menu.

---

*For Mike:* releases are posted by `npm run tester -- --publish` in `desk-device/mac-app` of the app's repository
(see `TESTER-BUILD.md` there). Don't edit or delete a release's files by hand: testers' apps read them.
