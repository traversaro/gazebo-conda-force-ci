# gazebo-conda-forge-ci

Continuous Integration based on conda-forge for Gazebo simulator.

This repo contains two main CI jobs:
* [.github/workflows/conda-forge-check-released-binary.yml](.github/workflows/conda-forge-check-released-binary.yml) : checks that the conda-forge provided gazebo binaries run fine with an empty world.
* [.github/workflows/conda-forge-ci-build-and-tests.yml](.github/workflows/conda-forge-ci-build-and-tests.yml) : checks that tip of the gazebo11 branch from the official Gazebo repo compiles fine against the latest conda-forge dependencies, and the test suite works fine.
