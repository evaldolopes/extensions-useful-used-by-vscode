# extensions-useful-used-by-vscode
extensions useful used by vscode

### EXTENSIONS (necessary)

- IntelliSense for CSS class names in HTML [Zignd]
- Javascript Snippets [charalampos karypidis]
- PHP Extension Pack [Xdebug]
- PHP Intelephense [Ben Mewburn]
- PHP Namespace Resolver [Mehedi Hassan]
- Laravel Blade Snippets [Winnie Lin]
- Laravel Snippets [Winnie Lin]
- Laravel Artisan [Ryan Naddy]
- Laravel Extra Intellisense [amir]
- Laravel goto view [codingyu]
- laravel-goto-components [naoray]
- Laravel Blade formatter [Shuhei Hayashibara] (needs .bladeformatterrc on root)
- Prettier - Code formatter [Prettier]
- Auto Rename Tag [Jun Han]
- Auto Close Tag [Jun Han]
- GitLens - Git supercharged [GitKraken]
- MySQL [cweijan]
- Better Comments [Aaron Bond]
- Tailwind CSS IntelliSense [Tailwind Labs]
- Bookmarks [Alessandro Fragnani]
- Git History [Don Jayamanne]
- HTML CSS Support [ecmel]
- PHP Getters & Setters [phproberto]
- Vue Language Features (Volar) [Vue]
- PHP Parameter Hint [Robert]
- Laravel Blade Spacer [Austen Cameron]
- vscode-icons [VSCode Icons Team]

### MY PERSONAL VS CODE SETTINGS

Make <strong>.vscode</strong> directory on your root project with <strong>settings.json</strong> file. Insert the following settings in settings.json file:

```
{
    "workbench.iconTheme": "vscode-icons",
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[php]": {
        "editor.defaultFormatter": "bmewburn.vscode-intelephense-client"
    },
    "[css]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[blade]": {
        // "editor.defaultFormatter": "animus-coop.vscode-phpstorm-formatter"
    },
    "explorer.confirmDelete": true,
    "[scss]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "prettier.printWidth": 120,
    "[vue]": {
        "editor.defaultFormatter": "octref.vetur"
    },
    "editor.formatOnPaste": true,
    "editor.formatOnType": true,
    "editor.suggestSelection": "first",
    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
    "powermode.enabled": false,
    //   "powermode.presets": "flames",
    "editor.linkedEditing": true,
    "[dart]": {
        "editor.formatOnSave": true,
        "editor.formatOnType": true,
        "editor.rulers": [
            120
        ],
        "editor.selectionHighlight": false,
        "editor.suggest.snippetsPreventQuickSuggestions": false,
        "editor.suggestSelection": "first",
        "editor.tabCompletion": "onlySnippets",
        "editor.wordBasedSuggestions": false
    },
    "editor.fontFamily": "'Fira Code' ,Consolas, 'Courier New', monospace",
    "editor.fontSize": 12,
    "editor.fontLigatures": true,
    "workbench.colorCustomizations": {
        "tab.activeBackground": "#00aeff"
    },
    "dart.flutterCreateAndroidLanguage": "java",
    "dart.flutterCustomEmulators": [],
    "dart.openDevTools": "flutter",
    "files.associations": {
        "*.php": "php"
    },
    "php.validate.enable": true,
    "window.zoomLevel": 2,
    "github.gitAuthentication": false,
    "terminal.integrated.defaultProfile.windows": "Command Prompt",
    "terminal.external.windowsExec": "${env:windir}\\System32\\cmd.exe",
    "terminal.integrated.env.windows": {
        "CMDER_ROOT": "D:\\laragon\\bin\\cmder"
    },
    "terminal.integrated.profiles.windows": {
        "PowerShell": {
            "source": "PowerShell",
            "icon": "terminal-powershell"
        },
        "Command Prompt": {
            "path": [
                "${env:windir}\\Sysnative\\cmd.exe",
                "${env:windir}\\System32\\cmd.exe"
            ],
            "args": [
                "/k %CMDER_ROOT%\\vendor\\init.bat"
            ],
            "icon": "terminal-cmd"
        },
        "Git Bash": {
            "source": "Git Bash"
        }
    },
    "git.confirmSync": false,
    "workbench.sideBar.location": "left",
    "workbench.startupEditor": "none",
    "workbench.statusBar.visible": true,
    "editor.minimap.enabled": false,
    "editor.detectIndentation": false,
    "editor.tabSize": 4,
    "editor.formatOnSave": true,
    "editor.wordSeparators": "`~!@#%^&*()-=+[{]}\\|;:'\",.<>/?",
    "editor.bracketPairColorization.enabled": true,
    "editor.guides.bracketPairs": true,
    "[json]": {
        "editor.quickSuggestions": {
            "strings": true
        },
        "gitlens.codeLens.scopes": [
            "document"
        ],
        "editor.defaultFormatter": "vscode.json-language-features",
        "editor.suggest.insertMode": "replace"
    },
    "javascript.preferences.quoteStyle": "single",
    "javascript.updateImportsOnFileMove.enabled": "always",
    "gitlens.statusBar.enabled": false,
    "gitlens.hovers.enabled": false,
    "gitlens.blame.format": "${author|10} ${date}",
    "gitlens.blame.highlight.locations": [
        "gutter",
        "line",
        "overview"
    ],
    "gitlens.blame.avatars": false,
    "gitlens.blame.compact": false,
    "gitlens.defaultDateFormat": "DD/MM/YYYY",
    "gitlens.defaultDateShortFormat": "DD/MM/YYYY",
    "gitlens.blame.heatmap.enabled": false,
    "gitlens.codeLens.enabled": false,
    "files.trimTrailingWhitespace": true,
    // "intelephense.environment.phpVersion": "7.4.30",
    // "php.validate.executablePath": "D:\\laragon\\bin\\php\\php-7.4.30-Win32-vc15-x64\\php.exe",
    "intelephense.environment.phpVersion": "8.1.8",
    // "php.validate.executablePath": "D:\\laragon\\bin\\php\\php-8.1.9-Win32-vc16-x64\\php.exe",
}
```
