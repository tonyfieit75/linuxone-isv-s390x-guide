# Architecture & Dependency Assessment

Audit native components:
- JNI libraries
- Embedded native engines (RocksDB, snappy, lz4, zstd)
- C/C++ dependencies
- Architecture-specific binaries

Validate:
- Endianness (s390x is big-endian)
- glibc compatibility
- Hardcoded architecture assumptions
