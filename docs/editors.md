---
id: editors
title: Editor Integration
---

To get the most out of Prettier, it’s recommended to run it from your editor.

If your editor does not support Prettier, you can instead [run Prettier with a file watcher](watching-files.md).

**Note!** It’s important to [install](install.md) Prettier locally in every project, so each project gets the correct Prettier version.

## Visual Studio Code

`prettier-vscode` can be installed using the extension sidebar – it’s called “Prettier - Code formatter.” [Check its repository for configuration and shortcuts](https://github.com/prettier/prettier-vscode).

If you’d like to toggle the formatter on and off, install [`vscode-status-bar-format-toggle`](https://marketplace.visualstudio.com/items?itemName=tombonnike.vscode-status-bar-format-toggle).

## Emacs

Check out the [prettier-emacs](https://github.com/prettier/prettier-emacs) repo, or [prettier.el](https://github.com/jscheid/prettier.el). The package [Apheleia](https://github.com/raxod502/apheleia) supports multiple code formatters, including Prettier.

## Vim

[vim-prettier](https://github.com/prettier/vim-prettier) is a Prettier-specific Vim plugin. [Neoformat](https://github.com/sbdchd/neoformat), [ALE](https://github.com/w0rp/ale), and [coc-prettier](https://github.com/neoclide/coc-prettier) are multi-language Vim linter/formatter plugins that support Prettier.

For more details see [the Vim setup guide](vim.md).

## Helix

A formatter can be specified in your [Helix language configuration](https://docs.helix-editor.com/languages.html#language-configuration), which will take precedence over any language servers.

For more details see the [Helix external binary formatter configuration for Prettier](https://github.com/helix-editor/helix/wiki/External-formatter-configuration#prettier).

## Sublime Text

Sublime Text support is available through Package Control and the [JsPrettier](https://packagecontrol.io/packages/JsPrettier) plug-in.

## JetBrains WebStorm, PHPStorm, PyCharm...

See the [WebStorm setup guide](webstorm.md).

## Visual Studio

Install the [JavaScript Prettier extension](https://github.com/madskristensen/JavaScriptPrettier).

## Espresso

Espresso users can install the [espresso-prettier](https://github.com/eablokker/espresso-prettier) plugin.
