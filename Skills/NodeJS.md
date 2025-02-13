## Node.js and backend

- Internals and concepts
  - Strong and weak sides of node.js
  - Stateful and stateless servers
  - Nonblocking I/O and slocking code
  - Event loop: phases
  - Event loop: microtasks and macrotasks
  - Garbage collection
  - Node.js LTS schedule
  - I/O-bound, CPU-bound, memory-bound tasks
  - Interactive applications (close to real-time)
- Modularity, layers and dependencies
  - CommonJS modules: 🖐️ used
  - ECMAScript modules: 🖐️ used
  - node:module: 🖐️ used
  - Caching in CJS and ESM: 👂 heard
  - Modules as singletons: 🎓 known
  - Contexts and scripts node:vm
  - Dependencies: npm, node_modules: 🖐️ used
  - Dependencies: package.json and package lock: 🖐️ used
  - Module-based permissions model
  - Isolation with modularity
  - Dependency injection: 🖐️ used
  - DI containers
  - Coupling and cohesion: 🎓 known
  - Framework agnostic approach: 👂 heard
- Environment
  - Command line arguments: 🖐️ used
  - Node.js CLI: 🖐️ used 
  - Process-based permissions
  - Graceful shutdown: 👂 heard
  - Clustering
  - Watch filesystem changes with --watch
- Internal API
  - Streams API: 👂 heard
  - Web Streams API: 👂 heard
  - Crypto API: 🖐️ used
  - Password hashing with node:crypto.scrypt: 🖐️ used
  - Web Crypto API
  - File system API: sync and async: 🖐️ used
  - Copy folder recursively
  - Worker threads
  - Performance hooks
  - Native fetch and nodejs/undici
  - node:async_hooks
  - AsyncLocalStorage
  - AsyncResource
  - Deprecated domain API
  - Node.js single executable
  - Stream back pressure
  - SharedArrayBuffer: 👂 heard
  - node:worker_threads
  - node:child_process
  - MessageChannel, MessagePort
  - BroadcastChannel
  - Generating crypto random UUID
  - node:url vs new URL
  - node:assert: 👂 heard
  - Internationalization
  - Blob, File, Buffer, node:buffer: 👂 heard
  - Module node:zlib
- Application structure and architecture
  - Isolation between layer: 👂 heard
  - Multilayer approach
  - Separation of concerns: 👂 heard
  - Inversion of control: 👂 heard
  - Dependency injection: 🖐️ used
  - GRASP: 👂 heard
  - SOLID: 👂 heard
  - GoF patterns: 👂 heard
  - Distributed systems
  - Highload applications
  - Clean architecture
  - DDD: 👂 heard
  - Message Queue
  - CQS
  - CQRS
  - Event sourcing
  - Load balancing
  - Serverless clouds
  - FaaS clouds
  - Fat controller
  - GoF for Node.js
  - Leaking abstractions
- Network
  - IP sticky sessions
  - Endpoint throttling
  - HTTP(S): 🖐️ used
  - TCP/SSL: 🖐️ used
  - UDP: 🖐️ used 
  - TLS
  - Websocket:  🖐️ used
  - SSE
  - HTTP/3 (QUIC)
  - Long polling: 🖐️ used
  - REST: 🖐️ used
  - RPC
  - Routing: 🖐️ used
  - DoS
  - DDoS
  - XSS
  - Path traversal
  - CSRF
  - DNS
  - Fetch API
  - IncomingMessage
  - SQL injection
  - noDelay
  - keep-alive
  - ALPN
  - SNI callback
  - SSL certificates
  - Protocol agnostic approach
- Technique and tools
  - Native test runner
  - Logging
  - Application configuring
  - Testing: 🖐️ used
  - CI/CD
  - Readable: 🖐️ used
  - Writable: 🖐️ used
  - Transform
  - back pressure
  - Buffer: 🖐️ used
  - Console: 🖐️ used 
  - Inspector
  - Reliability
  - Quality
  - Availability
  - Flexibility
- Data access
  - Data access layer
  - Repository
  - Active record
  - Query builder
  - Object-Relational Mapping
- Error handling and debugging
  - Error: 🖐️ used
  - error.cause: 👂 heard
  - error.code: 🖐️ used
  - error.message: 🖐️ used
  - error.stack: 🖐️ used 
  - How to avoid mixins
  - Error.captureStackTrace
  - Uncaught exceptions: 🎓 known
  - Heap dump: 👂 heard
  - Debugging tools: 🎓 known
  - Flame graph
  - Memory leaks: 🎓 known
  - Resource leaks
  - Data race
- Integrations and bindings
  - Native addons: 🎓 known
  - C and C++ addons
  - Rust addons
  - Zig addons
  - NAN (Native Abstractions for Node.js)
  - Node-API (formerly N-API)
  - NAPI C and C++
  - NAPI Rust
  - NAPI Zig
  - Webassembly WAT
  - Webassembly C and C++
  - Webassembly Rust
  - Webassembly Zig
  - Webassembly AssemblyScript
  - Shared memory
  - SharedArrayBuffer
  - V8 binary serialization
