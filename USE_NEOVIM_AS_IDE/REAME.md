# NEOVIM IS NOT JUST AN EDITOR
My thoughts to use neovim as an fully IDE.

## Outline

## Overview
Vim is improved version of Vi with more features.
Vim is a command line text editor available on Linux, MacOs and Windows. Vim is the most popular editor on the world.

![Compare Vi and Vim](./assets/vi_n_vim.avif)


What is the Outstanding points of Vim compared to other similar tools:

1. Vim is lightweight and can run on many environment. (on different kind of machines: Server, Local Machine or different kind of operating systems Linux Macos Windows)

2. The strongest mindset of Neovim is all needed keyboards on the Alpha area (with `h`, `j`, `k` and `l` for movement).
It avoid moving from alpha area to arrow are on the keyboard and from the keyboard to the mouse.

3. When you are familiar with Neovim movement, you can use tools inspired by vim to enhance the productivity.

- K9s for kubernetes managemer

- Vimimum Extension on Chrome

- LazyGit for Git Version Control.

- Tmux for panel and window management on Terminal environment.


## The evolution from Vim to Neovim.
NeoVim is an open source project that forked from Vim to resolve Vim's headache issues:

- Allow contributions from community. The community support from Neovim is better than Vim when Neovim has 66.8 Github star (Jun 18 2023) and 1000 contributors while Vim just has 30.5k with 195 contributors.

- Configure in Lua with awsome plugins: Tresiter, LSP, Telescope.

- Floating UI support to allow plugins create smart UI/UX.

- With lazy options, to speed up loading multiple plugins at starting time.

- Nvim load the config from the ~/.config/ but vim is not. Vim's config file is `~/.vimrc`. Centralize configuration in ~/.config/ folder could back up easily later.

![Neovim is popular as Vim](./assets/best_editor_survey.jpg)

## How to start with NeoVim
For beginner, Neovim or Vim is really hard at the beginning time. To get used to with it, you could follow my proposal reoadmap:

![Vim learning curve](./assets/vim_learning_curve.png)

1. Firstly, to get used To with Neovim, you could walk around with command: `vimtutor`. After getting familiar with Neovim style, you could switch to use the Vim officially.

2. Secondly, I highly recommend you to try using Neovim mode in your existing IDE. It could help you avoid being overwhelmed by the Neovim world.

3. Try with an Nvim Template Project.

4. Learn Lua and build your customized Neovim configuration. Here is step by step to configure your customized Neovim:

- Plugins Managemer (Lazy Nvim, Packer,...)

- Nvim configuration structure.

- Choose needed plugins depend on your demand

- Key mappings for internal neovim and installed plugins.

## Neovim Plugins
- What is IDE.
- Which features Neovim need to be configured to become an IDE?

You already knew the Neovim with a lot of great features in the first part.
In this part, I will show Neovim plugins that you could install to make the Neovim work as an IDE.

List of Neovim plugins to make neovim as an IDE.
- Tresiter for Syntax Highlighting.

- LSP.
The Language Server Protocol (LSP) defines the protocol used between an editor or IDE and a language server that provides language features like auto complete, go to definition, find all references etc.
- Telescope for searching, previewing file and words.

| ![Telescope Demo](./assets/telescope.gif) |
|:--:|
| *(source: Telescope Github Repo)* |

- Git signs for Git Integration.
https://github.com/lewis6991/gitsigns.nvim

- Hop for quickly move the cursor to anywhere on the current view.

- Null-ls for code auto-formating.

Awssome plugins list:
https://github.com/rockerBOO/awesome-neovim

## Neovim Challenges
Challenges with NeoVim:
1. Take a lot of time and effort at the begining time.

| ![Vim learning curve with others](./assets/vim_learning_curve_with_others.webp) |
|:--:|
| *Vim learning curve with other tools (source: Internet)* |

*Vim learning curve with other tools*

2. Need a big motivation and an open mindset to bare with Neovim at the begining time and get familiar with it day by day.

|![We are too busy](./assets/weel-too-busy.png)|
|:--:|
| *Need an optimized work philosophy (source: Steen Schledermann)* |

## Conclusion
- Vim or Neovim is recommended by many famous universities for programing students or software engineer and developers.
![CS107 from Standford](./assets/standford_cs107.png)
![MIT missing semester course](./assets/mit_missing_course.png)

For choosing an IDE, there is no best solution, just go ahead with your most suitable or familiar one.

Take everything with a grain of salt. Just be yourself.

## Appendix:
Vim quick guide:

It is a lightweight editor with 4 main modes: Normal, Insert, Visual and Command with these usages:
- In Normal mode (press <Esc> to enter this mode): you can easily move the cursor with h,j,k,l or by other shortcuts.
- In Insert Mode (from Normal mode, press <i> to enter this mode): You could edit the text at the current cursor.
- In Visual mode (from Normal mode, press <v>): You can select your words and then have follow up action (often yank).
- Command mode: (from Normal mode, press <:>) for running a command.
