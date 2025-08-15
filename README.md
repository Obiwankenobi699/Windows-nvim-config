# Windows-nvim-config
<div style="background-color:#1a1b26; color:#c0caf5; padding: 20px; border-radius: 10px;">

<h1 style="color:#7aa2f7;">Neovim Configuration - Tokyo Night Setup</h1>

<img src="image.png" alt="Neovim Tokyo Night" style="width:100%; max-width:600px; border-radius:10px; margin-bottom:20px;"/>

<p>A full-featured <strong>Neovim configuration</strong> with the beautiful <strong>Tokyo Night theme</strong>, focused on productivity, LSP, autocompletion, and modern development experience.</p>

<h2 style="color:#bb9af7;">Features</h2>
<ul>
  <li><strong>Theme & Appearance:</strong> Tokyo Night & optional Gruvbox theme, Lualine, icons</li>
  <li><strong>File Navigation:</strong> Nvim Tree, Telescope fuzzy finder</li>
  <li><strong>LSP & Autocompletion:</strong> Mason, nvim-lspconfig, nvim-cmp, LuaSnip</li>
  <li><strong>Code Editing & Productivity:</strong> Treesitter, Which-key, Presence.nvim, Snippets, Magma.nvim</li>
</ul>

<h2 style="color:#bb9af7;">Installation</h2>
<pre style="background-color:#16161e; color:#c0caf5; padding:10px; border-radius:5px;">
git clone https://github.com/Obiwankenobi699/nvim_Config_4Everyone.git ~/.config/nvim
nvim
:PackerSync
</pre>

<h2 style="color:#bb9af7;">Folder Structure</h2>
<pre style="background-color:#16161e; color:#c0caf5; padding:10px; border-radius:5px;">
~/.config/nvim/
├── init.lua
├── image.png
└── lua/
    └── core/
        ├── keymaps.lua
        ├── plugin_config/
        │   └── init.lua
        └── settings.lua
</pre>

<h2 style="color:#bb9af7;">Plugins Used</h2>
<ul>
  <li>wbthomason/packer.nvim</li>
  <li>nvim-lua/plenary.nvim</li>
  <li>folke/tokyonight.nvim</li>
  <li>ellisonleao/gruvbox.nvim</li>
  <li>nvim-treesitter/nvim-treesitter</li>
  <li>folke/which-key.nvim</li>
  <li>nvim-tree/nvim-tree.lua</li>
  <li>williamboman/mason.nvim</li>
  <li>neovim/nvim-lspconfig</li>
  <li>nvim-lualine/lualine.nvim</li>
  <li>andweeb/presence.nvim</li>
  <li>hrsh7th/nvim-cmp + LuaSnip + friendly-snippets</li>
  <li>nvim-telescope/telescope.nvim</li>
  <li>dccsillag/magma-nvim</li>
</ul>

<h2 style="color:#bb9af7;">Tips & Configuration</h2>
<ul>
  <li><strong>Change Theme:</strong> Open <code>lua/core/settings.lua</code> and set your preferred theme:
    <pre style="background-color:#16161e; color:#c0caf5; padding:5px;">vim.cmd("colorscheme tokyonight")</pre>
  </li>
  <li><strong>Keymaps:</strong> Add custom shortcuts in <code>lua/core/keymaps.lua</code>. Example:
    <pre style="background-color:#16161e; color:#c0caf5; padding:5px;">vim.api.nvim_set_keymap('n', '<leader>ff', ':Telescope find_files<CR>', { noremap = true, silent = true })</pre>
  </li>
  <li><strong>Add Plugins:</strong> Edit <code>lua/core/plugin_config/init.lua</code> and run <code>:PackerSync</code>.</li>
  <li><strong>LSP Servers:</strong> Install or configure servers via Mason:
    <pre style="background-color:#16161e; color:#c0caf5; padding:5px;">:Mason</pre>
  </li>
  <li><strong>Update Plugins:</strong> Run:
    <pre style="background-color:#16161e; color:#c0caf5; padding:5px;">:PackerSync</pre>
  </li>
  <li><strong>Notebook Cells:</strong> Use <code>magma-nvim</code> to execute code cells. Example:
    <pre style="background-color:#16161e; color:#c0caf5; padding:5px;">:MagmaInit</pre>
  </li>
</ul>

</div>

