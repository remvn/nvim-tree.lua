# Changelog

## [1.6.1](https://github.com/nvim-tree/nvim-tree.lua/compare/nvim-tree-v1.6.0...nvim-tree-v1.6.1) (2024-09-09)


### Bug Fixes

* **#2794:** sshfs compatibility ([#2893](https://github.com/nvim-tree/nvim-tree.lua/issues/2893)) ([2d6e64d](https://github.com/nvim-tree/nvim-tree.lua/commit/2d6e64dd8c45a86f312552b7a47eef2c8623a25c))
* **#2868:** windows: do not visit unenumerable directories such as Application Data ([#2874](https://github.com/nvim-tree/nvim-tree.lua/issues/2874)) ([2104786](https://github.com/nvim-tree/nvim-tree.lua/commit/210478677cb9d672c4265deb0e9b59d58b675bd4))
* **#2878:** nowrapscan prevents move from root ([#2880](https://github.com/nvim-tree/nvim-tree.lua/issues/2880)) ([4234095](https://github.com/nvim-tree/nvim-tree.lua/commit/42340952af598a08ab80579d067b6da72a9e6d29))
* **#2879:** remove unnecessary tree window width setting to prevent unnecessary :wincmd = ([#2881](https://github.com/nvim-tree/nvim-tree.lua/issues/2881)) ([d43ab67](https://github.com/nvim-tree/nvim-tree.lua/commit/d43ab67d0eb4317961c5e9d15fffe908519debe0))

## [1.6.0](https://github.com/nvim-tree/nvim-tree.lua/compare/nvim-tree-v1.5.0...nvim-tree-v1.6.0) (2024-08-10)


### Features

* **#2225:** add renderer.hidden_display to show a summary of hidden files below the tree ([#2856](https://github.com/nvim-tree/nvim-tree.lua/issues/2856)) ([e25eb7f](https://github.com/nvim-tree/nvim-tree.lua/commit/e25eb7fa83f7614bb23d762e91d2de44fcd7103b))
* **#2349:** add "right_align" option for renderer.icons.*_placement ([#2839](https://github.com/nvim-tree/nvim-tree.lua/issues/2839)) ([1d629a5](https://github.com/nvim-tree/nvim-tree.lua/commit/1d629a5d3f7d83d516494c221a2cfc079f43bc47))
* **#2349:** add "right_align" option for renderer.icons.*_placement ([#2846](https://github.com/nvim-tree/nvim-tree.lua/issues/2846)) ([48d0e82](https://github.com/nvim-tree/nvim-tree.lua/commit/48d0e82f9434691cc50d970898142a8c084a49d6))
* add renderer.highlight_hidden, renderer.icons.show.hidden and renderer.icons.hidden_placement for dotfile icons/highlights ([#2840](https://github.com/nvim-tree/nvim-tree.lua/issues/2840)) ([48a9290](https://github.com/nvim-tree/nvim-tree.lua/commit/48a92907575df1dbd7242975a04e98169cb3a115))


### Bug Fixes

* **#2859:** make sure window still exists when restoring options ([#2863](https://github.com/nvim-tree/nvim-tree.lua/issues/2863)) ([466fbed](https://github.com/nvim-tree/nvim-tree.lua/commit/466fbed3e4b61fcc23a48fe99de7bfa264a9fee8))

## [1.5.0](https://github.com/nvim-tree/nvim-tree.lua/compare/nvim-tree-v1.4.0...nvim-tree-v1.5.0) (2024-07-11)


### Features

* **#2127:** add experimental.actions.open_file.relative_path to open files with a relative path rather than absolute ([#2805](https://github.com/nvim-tree/nvim-tree.lua/issues/2805)) ([869c064](https://github.com/nvim-tree/nvim-tree.lua/commit/869c064721a6c2091f22c3541e8f0ff958361771))
* **#2598:** add api.tree.resize ([#2811](https://github.com/nvim-tree/nvim-tree.lua/issues/2811)) ([2ede0de](https://github.com/nvim-tree/nvim-tree.lua/commit/2ede0de67b47e89e2b4cb488ea3f58b8f5a8c90a))
* **#2799:** `filesystem_watchers.ignore_dirs` and `git.disable_for_dirs` may be functions ([#2800](https://github.com/nvim-tree/nvim-tree.lua/issues/2800)) ([8b2c5c6](https://github.com/nvim-tree/nvim-tree.lua/commit/8b2c5c678be4b49dff6a2df794877000113fd77b))
* **#2799:** filesystem_watchers.ignore_dirs and git.disable_for_dirs may be functions ([8b2c5c6](https://github.com/nvim-tree/nvim-tree.lua/commit/8b2c5c678be4b49dff6a2df794877000113fd77b))


### Bug Fixes

* **#2813:** macos: enable file renaming with changed capitalization ([#2814](https://github.com/nvim-tree/nvim-tree.lua/issues/2814)) ([abfd1d1](https://github.com/nvim-tree/nvim-tree.lua/commit/abfd1d1b6772540364743531cc0331e08a0027a9))
* **#2819:** experimental.actions.open_file.relative_path issue following change directory ([#2820](https://github.com/nvim-tree/nvim-tree.lua/issues/2820)) ([12a9a99](https://github.com/nvim-tree/nvim-tree.lua/commit/12a9a995a455d2c2466e47140663275365a5d2fc))

## [1.4.0](https://github.com/nvim-tree/nvim-tree.lua/compare/nvim-tree-v1.3.3...nvim-tree-v1.4.0) (2024-06-09)

### Notice

* Neovim 0.9 is now the minimum supported version; please upgrade to neovim release version 0.9 or 0.10.

### Reverts

* **#2781:** "refactor: replace deprecated use of vim.diagnostic.is_disabled()" ([#2784](https://github.com/nvim-tree/nvim-tree.lua/issues/2784)) ([517e4fb](https://github.com/nvim-tree/nvim-tree.lua/commit/517e4fbb9ef3c0986da7047f44b4b91a2400f93c))


### Miscellaneous Chores

* release 1.4.0 ([1cac800](https://github.com/nvim-tree/nvim-tree.lua/commit/1cac8005df6da484c97499247754afa59fef92db))

## [1.3.3](https://github.com/nvim-tree/nvim-tree.lua/compare/nvim-tree-v1.3.2...nvim-tree-v1.3.3) (2024-05-14)


### Bug Fixes

* nil access exception with git integration when changing branches ([#2774](https://github.com/nvim-tree/nvim-tree.lua/issues/2774)) ([340d3a9](https://github.com/nvim-tree/nvim-tree.lua/commit/340d3a9795e06bdd1814228de398cd510f9bfbb0))

## [1.3.2](https://github.com/nvim-tree/nvim-tree.lua/compare/nvim-tree-v1.3.1...nvim-tree-v1.3.2) (2024-05-12)


### Bug Fixes

* **#2758:** use nvim-webdevicons default file icon, not renderer.icons.glyphs.default, as per :help ([#2759](https://github.com/nvim-tree/nvim-tree.lua/issues/2759)) ([347e1eb](https://github.com/nvim-tree/nvim-tree.lua/commit/347e1eb35264677f66a79466bb5e3d111968e12c))
* **#2758:** use nvim-webdevicons default for default files ([347e1eb](https://github.com/nvim-tree/nvim-tree.lua/commit/347e1eb35264677f66a79466bb5e3d111968e12c))
* **#925:** handle newlines in file names ([#2754](https://github.com/nvim-tree/nvim-tree.lua/issues/2754)) ([64f61e4](https://github.com/nvim-tree/nvim-tree.lua/commit/64f61e4c913047a045ff90bd188dd3b54ee443cf))

## [1.3.1](https://github.com/nvim-tree/nvim-tree.lua/compare/nvim-tree-v1.3.0...nvim-tree-v1.3.1) (2024-04-25)


### Bug Fixes

* **#2535:** TextYankPost event sends vim.v.event ([#2734](https://github.com/nvim-tree/nvim-tree.lua/issues/2734)) ([d8d3a15](https://github.com/nvim-tree/nvim-tree.lua/commit/d8d3a1590a05b2d8b5eb26e2ed1c6052b1b47a77))
* **#2733:** escape trash path ([#2735](https://github.com/nvim-tree/nvim-tree.lua/issues/2735)) ([81eb8d5](https://github.com/nvim-tree/nvim-tree.lua/commit/81eb8d519233c105f30dc0a278607e62b20502fd))

## [1.3.0](https://github.com/nvim-tree/nvim-tree.lua/compare/nvim-tree-v1.2.0...nvim-tree-v1.3.0) (2024-03-30)


### Features

* add update_focused_file.exclude  ([#2673](https://github.com/nvim-tree/nvim-tree.lua/issues/2673)) ([e20966a](https://github.com/nvim-tree/nvim-tree.lua/commit/e20966ae558524f8d6f93dc37f5d2a8605f893e2))


### Bug Fixes

* **#2658:** change SpellCap groups to reduce confusion: ExecFile-&gt;Question, ImageFile->Question, SpecialFile->Title, Symlink->Underlined; add all other highlight groups to :NvimTreeHiTest ([#2732](https://github.com/nvim-tree/nvim-tree.lua/issues/2732)) ([0aca092](https://github.com/nvim-tree/nvim-tree.lua/commit/0aca0920f44b12a8383134bcb52da9faec123608))
* bookmark filter shows marked directory children ([#2719](https://github.com/nvim-tree/nvim-tree.lua/issues/2719)) ([2d97059](https://github.com/nvim-tree/nvim-tree.lua/commit/2d97059661c83787372c8c003e743c984ba3ac50))

## [1.2.0](https://github.com/nvim-tree/nvim-tree.lua/compare/nvim-tree-v1.1.1...nvim-tree-v1.2.0) (2024-03-24)


### Features

* add api.tree.toggle_enable_filters ([#2706](https://github.com/nvim-tree/nvim-tree.lua/issues/2706)) ([f7c09bd](https://github.com/nvim-tree/nvim-tree.lua/commit/f7c09bd72e50e1795bd3afb9e2a2b157b4bfb3c3))

## [1.1.1](https://github.com/nvim-tree/nvim-tree.lua/compare/nvim-tree-v1.1.0...nvim-tree-v1.1.1) (2024-03-15)


### Bug Fixes

* **#2395:** marks.bulk.move defaults to directory at cursor ([#2688](https://github.com/nvim-tree/nvim-tree.lua/issues/2688)) ([cfea5bd](https://github.com/nvim-tree/nvim-tree.lua/commit/cfea5bd0806aab41bef6014c6cf5a510910ddbdb))
* **#2705:** change NvimTreeWindowPicker cterm background from Cyan to more visible DarkBlue ([#2708](https://github.com/nvim-tree/nvim-tree.lua/issues/2708)) ([1fd9c98](https://github.com/nvim-tree/nvim-tree.lua/commit/1fd9c98960463d2d5d400916c0633b2df016941d))
* bookmark filter should include parent directory ([#2704](https://github.com/nvim-tree/nvim-tree.lua/issues/2704)) ([76b9810](https://github.com/nvim-tree/nvim-tree.lua/commit/76b98109f62caa12b2f1dff472060b2233ea2e90))

## [1.1.0](https://github.com/nvim-tree/nvim-tree.lua/compare/nvim-tree-v1.0.0...nvim-tree-v1.1.0) (2024-03-14)


### Features

* **#2630:** file renames can now create directories ([#2657](https://github.com/nvim-tree/nvim-tree.lua/issues/2657)) ([efafd73](https://github.com/nvim-tree/nvim-tree.lua/commit/efafd73efa9bc8c26282aed563ba0f01c7465b06))
* add api.fs.copy.basename, default mapping ge ([#2698](https://github.com/nvim-tree/nvim-tree.lua/issues/2698)) ([8f2a50f](https://github.com/nvim-tree/nvim-tree.lua/commit/8f2a50f1cd0c64003042364cf317c8788eaa6c8c))


### Bug Fixes

* **#2695:** git toplevel guard against missing paths ([#2696](https://github.com/nvim-tree/nvim-tree.lua/issues/2696)) ([3c4267e](https://github.com/nvim-tree/nvim-tree.lua/commit/3c4267eb5045fa86b67fe40c0c63d31efc801e77))
* searchcount exception on invalid search regex ([#2693](https://github.com/nvim-tree/nvim-tree.lua/issues/2693)) ([041dbd1](https://github.com/nvim-tree/nvim-tree.lua/commit/041dbd18f440207ad161503a384e7c82d575db66))

## [1.0.0](https://github.com/nvim-tree/nvim-tree.lua/compare/nvim-tree-v0.100.0...nvim-tree-v1.0.0) (2024-02-18)


### Features

* **#2654:** filters.custom may be a function ([#2655](https://github.com/nvim-tree/nvim-tree.lua/issues/2655)) ([4a87b8b](https://github.com/nvim-tree/nvim-tree.lua/commit/4a87b8b46b4a30107971871df3cb7f4c30fdd5d0))


### Miscellaneous Chores

* release 1.0.0 ([#2678](https://github.com/nvim-tree/nvim-tree.lua/issues/2678)) ([d16246a](https://github.com/nvim-tree/nvim-tree.lua/commit/d16246a7575538f77e9246520449b99333c469f7))

## [0.100.0](https://github.com/nvim-tree/nvim-tree.lua/compare/nvim-tree-v0.99.0...nvim-tree-v0.100.0) (2024-02-11)


### Features

* **#1389:** api: recursive node navigation for git and diagnostics ([#2525](https://github.com/nvim-tree/nvim-tree.lua/issues/2525)) ([5d13cc8](https://github.com/nvim-tree/nvim-tree.lua/commit/5d13cc8205bce4963866f73c50f6fdc18a515ffe))
* **#2415:** add :NvimTreeHiTest ([#2664](https://github.com/nvim-tree/nvim-tree.lua/issues/2664)) ([b278fc2](https://github.com/nvim-tree/nvim-tree.lua/commit/b278fc25ae0fc95e4808eb5618f07fc2522fd2b3))
* **#2415:** colour and highlight overhaul, see :help nvim-tree-highlight-overhaul ([#2455](https://github.com/nvim-tree/nvim-tree.lua/issues/2455)) ([e9c5abe](https://github.com/nvim-tree/nvim-tree.lua/commit/e9c5abe073a973f54d3ca10bfe30f253569f4405))
* add node.open.toggle_group_empty, default mapping L ([#2647](https://github.com/nvim-tree/nvim-tree.lua/issues/2647)) ([8cbb1db](https://github.com/nvim-tree/nvim-tree.lua/commit/8cbb1db8e90b62fc56f379992e622e9f919792ce))


### Bug Fixes

* **#2415:** disambiguate highlight groups, see :help nvim-tree-highlight-overhaul ([#2639](https://github.com/nvim-tree/nvim-tree.lua/issues/2639)) ([d9cb432](https://github.com/nvim-tree/nvim-tree.lua/commit/d9cb432d2c8d8fa9267ddbd7535d76fe4df89360))
* **#2415:** fix NvimTreeIndentMarker highlight group: FileIcon-&gt;FolderIcon ([e9ac136](https://github.com/nvim-tree/nvim-tree.lua/commit/e9ac136a3ab996aa8e4253253521dcf2cb66b81b))
* **#2415:** highlight help header and mappings ([#2669](https://github.com/nvim-tree/nvim-tree.lua/issues/2669)) ([39e6fef](https://github.com/nvim-tree/nvim-tree.lua/commit/39e6fef85ac3bb29532b877aa7c9c34911c661af))
* **#2415:** nvim 0.8 highlight overhaul support, limited to only show highest highlight precedence ([#2642](https://github.com/nvim-tree/nvim-tree.lua/issues/2642)) ([f39f7b6](https://github.com/nvim-tree/nvim-tree.lua/commit/f39f7b6fcd3865ac2146de4cb4045286308f2935))
* **#2415:** NvimTreeIndentMarker highlight group: FileIcon-&gt;FolderIcon ([#2656](https://github.com/nvim-tree/nvim-tree.lua/issues/2656)) ([e9ac136](https://github.com/nvim-tree/nvim-tree.lua/commit/e9ac136a3ab996aa8e4253253521dcf2cb66b81b))
* **#2624:** open file from docked floating window ([#2627](https://github.com/nvim-tree/nvim-tree.lua/issues/2627)) ([f24afa2](https://github.com/nvim-tree/nvim-tree.lua/commit/f24afa2cef551122b8bd53bb2e4a7df42343ce2e))
* **#2632:** occasional error stack when locating nvim-tree window ([#2633](https://github.com/nvim-tree/nvim-tree.lua/issues/2633)) ([48b1d86](https://github.com/nvim-tree/nvim-tree.lua/commit/48b1d8638fa3726236ae22e0e48a74ac8ea6592a))
* **#2637:** show buffer modified icons and highlights ([#2638](https://github.com/nvim-tree/nvim-tree.lua/issues/2638)) ([7bdb220](https://github.com/nvim-tree/nvim-tree.lua/commit/7bdb220d0fe604a77361e92cdbc7af1b8a412126))
* **#2643:** correctly apply linked highlight groups in tree window ([#2653](https://github.com/nvim-tree/nvim-tree.lua/issues/2653)) ([fbee8a6](https://github.com/nvim-tree/nvim-tree.lua/commit/fbee8a69a46f558d29ab84e96301425b0501c668))
* allow highlight overrides for DEFAULT_DEFS: NvimTreeFolderIcon, NvimTreeWindowPicker ([#2636](https://github.com/nvim-tree/nvim-tree.lua/issues/2636)) ([74525ac](https://github.com/nvim-tree/nvim-tree.lua/commit/74525ac04760bf0d9fec2bf51474d2b05f36048e))
* bad column offset when using full_name ([#2629](https://github.com/nvim-tree/nvim-tree.lua/issues/2629)) ([75ff64e](https://github.com/nvim-tree/nvim-tree.lua/commit/75ff64e6663fc3b23c72dca32b2f838acefe7c8a))
* passing nil as window handle in view.get_winnr ([48b1d86](https://github.com/nvim-tree/nvim-tree.lua/commit/48b1d8638fa3726236ae22e0e48a74ac8ea6592a))

## 0.99.0 (2024-01-01)


### Features

* **#1850:** add "no bookmark" filter ([#2571](https://github.com/nvim-tree/nvim-tree.lua/issues/2571)) ([8f92e1e](https://github.com/nvim-tree/nvim-tree.lua/commit/8f92e1edd399f839a23776dcc6eee4ba18030370))
* add kind param to vim.ui.select function calls ([#2602](https://github.com/nvim-tree/nvim-tree.lua/issues/2602)) ([dc839a7](https://github.com/nvim-tree/nvim-tree.lua/commit/dc839a72a6496ce22ebd3dd959115cf97c1b20a0))
* add option to skip gitignored files on git navigation ([#2583](https://github.com/nvim-tree/nvim-tree.lua/issues/2583)) ([50f30bc](https://github.com/nvim-tree/nvim-tree.lua/commit/50f30bcd8c62ac4a83d133d738f268279f2c2ce2))


### Bug Fixes

* **#2519:** Diagnostics Not Updated When Tree Not Visible ([#2597](https://github.com/nvim-tree/nvim-tree.lua/issues/2597)) ([96a783f](https://github.com/nvim-tree/nvim-tree.lua/commit/96a783fbd606a458bcce2ef8041240a8b94510ce))
* **#2609:** help toggle ([#2611](https://github.com/nvim-tree/nvim-tree.lua/issues/2611)) ([fac4900](https://github.com/nvim-tree/nvim-tree.lua/commit/fac4900bd18a9fa15be3d104645d9bdef7b3dcec))
* hijack_cursor on update focused file and vim search ([#2600](https://github.com/nvim-tree/nvim-tree.lua/issues/2600)) ([02ae523](https://github.com/nvim-tree/nvim-tree.lua/commit/02ae52357ba4da77a4c120390791584a81d15340))
