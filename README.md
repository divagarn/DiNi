# DiNi

**DiNi** is a lightweight, terminal-based Vim-like text editor written in Python using the `curses` library. It provides basic editing features such as insert mode, arrow key navigation, and `:w`, `:q`, `:wq` commands — inspired by the simplicity of Vim.

---

## ✨ Features

- Normal and Insert modes
- Cursor navigation with arrow keys
- `:w`, `:q`, `:wq` command support
- Save, load, and edit plain text files
- Written in pure Python

---

## 📦 Install via APT (Debian/Ubuntu)

### Step 1: Add the APT source

```bash
echo "deb [trusted=yes] https://divagarn.github.io/DiNi/ ./" | sudo tee /etc/apt/sources.list.d/dini.list
sudo apt update
sudo apt install dini
