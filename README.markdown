## Installation

### Manual Installation

Clone the repository and symlink file to Sublime's User Directory:

#### OS X

Sublime Text 2:

```
git clone git@github.com:unamaria/SublimeTwig.git ~/.sublime_twig

ln -fs ~/.sublime_twig/ ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/SublimeTwig

```

Sublime Text 3:

```
git clone git@github.com:eddorre/Sublimetwig.git ~/.sublime_twig

ln -fs ~/.sublime_twig/ ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/SublimeTwig

```

#### Linux

Sublime Text 2:

```
git clone git@github.com:unamaria/SublimeTwig.git ~/.sublime_twig

ln -fs ~/.sublime_twig/ ~/.config/sublime-text-2/Packages/SublimeTwig
```

Sublime Text 3:

```
git clone git@github.com:unamaria/SublimeTwig.git ~/.sublime_twig

ln -fs ~/.sublime_twig/ ~/.config/sublime-text-3/Packages/SublimeTwig
```

## Usage

### Add Keybinding

Open your User Keybinding File and add the following keybinding to activate the toggle command in all file types:

```json
  [
    { "keys": ["ctrl+shift+."], "command": "twig" }
  ]
```

Now you can use `ctrl+shift+.` to create and toggle between Twig tags (after restarting Sublime Text).

## Update To Latest Version

```
  cd ~/.sublime_twig
  git pull --rebase
```

## Copyright

Created from [SublimeERB](https://github.com/eddorre/SublimeERB) by [Carlos Rodriguez](https://github.com/eddorre).
Released under the MIT License.
