# brSmoothWeights & brTransferWeights
Tools for smoothing and transferring skin weights between influences in Autodesk Maya.

## Video
[brSmoothWeights on Vimeo](https://vimeo.com/304704799)

## Installation
Installation is easy with the included installer.

[Easy Install](https://github.com/IngoClemens/brSmoothWeights/wiki/Installation)

## Getting Started
Visit the [Quick Guide](https://github.com/IngoClemens/brSmoothWeights/wiki/Quick-Guide) for basic tool usage.

See the [Wiki](https://github.com/IngoClemens/brSmoothWeights/wiki) for full details.

# Linux Compile Instructions For Maya 2020

export CC="/sw/pkg/gcc/6.3.1/bin/gcc"

export DEVKIT_LOCATION="/sw/pkg/maya/2020/maya2020/devkit"

cmake -H. -Bbuild -G "Unix Makefiles"

cmake --build build/
