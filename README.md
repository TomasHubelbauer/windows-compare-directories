# Windows Compare Directories

```powershell
Compare-Object `
  -ReferenceObject $(Get-ChildItem -Recurse -Force -Path a) `
  -DifferenceObject $(Get-ChildItem -Recurse -Force -Path b) `
```

`-Force` is used to include hidden files and directories.
