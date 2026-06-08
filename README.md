# iam-rust-proto

Shared gRPC **contracts** for the IAM Rust microservices: the `.proto` sources and
the `proto` crate that compiles them with `tonic-build`. Consumed via a git
dependency by [iam-rust-auth](https://github.com/malvinpratama/iam-rust-auth),
[iam-rust-user](https://github.com/malvinpratama/iam-rust-user) and
[iam-rust-gateway](https://github.com/malvinpratama/iam-rust-gateway).

```toml
proto = { git = "https://github.com/malvinpratama/iam-rust-proto", tag = "v0.4.0" }
```

Requires `protobuf-compiler`. Part of the [iam-rust](https://github.com/malvinpratama/iam-rust) platform.
