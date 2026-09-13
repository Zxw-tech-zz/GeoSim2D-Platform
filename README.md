# GeoSim2D Platform

Portable 2D CAE platform for Windows x64.

## Download

### [Download GeoSim2D.exe](https://github.com/Zxw-tech-zz/GeoSim2D-Platform/releases/download/v2026.09.13-private.1/GeoSim2D.exe)

**2026.09.13 Private Preview · Windows x64 · 997 MiB**

Sign in with a GitHub account authorized to access this private repository, download the single executable, and run it directly. No separate Python, Conda, Product package, or bundled Solver installation is required.

## Included

- Mesh Studio
- FEM with GeoSimFEM
- MPM with TaichiMpmSolver
- UBLA with GeoSim_PDIP_UBLA

## Before running

- Allow ample free disk space: startup extracts approximately 1.69 GiB, with additional temporary files used by the bundled Solvers.
- The first launch may take time. The executable is unsigned, so Windows security software may display a warning.
- GPU operations require compatible hardware and drivers.
- This is a private evaluation build. Clean-Windows VM qualification and full interactive GUI testing have not been completed.
- The UBLA rigid rectangle verification currently reports non-convergence. The elastoplastic rectangle verification passed.
- Ordinary PyInstaller packaging does not prevent extraction or reverse engineering. Private access restricts downloads; it does not encrypt the executable.

## File verification

SHA-256 for the executable:

```text
f57a2bc59ad83f15d9d75d5f2ed27ce5257d7c005522bcf5ae809ecb789aecfe
```

This repository is for application downloads and English usage information only. The application implementation and its development history are not hosted here.

Third-party components retain their respective licenses and notices.