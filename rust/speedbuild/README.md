## linker

- Ubuntu: sudo apt-get install lld clang
- Fedora: sudo dnf install lld clang
- Arch: sudo pacman -S lld clang
- MacOS: brew install llvm
- Windows:

```bash
cargo install -f cargo-binutils
rustup component add llvm-tools-preview
```
