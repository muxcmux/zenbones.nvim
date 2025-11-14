# Changelog

## [5.0.0](https://github.com/muxcmux/zenbones.nvim/compare/v4.7.2...v5.0.0) (2025-11-14)


### ⚠ BREAKING CHANGES

* **treesitter:** support nvim-treesitter@0.9.2 ([#151](https://github.com/muxcmux/zenbones.nvim/issues/151))
* nvim-treesitter changes
* bump min nvim version to v0.6.0
* support leap (drop lightspeed) ([#94](https://github.com/muxcmux/zenbones.nvim/issues/94))
* **build:** copy cterm from gui lush option
* **build:** use color name for _compat config

### Features

* add duckbones flavor ([ecef036](https://github.com/muxcmux/zenbones.nvim/commit/ecef0367bcc1fc06d33f6aa7a193f0720828f63f))
* add lsp semantic tokens ([519fc82](https://github.com/muxcmux/zenbones.nvim/commit/519fc821565553480eb8fc49369227d21b2abea2))
* add more lsp hl group ([#121](https://github.com/muxcmux/zenbones.nvim/issues/121)) ([0cb5aff](https://github.com/muxcmux/zenbones.nvim/commit/0cb5aff21dac1cbd96bcfc476dd9da8dc3895d31))
* add randombones ([dcbaed0](https://github.com/muxcmux/zenbones.nvim/commit/dcbaed04d7191692955805d7f71fcf16ca55943e))
* **build:** copy cterm from gui lush option ([a5d8bf1](https://github.com/muxcmux/zenbones.nvim/commit/a5d8bf14ec6c96bccc6e2dcf95cc6f108d3e5bc1))
* **build:** use color name for _compat config ([111ed8f](https://github.com/muxcmux/zenbones.nvim/commit/111ed8ff6443ba5b7255c3571b4759dd5fab46bb))
* bump min nvim version to v0.6.0 ([b4761a2](https://github.com/muxcmux/zenbones.nvim/commit/b4761a288a421ae00582216ab22b0194a286a12a))
* **ci:** refactor ci auto commit ([183ca1c](https://github.com/muxcmux/zenbones.nvim/commit/183ca1ce95d0accea0bd993a8cc0151b33e5bae1))
* **ci:** sync to codeberg and gitlab ([#168](https://github.com/muxcmux/zenbones.nvim/issues/168)) ([f5f5fff](https://github.com/muxcmux/zenbones.nvim/commit/f5f5fff4e9ebb68c956a4557790a8941fbcf9c1d))
* **ci:** use stylua action ([000a1ef](https://github.com/muxcmux/zenbones.nvim/commit/000a1ef90d3b31217d309c029b145b20c0ac2b25))
* CursorLine contrast option ([b3cda0a](https://github.com/muxcmux/zenbones.nvim/commit/b3cda0abb3b5ea27447e9988e7a2a5561c42378a))
* DiagnosticOk ([#142](https://github.com/muxcmux/zenbones.nvim/issues/142)) ([c7b66be](https://github.com/muxcmux/zenbones.nvim/commit/c7b66be373d7576ad02b5ee9c847971421c6781c))
* disable italics when not supported ([4af87ff](https://github.com/muxcmux/zenbones.nvim/commit/4af87ff7ba0643435f98d21ba4c1d51a4c7565d3))
* **extras:** remove excludes ([7009ede](https://github.com/muxcmux/zenbones.nvim/commit/7009ede80daaabeaa5dbd3c9567252c7a243c221))
* **foot:** Support foot terminal ([cbfa9e6](https://github.com/muxcmux/zenbones.nvim/commit/cbfa9e6bbe6fc5a326c0dac58444976dc0b229ac))
* generate Alacritty files in toml instead of yaml ([#158](https://github.com/muxcmux/zenbones.nvim/issues/158)) ([7abac65](https://github.com/muxcmux/zenbones.nvim/commit/7abac65da3a19767314e6bc42e98631a45f178a4))
* **hl:** add `CocSearch` ([#84](https://github.com/muxcmux/zenbones.nvim/issues/84)) ([46aaa50](https://github.com/muxcmux/zenbones.nvim/commit/46aaa50e01706561f0817c22c5955535cfafd3fb))
* **hl:** Add `CurSearch` ([#83](https://github.com/muxcmux/zenbones.nvim/issues/83)) ([e4def19](https://github.com/muxcmux/zenbones.nvim/commit/e4def19944485787f5172bb952f8d46755999688))
* **main:** noice support ([729110b](https://github.com/muxcmux/zenbones.nvim/commit/729110be6e0b6f74d1c9a4d14322f3a79206e397))
* **main:** support nvim-notify ([#132](https://github.com/muxcmux/zenbones.nvim/issues/132)) ([dd4ad12](https://github.com/muxcmux/zenbones.nvim/commit/dd4ad1273defc46695ea3997f030661e4a893eb1))
* more fzf-lua support ([f860d70](https://github.com/muxcmux/zenbones.nvim/commit/f860d70d57f51134a9b7a54d8b39d8385744bcb1))
* nvim-treesitter changes ([bfb2e0d](https://github.com/muxcmux/zenbones.nvim/commit/bfb2e0d43a92bf36760270810e0cacde37126ca2))
* render markdown codeblock bg ([#199](https://github.com/muxcmux/zenbones.nvim/issues/199)) ([f82c02d](https://github.com/muxcmux/zenbones.nvim/commit/f82c02d773b952f2cf0edd443665e4be0873e17d))
* support blink.cmp ([a92d8fa](https://github.com/muxcmux/zenbones.nvim/commit/a92d8fad347969490af0a95d6722b7f22344fef7))
* support fzf-lua ([#178](https://github.com/muxcmux/zenbones.nvim/issues/178)) ([a509e6c](https://github.com/muxcmux/zenbones.nvim/commit/a509e6c590a07a195cc1cb77a0afe82217a2705d))
* support leap (drop lightspeed) ([#94](https://github.com/muxcmux/zenbones.nvim/issues/94)) ([d8a93c2](https://github.com/muxcmux/zenbones.nvim/commit/d8a93c2566fbf9a1c5557a6b8059ea3acc9b3737))
* support mason.nvim ([30d9598](https://github.com/muxcmux/zenbones.nvim/commit/30d9598356588bde64c4a29eb56aa241a246108c))
* support nvim 0.10 ([#176](https://github.com/muxcmux/zenbones.nvim/issues/176)) ([8877bb1](https://github.com/muxcmux/zenbones.nvim/commit/8877bb1dfc50467888ebe16aaf424e36492807c9))
* support randombones palette, lightline and lualine ([15d724c](https://github.com/muxcmux/zenbones.nvim/commit/15d724c7387d01515fd96dad182ef2226a928dc5))
* support snacks indent ([21f2a3a](https://github.com/muxcmux/zenbones.nvim/commit/21f2a3aaf9ae0d9499ab1c47fdbb50f8fc9e6737))
* support Snacks.picker ([#209](https://github.com/muxcmux/zenbones.nvim/issues/209)) ([8e6b18c](https://github.com/muxcmux/zenbones.nvim/commit/8e6b18c3032378f61d0d1efdf191301804a3da1c))
* transparent background option ([cd109e0](https://github.com/muxcmux/zenbones.nvim/commit/cd109e0cf79604d9b19379a82e1d08c865b0e239))
* **treesitter:** support nvim-treesitter@0.9.2 ([#151](https://github.com/muxcmux/zenbones.nvim/issues/151)) ([eed5f2d](https://github.com/muxcmux/zenbones.nvim/commit/eed5f2d3e3912994d8c16d4d56f73ca8d7b7f6d9))
* upgrade panvimdoc ([60278f0](https://github.com/muxcmux/zenbones.nvim/commit/60278f060cd0163d5b9152ed54c3895cef4054f7))
* **windows terminal:** supported ([#68](https://github.com/muxcmux/zenbones.nvim/issues/68)) ([0bf9c5a](https://github.com/muxcmux/zenbones.nvim/commit/0bf9c5a489ccb7a41f80447f2c82bec8bb095da4))


### Bug Fixes

* add IblScope ([#140](https://github.com/muxcmux/zenbones.nvim/issues/140)) ([a2f1b4c](https://github.com/muxcmux/zenbones.nvim/commit/a2f1b4c6a28c2b4a4bc3bb1b0121c505b4974ee9))
* add lazy.nvim instructions ([6c01e4c](https://github.com/muxcmux/zenbones.nvim/commit/6c01e4cd3a4e8ae4321069bfb814cac1e2b2a07e))
* add missing fzf-lua hl ([#179](https://github.com/muxcmux/zenbones.nvim/issues/179)) ([f74fc32](https://github.com/muxcmux/zenbones.nvim/commit/f74fc327273d627ef305f85faf72c3fd9c049c3f))
* adjust requirements ([b44f104](https://github.com/muxcmux/zenbones.nvim/commit/b44f1043bfa59a31e9cc5a76bd6f8d92384da2f7))
* adjust WhichKeySeparator ([12b7478](https://github.com/muxcmux/zenbones.nvim/commit/12b7478c8fe25487d14949e2723f586469bf99a9))
* **build:** remove neovim only plugins in compat ([10b299a](https://github.com/muxcmux/zenbones.nvim/commit/10b299a7bd5d8dc9ff28561fa8d8a69277d35721))
* ci error ([c997d8d](https://github.com/muxcmux/zenbones.nvim/commit/c997d8d53778c560949fcbdd1aed626c4ec6b180))
* ci selene-action version ([a37860d](https://github.com/muxcmux/zenbones.nvim/commit/a37860d3ccad281f96c4eb053d6ecec2eca81cc5))
* **ci:** add tagging step back ([#189](https://github.com/muxcmux/zenbones.nvim/issues/189)) ([1acd87e](https://github.com/muxcmux/zenbones.nvim/commit/1acd87ea10ce26b1613167b7e060ff7110f20686))
* **ci:** create build dir ([0b9ed8e](https://github.com/muxcmux/zenbones.nvim/commit/0b9ed8e831578fd3c3512529188093cfedd06dce))
* **ci:** double run ([8ba2227](https://github.com/muxcmux/zenbones.nvim/commit/8ba222734f67b19615b9a94d41a79253dec4012f))
* **ci:** fix release step ([#185](https://github.com/muxcmux/zenbones.nvim/issues/185)) ([b42f399](https://github.com/muxcmux/zenbones.nvim/commit/b42f3994a9079c192eba674dd8fb8acbacca80d8))
* **ci:** proper permissions ([#187](https://github.com/muxcmux/zenbones.nvim/issues/187)) ([26e26dc](https://github.com/muxcmux/zenbones.nvim/commit/26e26dc704f0ce037fca4b96742f2224292fbe07))
* **ci:** remove deprecated release ([#186](https://github.com/muxcmux/zenbones.nvim/issues/186)) ([65d324d](https://github.com/muxcmux/zenbones.nvim/commit/65d324d2d703296b8c9872063a8733ce34d69fd4))
* **ci:** remove extra steps ([ada98d3](https://github.com/muxcmux/zenbones.nvim/commit/ada98d316d384357c006e8b8014400ad04d93e40))
* **ci:** stage changed colors ([1529ba3](https://github.com/muxcmux/zenbones.nvim/commit/1529ba34121b322ff23ea2d6ea597c1a31fdca38))
* **ci:** stylua ([b7031b3](https://github.com/muxcmux/zenbones.nvim/commit/b7031b38fbb3f76b6dd7dd7e5b5a24f6e7ddc6a7))
* **ci:** stylua pin version ([6455bdf](https://github.com/muxcmux/zenbones.nvim/commit/6455bdfa0ef8d8ef1dd6412608f82aa04b629d9c))
* **ci:** sync remote gitlab ([cdb980d](https://github.com/muxcmux/zenbones.nvim/commit/cdb980d8144ea789fa73b47b05b9d180af9ff5b1))
* **ci:** turn off sync for pr ([#177](https://github.com/muxcmux/zenbones.nvim/issues/177)) ([a983937](https://github.com/muxcmux/zenbones.nvim/commit/a9839370202c62527f37f695e18df5a0576bf08e))
* **ci:** update ([#188](https://github.com/muxcmux/zenbones.nvim/issues/188)) ([9cf9de9](https://github.com/muxcmux/zenbones.nvim/commit/9cf9de96db145854927ac4621772b7161d38935c))
* **ci:** update actions versions ([90fa472](https://github.com/muxcmux/zenbones.nvim/commit/90fa472caf8d47d1ca1a22f68402a7da7d2a4493))
* **ci:** update auto commit ([#184](https://github.com/muxcmux/zenbones.nvim/issues/184)) ([ce694ef](https://github.com/muxcmux/zenbones.nvim/commit/ce694ef8e222e4682ebd9c7de62cf2747efccea0))
* **coc.nvim:** add highlight for MenuSel ([#91](https://github.com/muxcmux/zenbones.nvim/issues/91)) ([e2ac055](https://github.com/muxcmux/zenbones.nvim/commit/e2ac0557a3df217e5d82b7e580af75c244602a33))
* **coc:** CocWarningVirtualText typo ([52b8939](https://github.com/muxcmux/zenbones.nvim/commit/52b893945e1a83bc8c2068e7968a5c648a587bfc))
* consistent vim option setting ([0e9e489](https://github.com/muxcmux/zenbones.nvim/commit/0e9e48946b765e7b163da4bcd5d7aac2e14f9499))
* correct bug and clarify lazy.nvim install ([#202](https://github.com/muxcmux/zenbones.nvim/issues/202)) ([88960c8](https://github.com/muxcmux/zenbones.nvim/commit/88960c8aa3ad8aff0bcccdce7cd23629c7a3c510))
* define WinSeparator first ([8fb981e](https://github.com/muxcmux/zenbones.nvim/commit/8fb981e8fea1eab821df988728e10d341dd07b8f))
* diagnostic sign different bg ([772640b](https://github.com/muxcmux/zenbones.nvim/commit/772640b9104206d643d271e57c6186a190176187))
* **doc:** bug in example code ([#148](https://github.com/muxcmux/zenbones.nvim/issues/148)) ([3d2447e](https://github.com/muxcmux/zenbones.nvim/commit/3d2447e48a12a6af130669ad03f12441921a8b5e))
* **docs:** add git mirror links ([#170](https://github.com/muxcmux/zenbones.nvim/issues/170)) ([453ec69](https://github.com/muxcmux/zenbones.nvim/commit/453ec69d82d644ee6998a3464da49d0261df9f80))
* **doc:** update install ([e9ba830](https://github.com/muxcmux/zenbones.nvim/commit/e9ba8305f65524f9355515cdd8704b2c6ba2def6))
* FlashBackdrop ([b46b222](https://github.com/muxcmux/zenbones.nvim/commit/b46b2227c41ae0d4da594ac5f52dbff63f140beb))
* fzf match ([b6a0f6f](https://github.com/muxcmux/zenbones.nvim/commit/b6a0f6f41b660c9b183d60bfbc4b93908dc6c75a))
* improve diff ([07d790f](https://github.com/muxcmux/zenbones.nvim/commit/07d790faa3fe0206149c75a12629cac9db3e797b))
* improve diff ([168593f](https://github.com/muxcmux/zenbones.nvim/commit/168593f4ad8dc79fce52b88b5cf90447536d0a81))
* improve help highlighting ([#160](https://github.com/muxcmux/zenbones.nvim/issues/160)) ([3df286b](https://github.com/muxcmux/zenbones.nvim/commit/3df286bc8439ad7b4a6d6ec2f3944b0e30763191))
* Leap highlight are out of date ([#195](https://github.com/muxcmux/zenbones.nvim/issues/195)) ([b433225](https://github.com/muxcmux/zenbones.nvim/commit/b433225e29de5955a70b3e25a762cfaf2cf24a3d))
* **lint:** allow mixed table ([#150](https://github.com/muxcmux/zenbones.nvim/issues/150)) ([22cfe4b](https://github.com/muxcmux/zenbones.nvim/commit/22cfe4b28e8bb5173624f69ac6bb2803d8653a12))
* lsp inlay hint ([#180](https://github.com/muxcmux/zenbones.nvim/issues/180)) ([0554b55](https://github.com/muxcmux/zenbones.nvim/commit/0554b55153eaea443402e282e0064eeb7a0f75a7))
* LspDiagnostics linking ([586cbf7](https://github.com/muxcmux/zenbones.nvim/commit/586cbf73b9dd0bc12e7c4f4c04003bc5ef73695e))
* **main:** support flash.nvim ([f8fe7b1](https://github.com/muxcmux/zenbones.nvim/commit/f8fe7b163c3c898a1de465112b3965dca7689000))
* markup italic typo ([#153](https://github.com/muxcmux/zenbones.nvim/issues/153)) ([90a56c9](https://github.com/muxcmux/zenbones.nvim/commit/90a56c97459c8511003778a25633f121bf3fc976))
* **nordbones:** Identifer typo ([da9c6c3](https://github.com/muxcmux/zenbones.nvim/commit/da9c6c3404479926b799753ff693e002385067c1))
* **runners:** ignore undefined globals ([5c87010](https://github.com/muxcmux/zenbones.nvim/commit/5c8701019bb120da24085c50abe84fde75281952))
* sign hl groups base on SignColumn ([03820bf](https://github.com/muxcmux/zenbones.nvim/commit/03820bf1ae3e43f31fb7bd04070a168c31478275))
* sort italic override specs ([6eea2a9](https://github.com/muxcmux/zenbones.nvim/commit/6eea2a95c60b02d7a25ba292aba9b0c579656a7b))
* **specs:** sync light and dark ([c4e1845](https://github.com/muxcmux/zenbones.nvim/commit/c4e1845cdc9be2c1b2ba02c78ee0438e576898cf))
* **specs:** use Constant instead of Number ([#192](https://github.com/muxcmux/zenbones.nvim/issues/192)) ([a041a4e](https://github.com/muxcmux/zenbones.nvim/commit/a041a4e7a10b8f185f3eaf18e35e60cb0d3ca6a2))
* support indent-blankline v3 ([#136](https://github.com/muxcmux/zenbones.nvim/issues/136)) ([01ac6cb](https://github.com/muxcmux/zenbones.nvim/commit/01ac6cbb1af9f5f49465e7478d5ab7fa1900abd2))
* transparent Folded ([e608ef1](https://github.com/muxcmux/zenbones.nvim/commit/e608ef16b1a636e653a471f36c869193ed4b5e9d)), closes [#92](https://github.com/muxcmux/zenbones.nvim/issues/92)
* **ts:** use delimiter for [@constructor](https://github.com/constructor).lua ([8e63b5e](https://github.com/muxcmux/zenbones.nvim/commit/8e63b5e56f27d4d5275b45401e3a50334e94334a))
* **ts:** use delimiter for [@constructor](https://github.com/constructor).lua ([1ac520f](https://github.com/muxcmux/zenbones.nvim/commit/1ac520f7fc8b1c41d1414270ee48c8f8be2714b0))
* unmatched parenthesis ([#106](https://github.com/muxcmux/zenbones.nvim/issues/106)) ([910b8c2](https://github.com/muxcmux/zenbones.nvim/commit/910b8c240c6aaf5263db038db81c538602c766c3))
* use blossom for snack match ([68edbb8](https://github.com/muxcmux/zenbones.nvim/commit/68edbb8716132b3e3283817ae91899036ff02bc8))

## [4.7.2](https://github.com/zenbones-theme/zenbones.nvim/compare/v4.7.1...v4.7.2) (2025-04-21)


### Bug Fixes

* fzf match ([b6a0f6f](https://github.com/zenbones-theme/zenbones.nvim/commit/b6a0f6f41b660c9b183d60bfbc4b93908dc6c75a))

## [4.7.1](https://github.com/zenbones-theme/zenbones.nvim/compare/v4.7.0...v4.7.1) (2025-04-15)


### Bug Fixes

* use blossom for snack match ([68edbb8](https://github.com/zenbones-theme/zenbones.nvim/commit/68edbb8716132b3e3283817ae91899036ff02bc8))

## [4.7.0](https://github.com/zenbones-theme/zenbones.nvim/compare/v4.6.0...v4.7.0) (2025-03-04)


### Features

* support Snacks.picker ([#209](https://github.com/zenbones-theme/zenbones.nvim/issues/209)) ([8e6b18c](https://github.com/zenbones-theme/zenbones.nvim/commit/8e6b18c3032378f61d0d1efdf191301804a3da1c))


### Bug Fixes

* **ci:** sync remote gitlab ([cdb980d](https://github.com/zenbones-theme/zenbones.nvim/commit/cdb980d8144ea789fa73b47b05b9d180af9ff5b1))

## [4.6.0](https://github.com/zenbones-theme/zenbones.nvim/compare/v4.5.0...v4.6.0) (2025-02-16)


### Features

* support blink.cmp ([a92d8fa](https://github.com/zenbones-theme/zenbones.nvim/commit/a92d8fad347969490af0a95d6722b7f22344fef7))

## [4.5.0](https://github.com/zenbones-theme/zenbones.nvim/compare/v4.4.0...v4.5.0) (2025-01-09)


### Features

* more fzf-lua support ([f860d70](https://github.com/zenbones-theme/zenbones.nvim/commit/f860d70d57f51134a9b7a54d8b39d8385744bcb1))

## [4.4.0](https://github.com/zenbones-theme/zenbones.nvim/compare/v4.3.5...v4.4.0) (2024-10-03)


### Features

* render markdown codeblock bg ([#199](https://github.com/zenbones-theme/zenbones.nvim/issues/199)) ([f82c02d](https://github.com/zenbones-theme/zenbones.nvim/commit/f82c02d773b952f2cf0edd443665e4be0873e17d))


### Bug Fixes

* correct bug and clarify lazy.nvim install ([#202](https://github.com/zenbones-theme/zenbones.nvim/issues/202)) ([88960c8](https://github.com/zenbones-theme/zenbones.nvim/commit/88960c8aa3ad8aff0bcccdce7cd23629c7a3c510))

## [4.3.5](https://github.com/zenbones-theme/zenbones.nvim/compare/v4.3.4...v4.3.5) (2024-08-24)


### Bug Fixes

* add lazy.nvim instructions ([6c01e4c](https://github.com/zenbones-theme/zenbones.nvim/commit/6c01e4cd3a4e8ae4321069bfb814cac1e2b2a07e))
* improve diff ([168593f](https://github.com/zenbones-theme/zenbones.nvim/commit/168593f4ad8dc79fce52b88b5cf90447536d0a81))

## [4.3.4](https://github.com/zenbones-theme/zenbones.nvim/compare/v4.3.3...v4.3.4) (2024-08-23)


### Bug Fixes

* Leap highlight are out of date ([#195](https://github.com/zenbones-theme/zenbones.nvim/issues/195)) ([b433225](https://github.com/zenbones-theme/zenbones.nvim/commit/b433225e29de5955a70b3e25a762cfaf2cf24a3d))

## [4.3.3](https://github.com/zenbones-theme/zenbones.nvim/compare/v4.3.2...v4.3.3) (2024-08-08)


### Bug Fixes

* **specs:** use Constant instead of Number ([#192](https://github.com/zenbones-theme/zenbones.nvim/issues/192)) ([a041a4e](https://github.com/zenbones-theme/zenbones.nvim/commit/a041a4e7a10b8f185f3eaf18e35e60cb0d3ca6a2))

## [4.3.2](https://github.com/zenbones-theme/zenbones.nvim/compare/v4.3.1...v4.3.2) (2024-08-08)


### Bug Fixes

* **ci:** add tagging step back ([#189](https://github.com/zenbones-theme/zenbones.nvim/issues/189)) ([1acd87e](https://github.com/zenbones-theme/zenbones.nvim/commit/1acd87ea10ce26b1613167b7e060ff7110f20686))
* **ci:** fix release step ([#185](https://github.com/zenbones-theme/zenbones.nvim/issues/185)) ([b42f399](https://github.com/zenbones-theme/zenbones.nvim/commit/b42f3994a9079c192eba674dd8fb8acbacca80d8))
* **ci:** proper permissions ([#187](https://github.com/zenbones-theme/zenbones.nvim/issues/187)) ([26e26dc](https://github.com/zenbones-theme/zenbones.nvim/commit/26e26dc704f0ce037fca4b96742f2224292fbe07))
* **ci:** remove deprecated release ([#186](https://github.com/zenbones-theme/zenbones.nvim/issues/186)) ([65d324d](https://github.com/zenbones-theme/zenbones.nvim/commit/65d324d2d703296b8c9872063a8733ce34d69fd4))
* **ci:** update ([#188](https://github.com/zenbones-theme/zenbones.nvim/issues/188)) ([9cf9de9](https://github.com/zenbones-theme/zenbones.nvim/commit/9cf9de96db145854927ac4621772b7161d38935c))
* **ci:** update auto commit ([#184](https://github.com/zenbones-theme/zenbones.nvim/issues/184)) ([ce694ef](https://github.com/zenbones-theme/zenbones.nvim/commit/ce694ef8e222e4682ebd9c7de62cf2747efccea0))
* **doc:** update install ([e9ba830](https://github.com/zenbones-theme/zenbones.nvim/commit/e9ba8305f65524f9355515cdd8704b2c6ba2def6))
* **specs:** sync light and dark ([c4e1845](https://github.com/zenbones-theme/zenbones.nvim/commit/c4e1845cdc9be2c1b2ba02c78ee0438e576898cf))
* **ts:** use delimiter for [@constructor](https://github.com/constructor).lua ([1ac520f](https://github.com/zenbones-theme/zenbones.nvim/commit/1ac520f7fc8b1c41d1414270ee48c8f8be2714b0))

## [4.3.1](https://github.com/mcchrish/zenbones.nvim/compare/v4.3.0...v4.3.1) (2024-05-20)


### Bug Fixes

* lsp inlay hint ([#180](https://github.com/mcchrish/zenbones.nvim/issues/180)) ([0554b55](https://github.com/mcchrish/zenbones.nvim/commit/0554b55153eaea443402e282e0064eeb7a0f75a7))

## [4.3.0](https://github.com/mcchrish/zenbones.nvim/compare/v4.2.0...v4.3.0) (2024-05-19)


### Features

* **ci:** sync to codeberg and gitlab ([#168](https://github.com/mcchrish/zenbones.nvim/issues/168)) ([f5f5fff](https://github.com/mcchrish/zenbones.nvim/commit/f5f5fff4e9ebb68c956a4557790a8941fbcf9c1d))
* support fzf-lua ([#178](https://github.com/mcchrish/zenbones.nvim/issues/178)) ([a509e6c](https://github.com/mcchrish/zenbones.nvim/commit/a509e6c590a07a195cc1cb77a0afe82217a2705d))
* support nvim 0.10 ([#176](https://github.com/mcchrish/zenbones.nvim/issues/176)) ([8877bb1](https://github.com/mcchrish/zenbones.nvim/commit/8877bb1dfc50467888ebe16aaf424e36492807c9))


### Bug Fixes

* add missing fzf-lua hl ([#179](https://github.com/mcchrish/zenbones.nvim/issues/179)) ([f74fc32](https://github.com/mcchrish/zenbones.nvim/commit/f74fc327273d627ef305f85faf72c3fd9c049c3f))
* **ci:** turn off sync for pr ([#177](https://github.com/mcchrish/zenbones.nvim/issues/177)) ([a983937](https://github.com/mcchrish/zenbones.nvim/commit/a9839370202c62527f37f695e18df5a0576bf08e))
* **docs:** add git mirror links ([#170](https://github.com/mcchrish/zenbones.nvim/issues/170)) ([453ec69](https://github.com/mcchrish/zenbones.nvim/commit/453ec69d82d644ee6998a3464da49d0261df9f80))

## [4.2.0](https://github.com/mcchrish/zenbones.nvim/compare/v4.1.1...v4.2.0) (2024-03-24)


### Features

* **extras:** remove excludes ([7009ede](https://github.com/mcchrish/zenbones.nvim/commit/7009ede80daaabeaa5dbd3c9567252c7a243c221))


### Bug Fixes

* define WinSeparator first ([8fb981e](https://github.com/mcchrish/zenbones.nvim/commit/8fb981e8fea1eab821df988728e10d341dd07b8f))

## [4.1.1](https://github.com/mcchrish/zenbones.nvim/compare/v4.1.0...v4.1.1) (2024-02-10)


### Bug Fixes

* improve help highlighting ([#160](https://github.com/mcchrish/zenbones.nvim/issues/160)) ([3df286b](https://github.com/mcchrish/zenbones.nvim/commit/3df286bc8439ad7b4a6d6ec2f3944b0e30763191))

## [4.1.0](https://github.com/mcchrish/zenbones.nvim/compare/v4.0.2...v4.1.0) (2024-02-08)


### Features

* generate Alacritty files in toml instead of yaml ([#158](https://github.com/mcchrish/zenbones.nvim/issues/158)) ([7abac65](https://github.com/mcchrish/zenbones.nvim/commit/7abac65da3a19767314e6bc42e98631a45f178a4))

## [4.0.2](https://github.com/mcchrish/zenbones.nvim/compare/v4.0.1...v4.0.2) (2024-02-04)


### Bug Fixes

* **coc:** CocWarningVirtualText typo ([52b8939](https://github.com/mcchrish/zenbones.nvim/commit/52b893945e1a83bc8c2068e7968a5c648a587bfc))
* **nordbones:** Identifer typo ([da9c6c3](https://github.com/mcchrish/zenbones.nvim/commit/da9c6c3404479926b799753ff693e002385067c1))

## [4.0.1](https://github.com/mcchrish/zenbones.nvim/compare/v4.0.0...v4.0.1) (2024-02-03)


### Bug Fixes

* markup italic typo ([#153](https://github.com/mcchrish/zenbones.nvim/issues/153)) ([90a56c9](https://github.com/mcchrish/zenbones.nvim/commit/90a56c97459c8511003778a25633f121bf3fc976))

## [4.0.0](https://github.com/mcchrish/zenbones.nvim/compare/v3.5.0...v4.0.0) (2024-01-20)


### ⚠ BREAKING CHANGES

* **treesitter:** support nvim-treesitter@0.9.2 ([#151](https://github.com/mcchrish/zenbones.nvim/issues/151))

### Features

* **treesitter:** support nvim-treesitter@0.9.2 ([#151](https://github.com/mcchrish/zenbones.nvim/issues/151)) ([eed5f2d](https://github.com/mcchrish/zenbones.nvim/commit/eed5f2d3e3912994d8c16d4d56f73ca8d7b7f6d9))


### Bug Fixes

* **doc:** bug in example code ([#148](https://github.com/mcchrish/zenbones.nvim/issues/148)) ([3d2447e](https://github.com/mcchrish/zenbones.nvim/commit/3d2447e48a12a6af130669ad03f12441921a8b5e))
* **lint:** allow mixed table ([#150](https://github.com/mcchrish/zenbones.nvim/issues/150)) ([22cfe4b](https://github.com/mcchrish/zenbones.nvim/commit/22cfe4b28e8bb5173624f69ac6bb2803d8653a12))

## [3.5.0](https://github.com/mcchrish/zenbones.nvim/compare/v3.4.2...v3.5.0) (2023-10-30)


### Features

* DiagnosticOk ([#142](https://github.com/mcchrish/zenbones.nvim/issues/142)) ([c7b66be](https://github.com/mcchrish/zenbones.nvim/commit/c7b66be373d7576ad02b5ee9c847971421c6781c))

## [3.4.2](https://github.com/mcchrish/zenbones.nvim/compare/v3.4.1...v3.4.2) (2023-10-30)


### Bug Fixes

* add IblScope ([#140](https://github.com/mcchrish/zenbones.nvim/issues/140)) ([a2f1b4c](https://github.com/mcchrish/zenbones.nvim/commit/a2f1b4c6a28c2b4a4bc3bb1b0121c505b4974ee9))

## [3.4.1](https://github.com/mcchrish/zenbones.nvim/compare/v3.4.0...v3.4.1) (2023-10-02)


### Bug Fixes

* support indent-blankline v3 ([#136](https://github.com/mcchrish/zenbones.nvim/issues/136)) ([01ac6cb](https://github.com/mcchrish/zenbones.nvim/commit/01ac6cbb1af9f5f49465e7478d5ab7fa1900abd2))

## [3.4.0](https://github.com/mcchrish/zenbones.nvim/compare/v3.3.3...v3.4.0) (2023-08-30)


### Features

* **main:** support nvim-notify ([#132](https://github.com/mcchrish/zenbones.nvim/issues/132)) ([dd4ad12](https://github.com/mcchrish/zenbones.nvim/commit/dd4ad1273defc46695ea3997f030661e4a893eb1))

## [3.3.3](https://github.com/mcchrish/zenbones.nvim/compare/v3.3.2...v3.3.3) (2023-07-02)


### Bug Fixes

* FlashBackdrop ([b46b222](https://github.com/mcchrish/zenbones.nvim/commit/b46b2227c41ae0d4da594ac5f52dbff63f140beb))

## [3.3.2](https://github.com/mcchrish/zenbones.nvim/compare/v3.3.1...v3.3.2) (2023-07-02)


### Bug Fixes

* **main:** support flash.nvim ([f8fe7b1](https://github.com/mcchrish/zenbones.nvim/commit/f8fe7b163c3c898a1de465112b3965dca7689000))

## [3.3.1](https://github.com/mcchrish/zenbones.nvim/compare/v3.3.0...v3.3.1) (2023-06-27)


### Bug Fixes

* **build:** remove neovim only plugins in compat ([10b299a](https://github.com/mcchrish/zenbones.nvim/commit/10b299a7bd5d8dc9ff28561fa8d8a69277d35721))

## [3.3.0](https://github.com/mcchrish/zenbones.nvim/compare/v3.2.0...v3.3.0) (2023-06-26)


### Features

* **main:** noice support ([729110b](https://github.com/mcchrish/zenbones.nvim/commit/729110be6e0b6f74d1c9a4d14322f3a79206e397))

## [3.2.0](https://github.com/mcchrish/zenbones.nvim/compare/v3.1.0...v3.2.0) (2023-06-09)


### Features

* add more lsp hl group ([#121](https://github.com/mcchrish/zenbones.nvim/issues/121)) ([0cb5aff](https://github.com/mcchrish/zenbones.nvim/commit/0cb5aff21dac1cbd96bcfc476dd9da8dc3895d31))

## [3.1.0](https://github.com/mcchrish/zenbones.nvim/compare/v3.0.0...v3.1.0) (2023-04-09)


### Features

* add lsp semantic tokens ([519fc82](https://github.com/mcchrish/zenbones.nvim/commit/519fc821565553480eb8fc49369227d21b2abea2))
* **ci:** refactor ci auto commit ([183ca1c](https://github.com/mcchrish/zenbones.nvim/commit/183ca1ce95d0accea0bd993a8cc0151b33e5bae1))
* upgrade panvimdoc ([60278f0](https://github.com/mcchrish/zenbones.nvim/commit/60278f060cd0163d5b9152ed54c3895cef4054f7))


### Bug Fixes

* adjust requirements ([b44f104](https://github.com/mcchrish/zenbones.nvim/commit/b44f1043bfa59a31e9cc5a76bd6f8d92384da2f7))
* adjust WhichKeySeparator ([12b7478](https://github.com/mcchrish/zenbones.nvim/commit/12b7478c8fe25487d14949e2723f586469bf99a9))
* **ci:** remove extra steps ([ada98d3](https://github.com/mcchrish/zenbones.nvim/commit/ada98d316d384357c006e8b8014400ad04d93e40))
* unmatched parenthesis ([#106](https://github.com/mcchrish/zenbones.nvim/issues/106)) ([910b8c2](https://github.com/mcchrish/zenbones.nvim/commit/910b8c240c6aaf5263db038db81c538602c766c3))
