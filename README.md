# Atahan Demirer

Computer Engineering student interested in **backend engineering, systems programming, and networking**.

I mostly work with **Go, C, C++, and Rust**, building things to understand what happens beneath the abstractions: sockets, protocols, concurrency, memory management, and runtime behavior. I enjoy small, focused implementations as much as larger backend projects.

## Where my projects live

| Account / organization | What you'll find |
| --- | --- |
| **[M1ralai](https://github.com/M1ralai)** | My own software projects, backend services, and networking experiments. |
| **[choplib](https://github.com/choplib)** | Small, primarily C-based libraries and low-level experiments I implement to learn how the building blocks work. |
| **[Chokqu](https://github.com/Chokqu)** | AI-assisted coding experiments, rapid prototypes, and projects exploring what AI tools can build. Work there is intentionally separate from my personally implemented projects. |

The distinction matters to me: I want the code I write and the work I explore with AI to be easy to tell apart.

## Selected projects

### Backend and networking

- **[notly-api](https://github.com/M1ralai/notly-api)** — Modular Go backend with PostgreSQL, authentication, WebSockets, Google Calendar OAuth, and observability.
- **[multiplayer-snake](https://github.com/M1ralai/multiplayer-snake)** — C++20 peer-to-peer networking prototype with UDP communication and a tick-based simulation.
- **[DFS](https://github.com/M1ralai/DFS)** — Distributed storage control-plane experiment covering heartbeats, chunk placement, and replica metadata.

### Low-level work at choplib

- **[http](https://github.com/choplib/http)** — Experimental HTTP/1.1 server in C, exploring non-blocking I/O, event loops, request parsing, routing, and middleware.
- **[http-workers](https://github.com/choplib/http-workers)** — Unfinished worker-pool TCP server experiment using pthreads, a bounded queue, and socket handling.
- **[channel](https://github.com/choplib/channel)** — Bounded channel experiment in C using a circular buffer, mutex, and condition variables.
- **[dynamic-array](https://github.com/choplib/dynamic-array)** — Generic dynamic array with configurable capacity growth.
- **[arena-allocator](https://github.com/choplib/arena-allocator)** — Fixed-size-block arena allocator exploring bump allocation, alignment, and bulk memory management.

These are **learning projects**, not claims of production-ready libraries. I prefer understanding a small implementation end to end over adding features just to make it look more impressive.

### Other experiments
- **[chip-8](https://github.com/M1ralai/chip-8)** — Terminal-based CHIP-8 interpreter written in C, implementing instruction decoding, register and stack operations, sprite rendering, keyboard input, and CPU/timer scheduling without external graphics libraries.
- **[spy](https://github.com/M1ralai/spy)** — React Native party game exploring gesture-driven interfaces, in-app purchases, and offline-first state.
- **[Chokqu](https://github.com/Chokqu)** — A separate home for experiments made with substantial AI assistance. I use it to try ideas, investigate AI-assisted development workflows, and see what those tools can—and cannot—do.

## Currently exploring

- Go runtime internals, scheduling, and concurrency
- Memory management and small reusable components in C
- Networking protocols and server architecture
- The trade-offs between writing systems from scratch and using existing abstractions

I learn best by building, breaking, debugging, and revisiting things.
