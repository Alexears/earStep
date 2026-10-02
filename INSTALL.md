# earStep installation

## macOS

The macOS release includes VST3, AU and Standalone builds.

Because the current public build is unsigned and not notarized, macOS may block it the first time you open or install it.

If macOS shows a security warning:

1. Try to open or install earStep once.
2. Open **System Settings → Privacy & Security**.
3. Find the message about earStep.
4. Click **Open Anyway** and confirm.

Do not disable Gatekeeper globally.

Typical plug-in locations:

- VST3: `~/Library/Audio/Plug-Ins/VST3/`
- AU: `~/Library/Audio/Plug-Ins/Components/`

After installation, restart your DAW or rescan plug-ins.

## Windows

The Windows release includes VST3 and Standalone builds.

Windows SmartScreen may warn because the installer is currently unsigned. Check that the file was downloaded from the official **Alexears/earStep** GitHub Releases page before continuing.

Typical VST3 location:

- `C:\\Program Files\\Common Files\\VST3\\`

Restart your DAW or rescan plug-ins after installation.

## Linux

The Linux release is available as a `.deb` package and a `.tar.gz` archive.

The package contains VST3 and Standalone builds. Installation paths can vary depending on distribution and desktop environment.

## Support

If you run into an installation problem, contact **Alex Ears** on Telegram: [@Alexears](https://t.me/Alexears).
