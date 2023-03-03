# Squircle CE

<img src="https://raw.githubusercontent.com/massivemadness/Squircle-CE/develop/.github/images/icon.png" alt="Squircle CE" width="120" height="120" align="left">

<b>Squircle CE</b> is a fast and free multi-language code editor for Android.

This repository contains the complete source code and the build instructions for the project.  
_Note: If you're looking for the code editor library, it has been moved to a separate Git [repository](https://github.com/massivemadness/EditorKit)._

![Android CI](https://github.com/massivemadness/Squircle-CE/workflows/Android%20CI/badge.svg) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Build instructions

### Prerequisites

* At least **546,7MB** of free disk space: **141,2MB** for source codes and around **405,5MB** for
  files generated after building all variants
* **4GB** of RAM
* **macOS** or **Linux**-based operating system. **Windows** platform is supported by
  using [MSYS](https://www.msys2.org/) (e.g., [Git Bash](https://gitforwindows.org/)).

### Building

1. `$ git clone --recursive --depth=1 --shallow-submodules https://github.com/massivemadness/Squircle-CE Squircle-CE`
   — clone **Squircle CE** with submodules
2. In case you forgot the `--recursive` flag, `cd` into `Squircle-CE` directory
   and: `$ git submodule init && git submodule update --init --recursive --depth=1`
3. `$ cd Squircle-CE`
4. Now you can open the project using **[Android Studio](https://developer.android.com/studio/)** or
   build manually from the command line: `./gradlew assembleRelease`.

#### Available flavors

* `googlePlay`: A flavor used for publishing the app
  on [Google Play](https://play.google.com/store/apps/details?id=com.blacksquircle.ui)
* `fdroid`: A flavor used for publishing the app
  on [F-Droid](https://f-droid.org/packages/com.blacksquircle.ui/)

## Screenshots

<img src="https://raw.githubusercontent.com/massivemadness/Squircle-CE/master/.github/images/repository-screenshots.png">

## License

```
Copyright 2023 Squircle CE contributors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
