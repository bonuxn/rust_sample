# rust_sample

## use_dependencies

パッケージの使用方法について学びます。  
パッケージは、Rustでクレートと呼ぶそうです。

Cargo.tomlで使用するクレートを管理する  
```toml
[dependencies]
ferris-says = "0.3.1"
```
クレート内の関数を使用する場合は、
ソースコードで以下の処理を追加する
```rust
use ferris_says::say;
```