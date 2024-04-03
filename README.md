playing around with webassembly

- for rust file run `rustc --target wasm32-unknown-unknown -O example.rs -o example-rust.wasm`
- for C++ file run `emcc example.cpp -o example-cpp.wasm`
- run `python -m http.server` to serve files (CORS error will happen if doesn't)