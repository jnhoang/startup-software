# startup-software

## Homebrew
---
`ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`


## Git
---
`brew install git`


Configuring git
```
git config --global user.name "YOUR-USERNAME"
git config --global user.email "YOUR-EMAIL-ADDRESS"
git config --global push.default simple
git config --global credential.helper cache
```
Setting up SSH Key


[Github Generating SSH Keys](https://help.github.com/articles/generating-ssh-keys/)


## Node
--- 
```
brew install node
node -v
npm -v
```

To finish up your installation, run this command to allow for global installations of npm tools.
`sudo chown -R $USER /usr/local/lib`


## Sublime
---


### Custom Settings
```
{
  "font_size": 16,
  "hightlight_line": true,
  "ignored_packages":
  [
    "Vintage"
  ],
  "line_padding_bottom": 1,
  "line_padding_top": 1,
  "scroll_past_end": true,
  "shift_tab_unindent": true,
  "tab_size": 2,
  "theme": "Default.sublime-theme",
  "translate_tabs_to_spaces": true
}
```

### Packages
- abacus
- bracket highlighter
- color highlighter
- emmet
- babel
- gitgutter



## Setting up command-line
--- 
add a shortcut so we can load sublime from the Terminal.

`ln -s /Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl /usr/local/bin/subl`


restart

`subl .`


## iterm2
---
(Download)[https://www.iterm2.com/]
curl -L http://install.ohmyz.sh | sh

open the `~/.zhrc` file

* shortcut - `# alias subl="/Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl"`
* theme - `ZSH_THEME="honukai"`

restart terminal


## Postman
---
(Download)[https://app.getpostman.com/app/download/osx64]


## Python
---
(Download)[https://www.python.org/downloads/]