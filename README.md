# My Visual Studio Code IDE Settings

`settings.json` and `keybindings.json` are used to custumize the [VS Code IDE](https://code.visualstudio.com/).

You can use it by replacing the existing ones. In **macOS** the files are located under _\$HOME/Library/Application Support/Code/User/settings.json_. In **Linux** they are under _\$HOME/.config/Code/User/settings.json_.

# List of all extensions I use

`code --list-extensions`

```console
Angular.ng-template
be5invis.vscode-custom-css
christian-kohler.npm-intellisense
christian-kohler.path-intellisense
CoenraadS.bracket-pair-colorizer-2
dbaeumer.vscode-eslint
donjayamanne.githistory
DSKWRK.vscode-generate-getter-setter
esbenp.prettier-vscode
ExodiusStudios.comment-anchors
huizhou.githd
jakethashi.vscode-angular2-emmet
joelday.docthis
johnpapa.Angular2
jspolancor.presentationmode
markfknight.monokai-operator-theme
ms-mssql.mssql
ms-vscode.vscode-typescript-tslint-plugin
msjsdiag.debugger-for-chrome
naumovs.color-highlight
PKief.material-icon-theme
Prisma.vscode-graphql
rbbit.typescript-hero
ryuta46.multi-command
skyapps.fish-vscode
steoates.autoimport
Telerik.nativescript
vincaslt.highlight-matching-tag
vscodevim.vim
wix.vscode-import-cost
yzane.markdown-pdf
```

**Batch install**: If you have the [fish shell](https://fishshell.com/) installed you can batch install a list of extensions by saving them under *vs-extensions.txt* in the format above and using [one of my functions](https://github.com/al-soup/my-fish-functions/blob/master/vscodeinstall.fish). Run `vscodeinstall vs-extensions.txt`.
