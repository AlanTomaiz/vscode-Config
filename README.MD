## :fire: Configs
//
{
    // Tema
    "workbench.colorTheme": "Omni",
    "workbench.iconTheme": "material-icon-theme",

    // Tamanho e familia de fonte
    "editor.tabSize": 2,
    "editor.fontSize": 18,
    "editor.lineHeight": 26,
    "editor.fontFamily": "Fira Code",

    // Code style
    "editor.rulers": [80, 120],
    "files.insertFinalNewline": true,
    "files.trimTrailingWhitespace": true,

    "javascript.updateImportsOnFileMove.enabled": "never",
    "[javascript]": {
        "editor.formatOnSave": true,
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true
        }
    },

    "[javascriptreact]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true
        }
    },

    "typescript.updateImportsOnFileMove.enabled": "never",
    "[typescript]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true
        }
    },

    "[typescriptreact]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true
        }
    },

    "php.suggest.basic": false,
    "[php]": {
        "editor.formatOnSave": true,
    },

    // Workspace
    "editor.renderLineHighlight": "gutter",
    "workbench.startupEditor": "none",
    "workbench.editor.labelFormat": "short",
    "explorer.confirmDelete": false,
    "explorer.compactFolders": false,
    "explorer.confirmDragAndDrop": false,

    // Terminal
    "terminal.integrated.fontSize": 16,
    "terminal.integrated.shell.linux": "/bin/zsh"
}
