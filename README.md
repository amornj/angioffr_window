# angioFFR for Windows

Current build: **angioFFR 0.58.1**. Built from source commit [3e6a0f7](https://github.com/amornj/angioFFR/commit/3e6a0f7).

Downloads:

- [angioFFR-0.58.1-windows-x64.exe](angioFFR-0.58.1-windows-x64.exe)

Checksums: [SHA256SUMS](SHA256SUMS).

This update includes:

- Up to four angiographic images, with dedicated branch tracing and a selected best measurement view for each branch.
- Nested branch origins, visible-tree length and volume summaries, and crown-based Mode 5 flow allocation.
- PDF vessel models colored by calculated angioFFR, with the matching legend, regardless of the workspace color selection.
- Existing desktop Google sign-in, cloud backup/recovery, and save/export support.

Mode 5 is an independent research implementation; it does not inherit CathWorks FFRangio validation.

Run the `.exe` installer to install angioFFR for the current user. The installer is a 64-bit Windows build and allows you to choose the installation folder.

Build from the source project with:

```sh
npm run desktop:build:windows
```

The app is unsigned. If Windows SmartScreen warns during installation, choose **More info** and **Run anyway**.

The installer is cross-built on macOS. A live Windows installation test requires a Windows machine.
