# Muta downloads

Muta (Igbo for “learn”) is a personal tutor for maths and science that runs fully offline on an
ordinary laptop. Type, speak or snap a photo of your question, and Muta shows you the steps.

This is the Muta team's official download page. Website: https://trymuta.vercel.app

## Download

Open the [latest release](https://github.com/iitimii/muta-releases/releases/latest) and choose
the file for your laptop:

| Your laptop | File |
|---|---|
| Mac with Apple silicon (M1 or newer) | `Muta_<version>_darwin-aarch64_offline.tar.gz` |
| Mac with an Intel processor | `Muta_<version>_darwin-x86_64_offline.tar.gz` |
| Windows, 64-bit | `Muta_<version>_windows-x86_64_offline.zip` |
| Linux, 64-bit (x86-64) | `Muta_<version>_linux-x86_64_offline.tar.gz` |

Each file is 1.3 to 1.5 GB and holds everything Muta needs, its AI model included. You download
it once; after that, Muta works without internet.

Not sure which Mac you have? Open the Apple menu and choose **About This Mac**. “Chip: Apple M1”
(or M2, M3 and so on) means Apple silicon; “Processor: … Intel” means Intel.

## Install

1. Extract the whole archive.
2. Open `HOW TO INSTALL.txt` inside it and follow the steps.

These are early builds and they are not signed yet, so macOS and Windows will warn you the first
time you open Muta.

## Check your download (optional)

Each file has a matching `.sha256` file in the same release. To confirm a download is complete
and unchanged, put both files in one folder and run:

- macOS or Linux: `shasum -a 256 -c <file>.sha256`
- Windows (PowerShell): `Get-FileHash .\<file>.zip -Algorithm SHA256`, then compare the result
  with the text in the `.sha256` file.

## About this repository

It holds release files only. Muta's source code is not published here.
