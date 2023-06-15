# gha_cmake_gcc_cpp17_conan_boost_gprof

Branch   |[![GitHub Actions logo](pics/GitHubActions.png)](https://github.com/richelbilderbeek/gha_cmake_gcc_cpp17_conan_boost_gprof/actions)
---------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
`master` |[![Check build](https://github.com/richelbilderbeek/gha_cmake_gcc_cpp17_conan_boost_gprof/actions/workflows/check_build.yml/badge.svg?branch=master)](https://github.com/richelbilderbeek/gha_cmake_gcc_cpp17_conan_boost_gprof/actions/workflows/check_build.yml)
`develop`|[![Check build](https://github.com/richelbilderbeek/gha_cmake_gcc_cpp17_conan_boost_gprof/actions/workflows/check_build.yml/badge.svg?branch=develop)](https://github.com/richelbilderbeek/gha_cmake_gcc_cpp17_conan_boost_gprof/actions/workflows/check_build.yml)

The goal of this project is to have a clean GitHub Actions build, with specs:

 * Build system: `CMake`
 * C++ compiler: `g++`
 * C++ version: `C++17`
 * Package manager: `conan`
 * Libraries: `STL` and Boost
 * Code coverage: none
 * Profiling: `gprof`
 * Source: one single file, `main.cpp`

More complex builds:
 * [none]

Equally complex builds:
 * [none]

Less complex builds:

 * No Boost, no `gprof`: [gha_cmake_gcc_cpp17_conan](https://github.com/richelbilderbeek/gha_cmake_gcc_cpp17_conan)
 * No Boost, no `conan`: [gha_cmake_gcc_cpp17_gprof](https://github.com/richelbilderbeek/gha_cmake_gcc_cpp17_gprof)
 