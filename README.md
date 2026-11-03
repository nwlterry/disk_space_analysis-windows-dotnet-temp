# disk-space-analysis .NET release copy

Current portable build from [nwlterry/disk_space_analysis-windows-dotnet](https://github.com/nwlterry/disk_space_analysis-windows-dotnet/releases/tag/v1.0.0-beta.1). The executable name includes the version.

| Release | Executable |
|---|---|
| v1.0.0-beta.1 | `releases/v1.0.0-beta.1/disk-space-analysis-1.0.0-beta.1.exe` |
| v1.0.0-beta.2 | `releases/v1.0.0-beta.2/disk-space-analysis-1.0.0-beta.2.exe` |

The folder also has the source zip. The executable is a self-contained Windows x64 build. No .NET install.

```powershell
.\disk-space-analysis-1.0.0-beta.2.exe scan --path D:\ --out C:\disk-space-analysis-reports
```
