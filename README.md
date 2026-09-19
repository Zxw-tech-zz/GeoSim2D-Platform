# GeoSim2D Platform

GeoSim2D is a modular two-dimensional computer-aided engineering platform for geometry modeling, mesh generation, simulation setup, solver execution, and result visualization.

## Components

- Mesh Studio: geometry preparation and triangular mesh generation.
- FEM: finite element modeling and solver integration.
- MPM: material point modeling and solver integration.
- UBLA: upper-bound limit analysis modeling and solver integration.

## Windows application

The portable Windows x64 application is packaged as a single executable. It includes the supported Product packages and their bundled Solver executables. No separate Python or Conda installation is required.

The application extracts runtime dependencies to a temporary directory when it starts. A writable temporary directory and sufficient free disk space are required. GPU features require compatible hardware and drivers.

## Evaluation status

This software is provided for evaluation. Validation results, version information, and known limitations are documented in the release notes. Unsigned builds may trigger Windows security warnings. Packaging does not provide a guarantee against reverse engineering.

## Repository scope

This repository contains English application information. Application binaries are maintained as Release assets, not as files in the repository. The implementation source tree, development history, credentials, and user projects are not published here.

Third-party components retain their respective licenses and notices.
