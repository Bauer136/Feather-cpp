# Feather Lang (CPP Compiler)

Feather is a Hobby programming language built to be lightweight with the intention of being self sustained in the future. Currently features basic arithmatic, if/else statements, and a print statement.

## Building

Requires `nasm` and `ld` on a Linux operating system.

```bash
git clone https://github.com/Bauer136/Feather-cpp.git
cd feather-cpp
mkdir build
cmake -S . -B build
cmake --build build
```

Executable will be `feather` in the `build/` directory.
