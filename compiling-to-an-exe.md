---
description: This page describes compiling the game to an `.exe` file.
---

# Compiling to an EXE

## Installing requirements

If not installed yet, install **PyInstaller:**

```text
$ pip install PyInstaller
```

Run PyInstaller to compile an EXE:

```text
$ pyinstaller main.py
```

The `.exe` file should now be present in the `/dist` directory.

