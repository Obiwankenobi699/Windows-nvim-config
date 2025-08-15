# Neovim Configuration - Tokyo Night Setup

![Neovim Tokyo Night](image.png)

A **full-featured Neovim configuration** featuring the **Tokyo Night theme**, optimized for productivity, coding, and modern development workflows. This setup includes LSP, Treesitter, autocompletion, file navigation, and even Jupyter-like notebook support.

---

## Features

### Theme & Appearance
- **Tokyo Night** theme with optional **Gruvbox** alternative.
- **Lualine** statusline with icons and custom sections.
- Customizable colors and theme settings in `lua/core/settings.lua`.
- **Icons** support with `nvim-web-devicons`.

### File Navigation & Search
- **Nvim Tree** file explorer.
- **Telescope.nvim** for fuzzy file search, buffers, git files, and more.

### Code Editing & Productivity
- **Treesitter** for syntax highlighting and text objects.
- **Which-key.nvim** to discover keybindings quickly.
- **Presence.nvim** for Discord Rich Presence integration.
- **Snippets** with LuaSnip and Friendly Snippets.
- **Jupyter/Notebook support** with `magma-nvim`.

### LSP & Autocompletion
- **Mason.nvim** to install and manage LSP/DAP/linters easily.
- **nvim-lspconfig** for configuring language servers.
- **nvim-cmp** for autocompletion with LuaSnip snippet integration.

### Other Utilities
- **Plenary.nvim** and **Popup.nvim** for Lua helper functions.
- Automatically installs **Packer.nvim** if not present.

---

## Screenshots

![Neovim Tokyo Night](image.png)

---

## Folder Structure

~/.config/nvim/
├── init.lua               # Main configuration entrypoint
├── image.png              # Screenshot for README
└── lua/
    └── core/
        ├── keymaps.lua           # Custom keybindings
        ├── settings.lua          # Theme and global options
        └── plugin_config/
            └── init.lua          # Packer plugin setup

---

## Plugins Used (with descriptions)

| Plugin | Description |
|--------|-------------|
| `wbthomason/packer.nvim` | Plugin manager |
| `folke/tokyonight.nvim` | Tokyo Night theme |
| `ellisonleao/gruvbox.nvim` | Alternative color scheme |
| `nvim-treesitter/nvim-treesitter` | Syntax highlighting & text objects |
| `folke/which-key.nvim` | Displays available keybindings |
| `nvim-tree/nvim-tree.lua` | File explorer |
| `nvim-tree/nvim-web-devicons` | File icons support |
| `williamboman/mason.nvim` | LSP/DAP/Linter installer |
| `williamboman/mason-lspconfig.nvim` | Mason + LSP integration |
| `neovim/nvim-lspconfig` | Language server configuration |
| `nvim-lualine/lualine.nvim` | Statusline |
| `andweeb/presence.nvim` | Discord Rich Presence |
| `hrsh7th/nvim-cmp` | Autocompletion engine |
| `hrsh7th/cmp-nvim-lsp` | LSP completion source |
| `hrsh7th/cmp-buffer` | Buffer completion source |
| `hrsh7th/cmp-path` | Path completion source |
| `L3MON4D3/LuaSnip` | Snippet engine |
| `saadparwaiz1/cmp_luasnip` | LuaSnip source for cmp |
| `rafamadriz/friendly-snippets` | Predefined snippets |
| `nvim-telescope/telescope.nvim` | Fuzzy finder |
| `dccsillag/magma-nvim` | Jupyter notebook support |

---

## Installation (Windows)

1. **Clone Repository**

```powershell
git clone https://github.com/Obiwankenobi699/nvim_Config_4Everyone.git $Env:USERPROFILE\.config\nvim
