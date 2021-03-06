# New Repository

https://github.com/TCROC/Ignorance-Submodule

## Reasons

1. Unity had a TOS update for use of UPM and I'm not exactly sure what that means for open source projects.  Submodules feel safer.  More can be read here. [here](https://forum.unity.com/threads/updates-to-our-terms-of-service-and-new-package-guidelines.999940/).

2. I could not get UPM get to work properly in Unity 2020 LTS.  The git submodules work perfectly tho!

I'll be archiving this repository, but feel free to use the other one! :)

# Ignorance-UPM

This repo runs nightly and formats Ignorance releases for UPM.  The Ignorance repo can be found here: https://github.com/SoftwareGuy/Ignorance.

# Dependencies

- Mirror

    - Reccomended to install via the [git upm repo](https://github.com/TCROC/Mirror-UPM.git).

    - Should also be compatible with the [Asset Store](https://assetstore.unity.com/packages/tools/network/mirror-129321) and [Main Repo Releases](https://github.com/vis2k/Mirror/releases) but it has not been tested. If anyone tests these out to verify, open up an issue and I'll update this README.

# How To Use

- [UPM Git Extension](https://github.com/mob-sakai/UpmGitExtension) (Recommended)
- [UPM Git Dependency](https://docs.unity3d.com/Manual/upm-git.html)
  - To pull the latest upm release:
    ```
    https://github.com/TCROC/Ignorance-UPM.git#releases/upm
    ```
  - To pull a tagged version:
    ```
    https://github.com/TCROC/Ignorance-UPM.git#[insert tag here]
    ```
    - Example:
      ```
      https://github.com/TCROC/Ignorance-UPM.git#1.3.8
      ```
# Version Differences

The tags at the main repo here: https://github.com/SoftwareGuy/Ignorance are not always compatible with UPM.  For example, the version v1.3.9.2 is not compatible with UPM and is converted to 1.3.9-2.  They are equivalent to each other.

# Reporting Issues

If you find any issues please open up an issue so it can be fixed :)

# Contributing

If you want to contribute, just fork this repo and create a PR to the dev branch when you are happy with your changes.
