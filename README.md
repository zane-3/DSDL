DroneCAN DSDL definitions
=========================

This repository contains the DSDL definitions of the standard DroneCAN
messages and services.

This DSDL is based on DroneCAN v1

For information about the Message type IDs (including how the unqiue IDs are allocated), see [**id distribution**](https://dronecan.github.io/Specification/5._Application_level_conventions/#id-distribution)

Message ID
----------

For broadcast messages the following should be used:

 - [0, 20000) Standard message types
 - [20000, 21000) Vendor-specific message types
 - [21000, 65536) Reserved for future use

For service types, the following should be used:

 - [0, 100) Standard service types
 - [100, 200) Reserved for future use
 - [200, 256) Vendor-specific service types

* [**DroneCAN website**](http://dronecan.org)

<!-- PROJECT_DOCS_START -->
## 文档与架构

- [分类文档目录](docs/README.md)
- [模块与依赖架构](docs/architecture.md)
- [仓库分支目录](docs/branches.md)
<!-- PROJECT_DOCS_END -->
