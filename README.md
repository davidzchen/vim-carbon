# Carbon Syntax Highlighting for Vim & Neovim

Extracted from `carbon-language/carbon-lang/utils/vim`: https://github.com/carbon-language/carbon-lang/tree/52f80c25ab79773260b618e12774d57fa661ecb4/utils/vim

<!--
Part of the Carbon Language project, under the Apache License v2.0 with LLVM
Exceptions. See /LICENSE for license information.
SPDX-License-Identifier: Apache-2.0 WITH LLVM-exception
-->

For Carbon devs using Vim or Neovim, this plugin provides syntax highlighting
for .carbon files found throughout `explorer/testdata`

## Manual Installation

### Vim Users

From the current directory `utils/vim`, please run the following commands to
install the syntax file.

```
mkdir -p ~/.vim/syntax && cp syntax/carbon.vim ~/.vim/syntax/
mkdir -p ~/.vim/ftdetect && cp ftdetect/carbon.vim ~/.vim/ftdetect/
```

### Neovim Users

Instead of copying to the `~/.vim` directory, please use the `~/.config/nvim`
directory, or your custom Neovim root directory.

```
mkdir -p ~/.config/nvim/syntax && cp syntax/carbon.vim ~/.config/nvim/syntax/
mkdir -p ~/.config/nvim/ftdetect && cp ftdetect/carbon.vim ~/.config/nvim/ftdetect/
```
