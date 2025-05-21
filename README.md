# FerraOS

**FerraOS** is a Rust-based experimental operating system focused on safety, performance, and modularity. Built from the ground up using modern language features, it aims to provide a secure and efficient systems programming foundation.

---

## ✨ Features

- ⚙️ Memory-safe kernel (Rust, `#![no_std]`)
- 🧩 Modular architecture with future desktop environment support
- 🔐 Strong emphasis on concurrency and system safety
- 🧪 Ideal for experimentation, research, and educational use

---

## 🚀 Getting Started

### Prerequisites

- Rust (nightly)
- QEMU (for virtualization)
- bootimage (cargo tool)

```bash
rustup default nightly
rustup component add rust-src llvm-tools-preview
cargo install bootimage
sudo apt install qemu-system-x86
```

---
## License
* FerraOS is released under the MIT License.

---
## Contributing
* Contributions are welcome! Please open issues or pull requests to collaborate.

