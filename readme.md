### 运行

```sh
cargo build --target wasm32-unknown-unknown # 编译rust 为webassembly
wasm-bindgen target/wasm32-unknown-unknown/debug/js_hello_world.wasm --out-dir . ##  output the wasm to javascript bindings
npm run build # transpile es6 wasm improt 
npm run serve # see in broswer
```