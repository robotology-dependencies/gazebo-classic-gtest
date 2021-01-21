# gazebo-classic-gtest

[Gazebo Classic](https://github.com/osrf/gazebo) provides the `gazebo::ServerFixture` class in the `gazebo/test/ServerFixture.hh` header, to simplify developing tests on top of its libraries.

Unfortunatly, to use it you **must** use exactly the same version of googletest that Gazebo vendors in its [`gazebo/test/gtest`](https://github.com/osrf/gazebo/tree/gazebo11/test/gtest) directory. This repo contains exactly a copy of that directory, in a standalone git repo to simplify its inclusion in other repos via [CMake's FetchContent module](https://cmake.org/cmake/help/latest/module/FetchContent.html).
