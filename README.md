# scoop-frc

[![Tests](https://github.com/hadley31/scoop-frc/actions/workflows/ci.yml/badge.svg)](https://github.com/hadley31/scoop-frc/actions/workflows/ci.yml) [![Excavator](https://github.com/hadley31/scoop-frc/actions/workflows/excavator.yml/badge.svg)](https://github.com/hadley31/scoop-frc/actions/workflows/excavator.yml)

A [scoop](https://scoop.sh) bucket for open source FRC software.

> **Please note these manifests are _not_ maintained by the original app developers.** If you experience any issues installing software from this scoop bucket, **please create [an issue](https://github.com/hadley31/scoop-frc/issues/new/choose) in this repo!**

How do I install these manifests?
---------------------------------
1. Open Powershell
1. Install Scoop (if it is not already installed)
    ```sh
    Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
    irm get.scoop.sh | iex
    ```
1. Add this bucket to scoop
    ```sh
    scoop bucket add frc https://github.com/hadley31/scoop-frc
    ```
1. Install an FRC application
    ```sh
    scoop install pathplanner
    ```
1. Run the application
    ```sh
    pathplanner
    ```

How do I contribute new manifests?
----------------------------------

To make a new manifest contribution, please read the [Contributing Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md).

----
