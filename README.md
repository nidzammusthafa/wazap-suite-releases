# WazapSuite Public Releases

This directory is intended to be a git submodule or a separate git repository linked to:
**[nidzammusthafa/wazap-suite-releases](https://github.com/nidzammusthafa/wazap-suite-releases)**

## Purpose

This repository serves as a **"Public Release Channel"** for the WazapSuite Desktop application.

- **Private Source Code:** The source code for the application is kept private in the main repository.
- **Public Installers:** The compiled `.exe` installers and update metadata (`latest.yml`) are pushed here.

## How it Works

The Auto-Updater in the React/Electron app is configured to check this specific repository for new releases, ensuring that users can receive updates without exposing the proprietary source code.

## Usage

1. Build the desktop app: `npm run make`
2. Copy the artifacts from `desktop/out/make` to this folder.
3. Commit and push/publish the release to GitHub Releases in this repository.
