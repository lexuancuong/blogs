# NEOVIM IS NOT JUST AN EDITOR
My thoughts to use neovim as an fully IDE.

## Outline

## 1. Overview
Vim is improved of Vi with more features. Vim is a command line text editor available on Linux, MacOs and Windows. Vim is the most popular editor on the world.

What is the Outstanding points of Vim compared to other similar tools:

- Vim is lightweight and can run on many environment. (on different kind of machines: Server, Local Machine or different kind of operating systems Linux Macos Windows)

- The strongest mindset of Neovim is all needed keyboards on the Alpha area (with `h`, `j`, `k` and `l` for movement).
It avoid moving from alpha area to arrow are on the keyboard and from the keyboard to the mouse.


The evolution from Vim to Neovim.
NeoVim is an open source project that forked from Vim to resolve Vim's headache issues:
- Allow contributions from community.
- Configure in Lua with awsome plugins: Tresiter, LSP, Telescope.
- Floating UI support to allow plugins create smart UI/UX.
- With lazy options, to speed up loading multiple plugins at starting time.
- Nvim load the config from the ~/.config/ but vim is not. Vim's config file is `~/.vimrc`. Centralize configuration in ~/.config/ folder could back up easily later.

![Neovim is popular as Vim](./assets/best_editor_survey.jpg)

## 2. How to start with NeoVim
1. Firstly, to get used To with Neovim, you could walk around with command: `vimtutor`. After getting familiar with Neovim style, you could switch to use the Vim officially.

2. Secondly, I highly recommend you to try using Neovim mode in your existing IDE. It could help you avoid being overwhelmed by the Neovim world.

3. Try with an Nvim Template Project.

4. Learn Lua and build your customized Neovim configuration. Here is basic steps to configure your customized Neovim:
- Plugins Managemer (Lazy Nvim)
- Nvim configuration structure.
- Choose needed plugins depend on your demand
- Key mappings for internal neovim and installed plugins.

## Neovim Plugins
- What is IDE.
- Which features Neovim need to be configured to become an IDE?

You already knew the Neovim with a lot of great features in the first part.
In this part, I will show Neovim plugins that you could install to make the Neovim work as an IDE.

List of Neovim plugins to make neovim as an IDE.
- Tresiter
- LSP
- Telescope
- Git linker
- Hop (Vim easy motion)

Awssome plugins list:
https://github.com/rockerBOO/awesome-neovim

## Neovim Challenges
Challenges with NeoVim:
1. Take a lot of time and effort at the begining

2. Need a big motivation and an open mindset to bare with Neovim at the begining time and get familiar with it day by day.

![We are too busy](./assets/weel-too-busy.png)

[Image from Steen Schledermann](https://www.ssp.sh/blog/why-using-neovim-data-engineer-and-writer-2023/weel-too-busy.png)

## Tools with Neovim syntax
- K9s
- Vimimum
- LazyGit
- Tmux

## Conclusion
- Vim or Neovim is recommended by many famous universities for programing students or software engineer and developers.
![CS107 from Standford](./assets/standford_cs107.png)
![MIT missing semester course](./assets/mit_missing_course.png)

For choosing an IDE, there is no best solution, just go ahead with your most suitable or familiar one.

Take everything with a grain of salt. Just be yourself.

## Appendix:
Vim quick guide:
It is lightweight and clever editor with 4 main modes: Normal, Insert, Visual and Visual Line.
- In Normal mode (press <Esc> to enter this mode): you can easily move the cursor with h,j,k,l or by other shortcuts.
- In Insert Mode (from Normal mode, press <i> to enter this mode): You could edit the text at the current cursor.
- In Visual mode (from Normal mode, press <v>): You can select your words and then have follow up action (often yank).
- Command mode: (from Normal mode, press <:>) for running a command.
