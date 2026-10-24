# Nocturne Sleep Music — One-Click Android APK Builder

This folder is pre-configured to automatically compile and sign a modern **Android APK (Signature Scheme v2/v3)** using GitHub Actions so it installs cleanly on Android 14, 15, and 16 without any "App not installed" errors.

## How to Get Your Signed APK in 3 Steps:
1. Create a new repository on [GitHub.com](https://github.com/new).
2. Click **"uploading an existing file"** on your new GitHub repository page, and drag-and-drop all files/folders extracted from this ZIP (`www/`, `.github/`, `config.xml`, and `README.md`), then click **Commit changes**.
   *(Important: Make sure the `.github/workflows/build-apk.yml` folder structure is included!)*
3. Click the **Actions** tab at the top of your GitHub repository, wait ~90 seconds for the **"Build Signed Android APK"** workflow to turn green, click on the run, and download **`Nocturne-Sleep-Music-Signed-APK`** under the **Artifacts** section at the bottom of the page.
