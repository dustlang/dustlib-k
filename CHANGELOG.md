# Changelog - dustlib_k (DPL K Regime Library)

All notable changes to dustlib_k are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.2.0] - 2026-02-12 (DPL v0.2)

### Added

- **DPL v0.2 Compliance**: Full support for v0.2 specification

#### dustlib_k_core
- K Regime-specific type definitions (Size, Offset, Address)
- System constants and limits
- Error handling for systems programming
- Low-level debugging utilities

#### dustlib_k_memory
- Heap allocation (malloc, free, realloc)
- Memory mapping (mmap, munmap)
- Buffer operations with safety guarantees
- Memory protection utilities

#### dustlib_k_concurrency
- Thread creation and management
- Mutex and synchronization primitives
- Atomic operations (load, store, fetch_add, compare_exchange)
- Thread-local storage support

#### dustlib_k_io
- File operations (open, read, write, close)
- Socket and network operations
- Device I/O and control
- Stream operations

#### dustlib_k_hardware
- Port I/O operations (in/out 8/16/32 bit)
- Interrupt handling and management
- Memory-mapped I/O operations
- CPU-specific operations

#### dustlib_k_system
- Process management (create, wait, terminate)
- System call interface
- System information retrieval
- Environment management

### Changed

- Sector structure reorganized for K Regime focus
- All stub functions now implemented
- Error handling unified across modules

### Fixed

- Thread safety in synchronization primitives
- Memory safety in hardware access operations
- Race condition fixes in atomic operations

### Removed

- Stub implementations without real functionality

## [0.1.0] - 2026-02-12

### Added

- Initial dustlib_k implementation
- Basic module structure
- API signatures for all planned functionality
- Stub implementations for documentation

### Known Issues

- Most implementations left as TODO stubs
- Requires compiler v0.2 for full functionality
- Threading not yet available

---

Copyright © 2026 Dust LLC