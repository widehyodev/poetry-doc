# Poetry-doc

Read pydoc for poetry project within vim editor. installed packages and your functions and classes.



https://github.com/user-attachments/assets/fa882389-5adc-484e-a2d3-a4b0640566f9



## Prerequisites

Before installing and using the poetrydoc plugin, please ensure that your system has the following prerequisites installed:

- **Vim 8 or newer:**
  This plugin leverages Vim's popup window feature, which is available in Vim 8+.

- **Poetry:**
  Poetry is used to manage your Python environment and dependencies. Install Poetry by following the [official documentation](https://python-poetry.org/docs/#installing-with-the-official-installer). Check your installation:
  ```bash
  poetry --version
  ```

- **ctags:**
  `ctags` is used to generate tags for your Python project. Install `ctags` using your system's package manager. For example:
  - On `Ubuntu/Debian:`
  ```bash
  sudo apt-get install exuberant-ctags
  ```
  - On `macOS(using Homebrew):`
  ```bash
  brew install ctags
  ```

## Install
- **Vundle.vim**
```
Plugin 'widehyodev/poetry-doc'
```

## How to use it

press `<leader>K` for show pydoc under cursor.

popup supports navigation with j, k, `<c-f>`, `<c-b>`, `<c-d>`, `<c-u>`, g(go to first line), G(go to last line), 1-9(press 1 to jump 10% of line, 2 for 20% of line). press q to quit popup.

this does not support python builtin functions like sum, len, etc. if you want to see pydoc for it, jusk use `K`, default key for it.

