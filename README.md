<h1 align="center">Native Assembly for Game Augmentation (aka NAGA)</h1>
<div align="center"><small>In Sanskrit, a nāga (नाग) primarily refers to a snake, most often specifically the Indian cobra (Naja naja)</small></div>

<h1 align="center">What is it?</h1>
<div align="center">A modular project designed to make it easier to modify games.</div>

---

The project is based on the following principles:
1. The core knowns nothing about any specific game
2. Each module is independent unless otherwise specified
3. Compatibility does not limit the platform's development
4. Contract is more important than implementation
5. And last: performance should not be sacrificed for abstractions unless necessary

<h1 align="center">Development Stack</h1>

1. Rust as the foundation for managing the entire process
2. C as low-level control of the game process and injection
