# USE NEOVIM AS AN IDE
My thoughts to use neovim as an fully IDE.

## Outline

## 1. Overview
Vim is improved of Vi with more features. Vim is a command line text editor available on Linux, MacOs and Windows. Vim is the most popular editor on the world.

The evolution from Vim to Neovim.
NeoVim is an open source project that forked from Vim to resolve some issues with Vim and get the contribution from community.
- Configure in Lua.
- Awsome plugins supported: Tresiter, LSP, Telescope.
- With Lazy options, to speed up loading multiple plugins at starting time.
- Floating UI support to allow create smart UI/UX.
- Nvim load the config from the ~/.config/ but vim is not. Vim's config file is `~/.vimrc`. Centralize configuration in ~/.config/ folder could back up easily later.

Outstanding points of Neovim:
- It is recommended by many famous universities for programing students.
![CS107 from Standford](./assets/standford_cs107.png)
![MIT missing semester course](./assets/mit_missing_course.png)

## 2. How to start with Neovim
Firstly, I highly recommend you to try using Neovim mode in your existing IDE. It could help you avoid being overwhelmed by the Neovim world.

To get used to with Neovim, you could walk around with command: `vimtutor`. After getting familiar with Neovim style, you could switch to use the Neovim officially.

Here is basic steps to configure your customized Neovim:
1. Install Plugins in Neovim
2. Nvim configuration structure
Plugins Managemer


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

## Conclusion

Challenges with NeoVim:

1. Take a lot of time and effort at the begining


2. Need a big motivation and open mindset to bare with Neovim at the begining and get familiar with it.

![We are too busy](./assets/weel-too-busy.png)

[Image from Steen Schledermann](https://www.ssp.sh/blog/why-using-neovim-data-engineer-and-writer-2023/weel-too-busy.png)

## Appendix:
Vim quick guide:
It is lightweight and clever editor with 4 main modes: Normal, Insert, Visual and Visual Line.
- In Normal mode (press <Esc> to enter this mode): you can easily move the cursor with h,j,k,l or by other shortcuts.
- In Insert Mode (from Normal mode, press <i> to enter this mode): You could edit the text at the current cursor.
- In Visual mode (from Normal mode, press <v>): You can select your words and then have follow up action (often yank).
- Command mode: (from Normal mode, press <:>) for running a command.
