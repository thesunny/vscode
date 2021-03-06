# Setup

## VS Code

- Install from <https://code.visualstudio.com/>
- Open the Command Palette (⇧⌘P) and type 'shell command' to find the Shell Command: Install 'code' command in PATH command.
- `cmd+shift+p` => `install extensions` => `Settings Sync`
- `opt+shift+d` to download sync
- It will ask for two tokens
  - Generate a token at the URL you get redirected to
  - This is my gist id `3572d1be5f4eac359763e5c14a32303c`


## Mac OSX Setup

```
# Key repeat
defaults write com.microsoft.VSCode ApplePressAndHoldEnabled -bool false         # For VS Code
defaults write com.microsoft.VSCodeInsiders ApplePressAndHoldEnabled -bool false # For VS Code Insider
defaults delete -g ApplePressAndHoldEnabled                                      # If necessary, reset global default

# Bad fonts
defaults write -g CGFontRenderingFontSmoothingDisabled -bool FALSE               # Fix wrong fonts on Mojave
```
- Keyboard
  - Set `Key Repeat` to `Fast`
  - Set `Delay Until Repeat` to one notch left of `Short`

## Convert Sublime Text Snippets to VS Code

Use this utility to convert Sublime Text snippets to VS Code

<https://www.npmjs.com/package/convert-snippets-to-vscode>
