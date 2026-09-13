# GeoSim2D Platform

Private, release-only distribution of GeoSim2D Platform for Windows x64.

## Download and run

Open [Releases](https://github.com/Zxw-tech-zz/GeoSim2D-Platform/releases), select a version, and download `GeoSim2D.exe`.
Run the executable directly. No separate Python, Conda, Product package, or bundled Solver installation is required.
Access requires a GitHub account with permission to this private repository.

## Included components

- Mesh Studio
- FEM
- MPM
- UBLA
- The Solver executables identified in each release's notes

## Requirements and limitations

- Windows x64 and a writable temporary directory with sufficient free disk space.
- A onefile build extracts its dependencies at startup. The first launch may take time.
- GPU operations require compatible hardware and drivers; this download does not install drivers.
- These are unsigned private evaluation builds unless the release notes explicitly state otherwise.
- Check each release's validation results and known limitations before using it.

## Code protection

The current private build uses ordinary PyInstaller Onefile, without PyArmor protection.
Python code inside the executable may be extracted or reverse engineered. Repository privacy is access control, not binary encryption.
Third-party libraries and supplied Solver executables are packaged without changes to their internal implementations.

## Repository contents

This repository contains English distribution information only. Application executables are Release assets, not Git-tracked files.
The implementation source tree, its Git history, build directories, credentials, and user projects are not uploaded here.
GitHub's automatically generated repository archives contain these documentation files, not the application source repository.

Third-party components retain their respective licenses and notices. Private access and onefile packaging do not override those terms.
