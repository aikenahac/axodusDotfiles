# axodusDotfiles

Hey guys, welcome to my dotfiles. You will find attached every main feature of my setup.

## Installation of stuff

Let's start with what we need:

### alacritty terminal
For the terminal, I am using alacritty with the zsh shell which has the powerlevel10k theme applied to it.
You can find all necessary links here:
* <a href="https://github.com/alacritty/alacritty">alacritty</a>
* <a href="https://github.com/romkatv/powerlevel10k">powerlevel10k</a>
* zsh: install via preffered package managet. It's already set as shell in Alacritty terminal

### polybar
For the status bar I am using polybar with a semi-custom config found in the dotfiles. 
You can find polybar <a href="https://github.com/polybar/polybar">here</a>.

### rofi
For the power menu I am using rofi, install <a href="https://github.com/davatorium/rofi">here</a>.

### dunst
My notification manager is the beloved dunst with my config. You can instal dunst via <a href="https://github.com/dunst-project/dunst">this GitHub repo</a>.

### spicetify
For the Spotify theme I am using <a href="https://github.com/morpheusthewhite/spicetify-themes/tree/master/Dribbblish">Dribbblish</a>, which is a theme made for <a href="https://github.com/morpheusthewhite/spicetify-themes/tree/master/Dribbblish"> Spicetify</a>.

## My config
Clone this repo

```
git clone https://github.com/Axodus/axodusDotfiles.git
```

Change directory inside the .config of **my** dotfiles.

```
cd axodusDotfiles/.config/
```

Copy all of the folders into your own .config

Example:
```
sudo cp -r alacritty/ ~/.config/
```
Do this for all the folders.

### Replacing GNOMEs status bar with polybar
Well for that I just use the extension <a href="https://extensions.gnome.org/extension/545/hide-top-bar/">hied-top-bar</a>.
![Settings for the extension](https://davatorium.github.io/rofi/images/rofi/window-list.png)
