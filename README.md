# Debde

## What is Debde
🛴 WIP: QUIC based distributed server for Games written in Pure Rust

# Getting Started
## Configuration
Debde requires a debde.conf file to run.  
A blank debde.conf file will run with all default settings. To generate one, run:
```shell
mkdir -p ~/.debde
touch ~/.debde/debde.conf
```
## Building 
```rust
cargo build
```

## Use
Now, run Debde!  
Currently, Debde is only officially supported on Ubuntu.
```rust
cargo run --bin debde
```

# License
For license information see the file [LICENSE](https://github.com/zTgx/Debde/blob/main/LICENSE).