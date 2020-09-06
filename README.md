# TA-Lib

This is the same copy of [TA-Lib source code](https://ta-lib.org/) but with some modifications to CMake rules to enable `-O3` during C compilation.

## Build

1. Install cmake

```
sudo apt install cmake
```

2. Clone and make

```
git clone https://github.com/nextwavecapital/ta-lib.git
cd ta-lib/ta-lib
mkdir build && cd build
cmake ..
make
sudo make install
```

TA Lib will be installed to `/usr/local/lib`.

## Python Bindings

```
pip install wheel
pip install TA-Lib
```
