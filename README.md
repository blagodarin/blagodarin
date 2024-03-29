# Sergei's Entertainment Projects

These are the projects that I work on — occasionally, in my spare time, without a plan, just for fun.
Severely unfinished, they may still have some value to the outer world, so here they are.

[Blocks](https://github.com/blagodarin/blocks) is a simple 2D game. You can download the latest Windows build
from the project page. And yes, the entire game with music, graphics and additional data is just a single 1.5 MiB
binary without any extra dependencies (not demoscene-size, but I didn't really tried).
Or, if you're not into downloading and running random binaries from the Internet, you can build the game from source.
With recent Visual Studio and CMake it's literally one click away — the build system will take care of everything
from downloading dependencies to packing data into the final binary.

[Yttrium](https://github.com/blagodarin/yttrium) is a toolkit that powers Blocks.
It's meant to be **the** toolkit for building games, providing every piece of code a game might need.
It's also really easy to use — just some three CMake lines will get you Yttrium with all its dependencies, no manual work required.

[Aulos](https://github.com/blagodarin/aulos) is a realtime audio synthesis toolkit.
It can be used as middleware as well as a standalone tool.

[Seir](https://github.com/blagodarin/seir) is the foundation all other projects are built upon.
It provides a set of C++ libraries as well as a simple CMake-based package management solution,
and is meant to replace Yttrium as an all-in-one toolkit.
