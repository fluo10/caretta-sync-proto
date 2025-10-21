# caretta-sync-proto

Protobuf definitions for [caretta-sync](https://github.com/fluo10/caretta-sync).

## Usage

### Installation

Add this repository and [mtid-proto](https://github.com/fluo10/mtid-proto) (imported by some protobuf files in this repository) to your project.

```bash
git submodule add https://github.com/fluo10/caretta-sync-proto
git submodule add https://github.com/fluo10/mtid-proto
```

### Compilation

You must specify the added directories using the `--proto_path` option during compilation.

```bash
protoc --proto_path=mtid-proto --proto_path=caretta-sync-proto --rust_out=BUILD_DIR authorized_node/authorized_node.proto
```

## License

Licensed under either of:

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE))
- MIT License ([LICENSE-MIT](LICENSE-MIT))

at your option.