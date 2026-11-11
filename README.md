# Jazyk Scoop bucket

Install on Windows x64:

```powershell
scoop bucket add jazyk https://github.com/JazykOrg/scoop-bucket
scoop install jazyk/jazyk
```

Upgrade with `scoop update jazyk`.

The manifest installs the native GitHub Release, including PDFium and third-party
notices. Node.js and Rust are not required. Local task commands require `sh` on
PATH, such as Git for Windows.

Source and documentation: https://github.com/JazykOrg/Jazyk.
