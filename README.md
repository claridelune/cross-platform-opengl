# cross-platform-opengl

## Linux

- Install C/C++ compiler

```
sudo apt install build-essential

sudo pacman -Sy base-devel
```

- Install the GLFW3, FreeType, zlib and cmake

- cd to ./hello_square

```
make -f Makefile.linux64
```

## MacOS

- You have to have brew install

- Install Clang or GNU compiler

clang

```
brew install llvm
brew install gcc cmake
```

Para ver la version

```
clang --version
```

- Install libraries

```
brew install glfw
brew install ftgl
brew install zlib
brew install glew
```

- cd to ./hello_square

```
make -f Makefile.osx
```

# Windows

- MinGW
- cd to ./hello_square
- make -f Makefile.win64
- cmake (chocolatey(?))


