# Colibri-Vscode

## Background

This is port of [colibri](https://github.com/archseer/colibri.vim), 
originally a VIM colorscheme, for Visual Studio Code.

I first found out about this scheme from [Helix](https://helix-editor.com/). I've been
using Helix for a couple of months, mostly for coding my 
[personal projects](https://ahmadalkadri.com/categories/projects/), 
and I found myself liking it a lot.

Somehow, one day I realized one of the biggest reasons of me 
liking Helix is not because of its simplicity, keybindings etc.,
but primarily because of its default colorscheme. It's so colorful
yet unobstrusive at the same time.

| ![Really like the colors](https://github.com/ahmad-alkadri/colibri-vscode/assets/22837764/7ec091df-4df3-40f5-a48b-d8b0a7055247) |
| --- |
| *Really like the colors* |

Unfortunately, mostly for work, I had to use VSCode. It's
simply an IDE that is the most widely used, plus there are
some extensions that are very useful for collaborative
works and debugging/testing.

Thus, that's why I decided to port this colorscheme into
a VSCode theme. 

After a quick digging, I found out that the default theme
for Helix is [called colibri](https://github.com/helix-editor/helix/discussions/8575). 
A quick search later and I found the [repo](https://github.com/archseer/colibri.vim).

The repo has the link to a website with the colorschemes
and their scopes. That made the porting so easy. I felt lucky.

## Installation

Currently, I'm still working out the CD/CI (with Github Actions)
for automatically publishing the theme into VSCode Marketplace.

In the meantime, you can install this theme on your VSCode by
following the steps below:

1. Cloning the repository:
    ```bash
    git clone https://github.com/ahmad-alkadri/colibri-vscode.git
    ```

2. Copying/moving it into your VSCode's extension folder:
    ```bash
    mv colibri-vscode ~/.vscode/extensions/
    ```

3. Open/reopen/restart your VSCode and go to `View -> Command Palette -> Preferences: Color Theme`, then find `Colibri-Vscode` and click it.

4. If all goes well, you should see the theme set for your VSCode as follows:

## Issues & Contributing

Contributions are welcome! You must've realized that I haven't yet
ported all colors and scopes. If you'd like to help doing it,
please don't hesitate! And of course, if you find any issues, problems,
bugs, please raise them as Issues in this repo.

## License

MIT © 2024 Ahmad Alkadri,
MIT © 2017 Blaž Hrastnik, 
see [the license](LICENSE).
