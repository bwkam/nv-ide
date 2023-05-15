<p align="center">
  <img src="https://raw.githubusercontent.com/crivotz/nv-ide/master/screenshots/NV-IDE.svg?raw=true"/>
</p>

[Neovim](https://neovim.io/) LUA configuration, oriented for web developers (rails, ruby, php, html, css, SCSS, javascript).  
I use this repository mainly to keep track of the changes that I made on my Neovim configuration, but I hope that it will be useful to other  
The project is constantly changing  
You can find old no-lua and coc version under branch `old_coc_version`
You can find old packer version under branch `old_packer`

Thanks to the developers of these plugins/color schemes

![nv-ide + startify](https://raw.githubusercontent.com/crivotz/nv-ide/master/screenshots/nv-ide_screenshot_0.png)
![nv-ide + nvim-compe + nvimtree ](https://raw.githubusercontent.com/crivotz/nv-ide/master/screenshots/nv-ide_screenshot_1.png)
![nv-ide + telescope ](https://raw.githubusercontent.com/crivotz/nv-ide/master/screenshots/nv-ide_screenshot_2.png)
![nv-ide + which-key ](https://raw.githubusercontent.com/crivotz/nv-ide/master/screenshots/nv-ide_screenshot_3.png)
![nv-ide + lazygit ](https://raw.githubusercontent.com/crivotz/nv-ide/master/screenshots/nv-ide_screenshot_4.png)
![nv-ide + noice + markid ](https://raw.githubusercontent.com/crivotz/nv-ide/master/screenshots/nv-ide_screenshot_5.png)

---

**SYNTAX**

Check [tree-sitter](https://github.com/tree-sitter/tree-sitter) for full list.  

**INSTALLATION**
```console
git clone --depth 1 https://github.com/crivotz/nv-ide.git ~/.nv-ide
cd ~/.config
ln -s ~/.nv-ide nvim
nvim
```
**DEPENDENCIES**

* Neovim
* [Universal-ctags](https://github.com/universal-ctags/ctags) with JSON format
* [FZF](https://github.com/junegunn/fzf)
* [ripgrep](https://github.com/BurntSushi/ripgrep): ripgrep recursively searches directories for a regex pattern  
* [Ripper-tags](https://github.com/tmm1/ripper-tags)
* [prettierd](https://github.com/fsouza/prettierd) for formatter.nvim install via Mason `MasonInstall prettierd`
* Needed DAP, show `lua/plugins/nvim-dap.lua` install via Mason for `node` with `MasonInstall node-debug2-adapter`
* Needed LSP, show `lua/lsp/init.lua` installed automatically with Mason
* Terminal that supports ligatures for proper representation

**SUGGESTION**

* Font: [JetBrains Mono](https://www.jetbrains.com/lp/mono/)
* [dot_files](https://github.com/crivotz/dot_files)

**PLUGINS.LUA**  

* [sainnhe/gruvbox-material](https://github.com/sainnhe/gruvbox-material): Gruvbox with Material Palette  
* [MunifTanjim/nui.nvim](https://github.com/MunifTanjim/nui.nvim): UI Component Library for Neovim.  
* [onsails/lspkind-nvim](https://github.com/onsails/lspkind-nvim): vscode-like pictograms for neovim lsp completion items  
* [weilbith/nvim-code-action-menu](https://github.com/weilbith/nvim-code-action-menu): Pop-up menu for code actions to show meta-information and diff preview  
* [hrsh7th/nvim-cmp](https://github.com/hrsh7th/nvim-cmp): A completion plugin for neovim coded in Lua.  
* [hrsh7th/cmp-buffer](https://github.com/hrsh7th/cmp-buffer): nvim-cmp source for buffer words  
* [hrsh7th/cmp-vsnip](https://github.com/hrsh7th/cmp-vsnip): nvim-cmp source for vim-vsnip  
* [hrsh7th/vim-vsnip](https://github.com/hrsh7th/vim-vsnip): Snippet plugin for vim/nvim that supports LSP/VSCode's snippet format.  
* [hrsh7th/cmp-path](https://github.com/hrsh7th/cmp-path): nvim-cmp source for path  
* [hrsh7th/cmp-calc](https://github.com/hrsh7th/cmp-calc): nvim-cmp source for math calculation  
* [hrsh7th/cmp-cmdline](https://github.com/hrsh7th/cmp-cmdline): nvim-cmp source for vim's cmdline  
* [ray-x/cmp-treesitter](https://github.com/ray-x/cmp-treesitter): cmp source for treesitter  
* [lukas-reineke/cmp-rg](https://github.com/lukas-reineke/cmp-rg): ripgrep source for nvim-cmp  
* [quangnguyen30192/cmp-nvim-tags](https://github.com/quangnguyen30192/cmp-nvim-tags): tags sources for nvim-cmp  
* [rafamadriz/friendly-snippets](https://github.com/rafamadriz/friendly-snippets): Set of preconfigured snippets for different languages.  
* [windwp/nvim-ts-autotag](https://github.com/windwp/nvim-ts-autotag): Use treesitter to auto close and auto rename html tag  
* [David-Kunz/markid](https://github.com/David-Kunz/markid): A Neovim extension to highlight same-name identifiers with the same color.  
* [nvim-treesitter/nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter): Nvim Treesitter configurations and abstraction layer  
* [mrjones2014/nvim-ts-rainbow](https://github.com/mrjones2014/nvim-ts-rainbow): Rainbow parentheses for neovim using tree-sitter.  
* [luukvbaal/statuscol.nvim](https://github.com/luukvbaal/statuscol.nvim): Status column plugin that provides a configurable 'statuscolumn' and click handlers.  
* [lukas-reineke/indent-blankline.nvim](https://github.com/lukas-reineke/indent-blankline.nvim): Indent guides for Neovim  
* [JoosepAlviste/nvim-ts-context-commentstring](https://github.com/JoosepAlviste/nvim-ts-context-commentstring): Neovim treesitter plugin for setting the commentstring based on the cursor location in a file.  
* [nvim-treesitter/nvim-treesitter-context](https://github.com/nvim-treesitter/nvim-treesitter-context): Show code context  
* [SmiteshP/nvim-gps](https://github.com/SmiteshP/nvim-gps): Simple statusline component that shows what scope you are working inside  
* [AckslD/nvim-neoclip.lua](https://github.com/AckslD/nvim-neoclip.lua): Clipboard manager neovim plugin with telescope integration  
* [nacro90/numb.nvim](https://github.com/nacro90/numb.nvim): Peek lines just when you intend  
* [karb94/neoscroll.nvim](https://github.com/karb94/neoscroll.nvim): Smooth scrolling neovim plugin written in lua  
* [tpope/vim-rails](https://github.com/tpope/vim-rails): rails.vim: Ruby on Rails power tools  
* [tpope/vim-abolish](https://github.com/tpope/vim-abolish): abolish.vim: Work with several variants of a word at once  
* [tpope/vim-sleuth](https://github.com/tpope/vim-sleuth): sleuth.vim: Heuristically set buffer options  
* [tpope/vim-bundler](https://github.com/tpope/vim-bundler): bundler.vim: Lightweight support for Ruby's Bundler  
* [tpope/vim-capslock](https://github.com/tpope/vim-capslock): capslock.vim: Software caps lock  
* [tpope/vim-repeat](https://github.com/tpope/vim-repeat): repeat.vim: enable repeating supported plugin maps with "."  
* [tpope/vim-endwise](https://github.com/tpope/vim-endwise): endwise.vim: Wisely add  
* [tpope/vim-dispatch](https://github.com/tpope/vim-dispatch): dispatch.vim: Asynchronous build and test dispatcher  
* [tpope/vim-dadbod](https://github.com/tpope/vim-dadbod): dadbod.vim: Modern database interface for Vim  
* [tpope/vim-jdaddy](https://github.com/tpope/vim-jdaddy): jdaddy.vim: JSON manipulation and pretty printing  
* [tpope/vim-fugitive](https://github.com/tpope/vim-fugitive): fugitive.vim: A Git wrapper so awesome, it should be illegal  
* [christoomey/vim-tmux-navigator](https://github.com/christoomey/vim-tmux-navigator): Seamless navigation between tmux panes and vim splits  
* [ludovicchabant/vim-gutentags](https://github.com/ludovicchabant/vim-gutentags): A Vim plugin that manages your tag files  
* [rcarriga/nvim-dap-ui](https://github.com/rcarriga/nvim-dap-ui): A UI for nvim-dap  
* [theHamsta/nvim-dap-virtual-text](https://github.com/theHamsta/nvim-dap-virtual-text):   
* [folke/todo-comments.nvim](https://github.com/folke/todo-comments.nvim): ✅ Highlight, list and search todo comments in your projects  
* [folke/which-key.nvim](https://github.com/folke/which-key.nvim): 💥 Create key bindings that stick. WhichKey is a lua plugin for Neovim 0.5 that displays a popup with possible keybindings of the command you started typing.  
* [airblade/vim-rooter](https://github.com/airblade/vim-rooter): Changes Vim working directory to project root.  
* [gorbit99/codewindow.nvim](https://github.com/gorbit99/codewindow.nvim):   
* [jeffkreeftmeijer/vim-numbertoggle](https://github.com/jeffkreeftmeijer/vim-numbertoggle): Toggles between hybrid and absolute line numbers automatically  
* [nvim-zh/colorful-winsep.nvim](https://github.com/nvim-zh/colorful-winsep.nvim): Make your nvim window separators colorful  
* [folke/zen-mode.nvim](https://github.com/folke/zen-mode.nvim): 🧘 Distraction-free coding for Neovim  
* [AckslD/muren.nvim](https://github.com/AckslD/muren.nvim): Multiple replacements in neovim  
* [lambdalisue/suda.vim](https://github.com/lambdalisue/suda.vim): 🥪 An alternative sudo.vim for Vim and Neovim, limited support sudo in Windows  
* [andymass/vim-matchup](https://github.com/andymass/vim-matchup): vim match-up: even better % 👊 navigate and highlight matching words 👊 modern matchit and matchparen. Supports both vim and neovim + tree-sitter.  
* [chrisbra/csv.vim](https://github.com/chrisbra/csv.vim): A Filetype plugin for csv files  
* [kazhala/close-buffers.nvim](https://github.com/kazhala/close-buffers.nvim): 📑 Delete multiple vim buffers based on different conditions  
* [folke/twilight.nvim](https://github.com/folke/twilight.nvim): 🌅 Twilight is a Lua plugin for Neovim 0.5 that dims inactive portions of the code you're editing using TreeSitter.  
* [zdharma-continuum/zinit-vim-syntax](https://github.com/zdharma-continuum/zinit-vim-syntax): A Vim syntax definition for Zinit commands in any ft=zsh file  
* [nvim-tree/nvim-web-devicons](https://github.com/nvim-tree/nvim-web-devicons): lua `fork` of vim-web-devicons for neovim  
* [rhysd/committia.vim](https://github.com/rhysd/committia.vim): A Vim plugin for more pleasant editing on commit messages  
* [chaoren/vim-wordmotion](https://github.com/chaoren/vim-wordmotion): More useful word motions for Vim  
* [windwp/nvim-spectre](https://github.com/windwp/nvim-spectre): Find the enemy and replace them with dark power.  
* [folke/trouble.nvim](https://github.com/folke/trouble.nvim): 🚦 A pretty diagnostics, references, telescope results, quickfix and location list to help you solve all the trouble your code is causing.  
* [mrbjarksen/neo-tree-diagnostics.nvim](https://github.com/mrbjarksen/neo-tree-diagnostics.nvim): A diagnostics source for neo-tree.nvim  

**PLUGINS AS MODULE**  

* [nvim-telescope/telescope.nvim](https://github.com/nvim-telescope/telescope.nvim): Find, Filter, Preview, Pick. All lua, all the time.  
* [nvim-lua/popup.nvim](https://github.com/nvim-lua/popup.nvim): [WIP] An implementation of the Popup API from vim in Neovim. Hope to upstream when complete  
* [nvim-lua/plenary.nvim](https://github.com/nvim-lua/plenary.nvim): plenary: full; complete; entire; absolute; unqualified. All the lua functions I don't want to write twice.  
* [cljoly/telescope-repo.nvim](https://github.com/cljoly/telescope-repo.nvim): 🦘 Jump into the repositories (git, mercurial…) of your filesystem with telescope.nvim, without any setup  
* [nvim-telescope/telescope-dap.nvim](https://github.com/nvim-telescope/telescope-dap.nvim): Integration for nvim-dap with telescope.nvim  
* [nvim-telescope/telescope-fzf-native.nvim](https://github.com/nvim-telescope/telescope-fzf-native.nvim): FZF sorter for telescope written in c  
* [nvim-telescope/telescope-fzy-native.nvim](https://github.com/nvim-telescope/telescope-fzy-native.nvim): FZY style sorter that is compiled  
* [nvim-telescope/telescope-live-grep-args.nvim](https://github.com/nvim-telescope/telescope-live-grep-args.nvim): Live grep with args  
* [pwntester/octo.nvim](https://github.com/pwntester/octo.nvim): Edit and review GitHub issues and pull requests from the comfort of your favorite editor  
* [freddiehaddad/feline.nvim](https://github.com/freddiehaddad/feline.nvim): A minimal, stylish and customizable statusline, statuscolumn, and winbar for Neovim  
* [nvim-neo-tree/neo-tree.nvim](https://github.com/nvim-neo-tree/neo-tree.nvim): Neovim plugin to manage the file system and other tree like structures.  
* [/](https://github.com//):   
* [rcarriga/nvim-notify](https://github.com/rcarriga/nvim-notify): A fancy, configurable, notification manager for NeoVim  
* [lewis6991/gitsigns.nvim](https://github.com/lewis6991/gitsigns.nvim): Git integration for buffers  
* [mhartington/formatter.nvim](https://github.com/mhartington/formatter.nvim):   
* [ggandor/leap.nvim](https://github.com/ggandor/leap.nvim): Neovim's answer to the mouse 🦘  
* [ggandor/flit.nvim](https://github.com/ggandor/flit.nvim): Enhanced f/t motions for Leap  
* [neovim/nvim-lspconfig](https://github.com/neovim/nvim-lspconfig): Quickstart configs for Nvim LSP  
* [williamboman/mason.nvim](https://github.com/williamboman/mason.nvim): Portable package manager for Neovim that runs everywhere Neovim runs. Easily install and manage LSP servers, DAP servers, linters, and formatters.  
* [williamboman/mason-lspconfig.nvim](https://github.com/williamboman/mason-lspconfig.nvim): Extension to mason.nvim that makes it easier to use lspconfig with mason.nvim. Strongly recommended for Windows users.  
* [hrsh7th/cmp-nvim-lsp](https://github.com/hrsh7th/cmp-nvim-lsp): nvim-cmp source for neovim builtin LSP client  
* [kevinhwang91/nvim-hlslens](https://github.com/kevinhwang91/nvim-hlslens): Hlsearch Lens for Neovim  
* [windwp/nvim-autopairs](https://github.com/windwp/nvim-autopairs): autopairs for neovim written by lua  
* [nvchad/nvim-colorizer.lua](https://github.com/nvchad/nvim-colorizer.lua): Maintained fork of the fastest Neovim colorizer  
* [noib3/nvim-cokeline](https://github.com/noib3/nvim-cokeline): 👃 A Neovim bufferline for people with addictive personalities  
* [mfussenegger/nvim-dap](https://github.com/mfussenegger/nvim-dap): Debug Adapter Protocol client implementation for Neovim  
* [akinsho/nvim-toggleterm.lua](https://github.com/akinsho/nvim-toggleterm.lua): A neovim lua plugin to help easily manage multiple terminal windows  
* [folke/noice.nvim](https://github.com/folke/noice.nvim): 💥 Highly experimental plugin that completely replaces the UI for messages, cmdline and the popupmenu.  
* [machakann/vim-sandwich](https://github.com/machakann/vim-sandwich): Set of operators and textobjects to search/select/edit sandwiched texts.  
* [numToStr/Comment.nvim](https://github.com/numToStr/Comment.nvim): 🧠 💪 // Smart and powerful comment plugin for neovim. Supports treesitter, dot repeat, left-right/up-down motions, hooks, and more  
