# Happy Hacking

Happy Hacking is a color scheme for Vim that's largely a rework of/inspired by
[Autumn][autumn]. It comes with various tweaks to the colors, a less messy
codebase and (better) support for more languages.

## Installation

To install this theme the old school way just drop it in ~/.vim/colors and load
it as following (e.g. in your .vimrc);

    color happy_hacking

If you're using Pathogen you can add this theme as following:

    git submodule add git@github.com:YorickPeterse/happy_hacking.vim \
        .vim/bundle/happy-hacking

Then load it like you'd normally would.

## Terminal Support

Happy Hacking can be used in both a GUI and a terminal emulator without the
need to install separate plugins of any kind. Note that due to the amount of
colors available to terminals things might look a little bit different compared
to a Vim GUI.

## License

Happy Hacking and all extra source code in this repository is licensed under
the MIT license unless specified otherwise. A copy of this license can be found
in the file "LICENSE" in the root directory of this repository.

[autumn]: https://github.com/yorickpeterse/autumn.vim
