# Get-RustDir

A utility to find the install path for the game [Rust](https://rust.facepunch.com/).

## Example Usage

```PowerShell
Import-Module "RustDir.psm1"

[System.IO.DirectoryInfo] $RustDir = (Get-RustDir)
```
