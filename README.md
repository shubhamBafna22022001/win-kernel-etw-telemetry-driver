# Windows Kernel Telemetry Driver (ETW)

This project implements a kernel-mode driver in C/C++ that streams system-level telemetry — including CPU, memory, and I/O counters — using Event Tracing for Windows (ETW).

It demonstrates:

- IRQL-safe logging and ring-buffer logic
- Kernel event registration via `EtwRegister` and `EtwWrite`
- Real-time trace generation for system diagnostics and performance monitoring
- Safe multiprocessor execution and DMA readiness

> 🔒 The full source code is available upon request to potential employers.  
Please reach out via LinkedIn or email to request access.
