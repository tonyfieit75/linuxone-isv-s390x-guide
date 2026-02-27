# Architecture & Dependency Assessment

## Objective
Ensure workload is architecture-neutral before build conversion.

### Native Dependencies
- JNI libraries
- RocksDB / embedded engines
- C/C++ compiled modules
- Compression libraries
- Go binaries compiled for specific architecture
- Go applications using CGO

### Endianness
s390x is Big-Endian. Validate serialization logic.

### CPU Assumptions
Remove x86-specific assembly.

### glibc Compatibility
Ensure alignment with RHEL 8/9.
