
---
# Date this page was created.
date: 2022-06-02T00:00:00

# Project title.
title: "YACHT"

# Project summary to display on homepage.
summary: "Yet Another C++ Helper Template, a template for starting C/C++ projects"

# Tags: can be used for filtering projects.
# Example: `tags: ["machine-learning", "deep-learning"]`
tags:
- C-Cpp
- Docker
- unix
- windows

# Optional external URL for project (replaces project detail page).
#external_link: "https://github.com/hill-a/stable-baselines"

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder.
image:
  caption:
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point: Smart

---

# YACHT

[YACHT](https://github.com/ShadowMitia/YACHT)([https://github.com/ShadowMitia/YACHT](https://github.com/ShadowMitia/YACHT)) is a C/C++ project template based on CMake designed by [ShadowMitia](https://shadowmitia.eu/) and I. Its goal is to avoid boilerplate CMake code, when trying to add extra features to your project. It uses a "pay for what you use" style of implementation, meaning it has a very small file size and does not generate file for features you didn't ask for.

It has support for:
* Easy compiler flags & feature configuration
* Linters and formatting tools: `clang-tidy`, `cppcheck`, `include-what-you-use`, & `clang-format`
* Integrated testing libraries: `GTest` & `Catch2`
* Package managers: `conan` & `vcpkg`
* Crossplatform support: Unix `Make`, `Ninja`, & Windows `Visual Studio` 2015 and up
* Dev perks: `Docker`, a fully featured `./build.sh` script, a predefined `.gitignore`, & a pre setup folder structure.

Being based on CMake, it also allows you to continue to use your custom `*.cmake` scripts and to alter any parts of the `CMakeLists.txt` with little  interference.
