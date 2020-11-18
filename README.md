# WebAssembly Demo
Credits to author:
Video over here: https://youtu.be/9lxnm9a-Yi8 
mani@maniks.net

## Getting Started

- `brew install llvm`
- `export PATH=/usr/local/opt/llvm/bin:$PATH`
- Run `llc --version` and check that `wasm32` is included
- `./compile.sh`
- `python3 -m http.server` - Note that Python2 does not support wasm
- Open `http://localhost:8000` in browser

## Resources

https://depth-first.com/articles/2019/10/16/compiling-c-to-webassembly-and-running-it-without-emscripten/
