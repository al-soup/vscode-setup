# My Visual Studio Code IDE Settings

`settings.json` and `keybindings.json` are used to custumize the [VS Code IDE](https://code.visualstudio.com/).

On **macOS** files are located under _\$HOME/Library/Application Support/Code/User/settings.json_. On **Linux** under _\$HOME/.config/Code/User/settings.json_.

# Setup

## Extensions

Create extension list: `code --list-extensions > vscode-extensions.list`

Install exentsions: `cat vscode-extensions.list | xargs -L 1 code --install-extension`

## macOS 

Add fast keyrepeat: `defaults write com.microsoft.VSCode ApplePressAndHoldEnabled -bool false`
