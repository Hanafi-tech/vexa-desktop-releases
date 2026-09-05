# VexaCode Installation Guide

VexaCode is distributed free of charge. The current installers are unsigned, so macOS and Windows may show a security warning on the first launch.

## Download

Download the installer for your platform from the **latest** release assets. On macOS, choose `arm64` for Apple Silicon Macs and `x64` for Intel Macs. Download `SHA256SUMS.txt` from the same release before installing.

## macOS

1. Open the `.dmg` file.
2. Drag **VexaCode** into the **Applications** folder.
3. Open **Applications → VexaCode**.
4. If macOS says it cannot verify the developer, close the dialog, then open **System Settings → Privacy & Security**.
5. Click **Open Anyway** for VexaCode and confirm **Open**.

Only use **Open Anyway** when the installer came from the trusted VexaCode release repository and its checksum matches `SHA256SUMS.txt`.

## Windows

1. Run the `.exe` installer.
2. If Microsoft Defender SmartScreen appears, select **More info**.
3. Select **Run anyway** only when the installer came from the trusted VexaCode release repository and its checksum matches `SHA256SUMS.txt`.
4. Follow the installer steps and launch VexaCode from the Start menu or desktop shortcut.

## Verify the checksum

On macOS or Linux:

```bash
shasum -a 256 VexaCode-installer.dmg
```

On Windows PowerShell:

```powershell
Get-FileHash .\VexaCode-installer.exe -Algorithm SHA256
```

Compare the result with the matching entry in `SHA256SUMS.txt`.

## Important

Unsigned builds are suitable for development and internal testing. A future signed release will reduce or remove these first-launch warnings.
