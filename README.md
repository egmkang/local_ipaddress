# local_ipaddress

Get your local ip address in Rust, using `UdpSocket` to get local ip address(not `network interface` or `ifconfig`), and won't `panic`.

API Docs: [https://docs.rs/local_ipaddress](https://docs.rs/local_ipaddress)

### Usage

Add this to your Cargo.toml:


```
[dependencies]
local_ipaddress = "0.1.3"
```

### Getting Started

```rust
use local_ipaddress;

fn main() {
    println!("{}", local_ipaddress::get().unwrap());
}
```

Tested and working with:
- Linux
- Windows
- macOS
- Android
- FreeBSD
- NetBSD

### License

MIT
