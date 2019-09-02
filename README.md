# local_ipaddress

Get your local ip address in Rust.

```
[dependencies]
local_ipaddress = "0.1.0"
```

then

```rust
extern crate local_ipaddress;

fn main() {
    println!("{}", local_ipaddress::get().unwrap());
}
```

It works fine with both `Windows` and `Linux`.

### License

MIT
