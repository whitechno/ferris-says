fsays
=====

Run from `fsays` directory
```text
$ cd fsays
$ ../target/debug/fsays 'Hello fellow Rustaceans!' -w 10
$ printf 'Hello fellow Rustaceans!' | cargo run
$ cargo run -- 'Hello fellow Rustaceans!' -w 10
```

Run from workspace root
```text
-p, --package
$ cargo run -p fsays -- 'Hello fellow Rustaceans!' -w 10
```
