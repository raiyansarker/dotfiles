[Guide](https://linkarzu.com/posts/macos/alacritty-to-kitty/)
<br>
[Themes](https://github.com/kovidgoyal/kitty-themes)

```sh
# This installs the kitty terminal
brew install --cask kitty

# I am also installing the fonts I like to use currently with my kitty config
brew install --cask font-meslo-lg-nerd-font

# This also downloads the kitty themes and puts them in the directory where my
# config looks
mkdir -p ~/github/dotfiles-latest/kitty/themes/
git clone --depth 1 https://github.com/kovidgoyal/kitty-themes.git ~/github/dotfiles-latest/kitty/themes/
rm -rf ~/github/dotfiles-latest/kitty/themes/.git/
rm -rf ~/github/dotfiles-latest/kitty/themes/.github/
```
