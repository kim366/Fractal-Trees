# Fractal Trees in the Wind

![Animation of result](demo.gif)

Randomly generated fractal trees visualized with SFML in C++. Watch out: `Tree` move constructor is _O(n)_.

## Dependencies
* [SFML](https://sfml-dev.org)
* [My SelbaWard fork](https://github.com/kim366/SelbaWard) (necessary files included in project)

## Building
This project can be built with [CMake](https://cmake.org)

```
mkdir build
cd build
cmake ..
./main
```