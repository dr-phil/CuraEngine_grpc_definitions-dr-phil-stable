# gRPC definitions for CuraEngine
This repository contains the gRPC proto definitions for CuraEngine. These definitions are used to generate the gRPC code for the CuraEngine gRPC plugin system.

## Overview
As part of the [CuraEngine](https://github.com/Ultimaker/CuraEngine) plugin system, the CuraEngine exposes a gRPC server. This server can be used to extend the functionality of the CuraEngine. The gRPC server is defined using the [Protocol Buffers](https://developers.google.com/protocol-buffers) format. This repository contains the definitions for the gRPC server and client(s).

## Usage
The gRPC definitions are available for the following languages:

<details>
  <summary>Conan</summary>

  TODO
</details>

<details>
  <summary>Python</summary>

  TODO
</details>

<details>
  <summary>Rust</summary>
  Required dependencies before the gRPC defintions can be used are: [`protoc`, `protobuf`](https://github.com/hyperium/tonic#dependencies).
  
  Then add the following package to your `Cargo.toml`:
  ```bash
  cargo add --git https://github.com/Ultimaker/curaengine_grpc_defintions.git
  ```
</details>
<details>
  <summary>Conan</summary>
</details>

## License

This project is licensed under the [MIT license](LICENSE).