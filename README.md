# angioFFR for Windows

Current build: angioFFR 0.55.4, which fixes the desktop save dialog so JSON studies, PDF reports, and CSV exports are written after saving.

Run the `.exe` installer to install angioFFR for the current user. The installer is a 64-bit Windows build and allows you to choose the installation folder.

Build from the source project with:

```sh
npm run desktop:build:windows
```

The app is unsigned. If Windows SmartScreen warns during installation, choose **More info** and **Run anyway**.
