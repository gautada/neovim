# Neovim Shortcut Library

A curated reference for Neovim shortcuts used in this environment.
Custom keybindings specific to this configuration are marked with 🔧.

---

## Navigation

| Mode   | Keys             | Action                           |
| ------ | ---------------- | -------------------------------- |
| Normal | `h / j / k / l`  | Move left / down / up / right    |
| Normal | `gg`             | Jump to first line               |
| Normal | `G`              | Jump to last line                |
| Normal | `Ctrl-d`         | Scroll half-page down            |
| Normal | `Ctrl-u`         | Scroll half-page up              |
| Normal | `%`              | Jump to matching bracket         |
| Normal | `*`              | Search for word under cursor     |
| Normal | `n / N`          | Next / previous search match     |
| Normal | `gd`             | Go to definition (LSP)           |
| Normal | `gr`             | Go to references (LSP)           |
| Normal | `K`              | Hover documentation (LSP)        |

---

## Windows / Splits

| Mode   | Keys             | Action                           |
| ------ | ---------------- | -------------------------------- |
| Normal | `Ctrl-w s`       | Horizontal split                 |
| Normal | `Ctrl-w v`       | Vertical split                   |
| Normal | `Ctrl-w h/j/k/l` | Move focus between splits        |
| Normal | `Ctrl-w =`       | Equalize split sizes             |
| Normal | `Ctrl-w q`       | Close current split              |

---

## Tabs

Reference: https://neovim.io/doc/user/tabpage.html

| Mode   | Keys             | Action                           |
| ------ | ---------------- | -------------------------------- |
| Normal | `:tabnew`        | Open a new tab                   |
| Normal | `gt`             | Go to next tab                   |
| Normal | `gT`             | Go to previous tab               |
| Normal | `{N}gt`          | Go to tab number N               |
| Normal | `:tabclose`      | Close current tab                |
| Normal | `:tabonly`       | Close all other tabs             |

---

## File Explorer (Neo-tree) 🔧

| Mode   | Keys              | Action                             |
| ------ | ----------------- | ---------------------------------- |
| Normal | `<leader>exf`     | Float file explorer                |
| Normal | `<leader>exs`     | Sidebar file explorer              |
| Normal | `<leader>exp`     | Buffer list (float)                |
| Normal | `h` (in tree)     | Navigate up one directory          |

---

## Search (Telescope) 🔧

| Mode   | Keys          | Action                             |
| ------ | ------------- | ---------------------------------- |
| Normal | `<leader>ff`  | Find files                         |
| Normal | `<leader>fg`  | Live grep (search text in files)   |
| Normal | `<leader>fp`  | Project picker (project.nvim)      |

---

## Terminal (toggleterm) 🔧

| Mode     | Keys    | Action                          |
| -------- | ------- | ------------------------------- |
| Normal   | `<C-t>` | Toggle floating terminal (zsh)  |
| Terminal | `<C-t>` | Close floating terminal         |

---

## Editing

| Mode   | Keys           | Action                              |
| ------ | -------------- | ----------------------------------- |
| Normal | `<leader>/`    | Toggle line comment                 |
| Normal | `u`            | Undo                                |
| Normal | `Ctrl-r`       | Redo                                |
| Normal | `ciw`          | Change inner word                   |
| Normal | `yiw`          | Yank inner word                     |
| Normal | `di{`          | Delete inside braces                |
| Visual | `>`            | Indent right                        |
| Visual | `<`            | Indent left                         |

---

## LSP

| Mode   | Keys           | Action                              |
| ------ | -------------- | ----------------------------------- |
| Normal | `gd`           | Go to definition                    |
| Normal | `gr`           | Go to references                    |
| Normal | `K`            | Hover docs                          |
| Normal | `<leader>rn`   | Rename symbol                       |
| Normal | `<leader>ca`   | Code action                         |
| Normal | `[d` / `]d`    | Previous / next diagnostic          |
| Normal | `<leader>e`    | Show diagnostic float               |

---

## Git (vim-fugitive)

| Mode   | Keys           | Action                              |
| ------ | -------------- | ----------------------------------- |
| Normal | `:Git`         | Open Fugitive status                |
| Normal | `:Git diff`    | Diff working tree                   |
| Normal | `:Git commit`  | Open commit editor                  |
| Normal | `:Git push`    | Push to remote                      |

---

## Custom Leader Reference

`<leader>` is mapped to `Space` in this configuration.

| Prefix        | Domain                     |
| ------------- | -------------------------- |
| `<leader>ex`  | File explorer              |
| `<leader>f`   | Search / find              |
| `<leader>/`   | Comment toggle             |
