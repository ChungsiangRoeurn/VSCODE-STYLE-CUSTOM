# VSCODE-STYLE-CUSTOM

JUST COPY AND PASTE IN TO YOUR VSCODE BY USING COMMAND CTRL + SHIFT P PASTE ALL THESE INTO THERE.

{
  // =====================================
  //  UI Layout & Appearance (FIXED)
  // =====================================
  "workbench.activityBar.location": "top",
  "workbench.sideBar.location": "left",
  "window.menuBarVisibility": "toggle",
  "workbench.editor.enablePreview": false,
  "window.commandCenter": false,

  // =====================================
  //& Text Customization (FIXED)
  // =====================================
  "editor.fontFamily": "'JetBrains Mono', 'Fira Code', monospace",
  "editor.fontLigatures": true,
  "editor.fontSize": 15,
  "editor.lineHeight": 1.8,
  "editor.letterSpacing": 0.5,
  "editor.tabSize": 2,
  "editor.renderWhitespace": "all",
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": "active",
  "editor.inlayHints.enabled": "on",

  // Formatting & Linting
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit",
    "source.organizeImports": "explicit"
  },

  // Fixed padding syntax
  "editor.padding.top": 15,
  "editor.padding.bottom": 15,
  "workbench.iconTheme": "material-icon-theme",
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": ["comment"],
        "settings": { "foreground": "#7CFC00" }
      },
      {
        "scope": ["keyword", "storage"],
        "settings": { "foreground": "#7B68EE" }
      },
      {
        "scope": ["function", "method"],
        "settings": { "foreground": "#9370DB" }
      },
      {
        "scope": ["variable", "property"],
        "settings": { "foreground": "#00FA9A" }
      }
    ]
  },

  // =====================================
  //  Terminal Customization (FIXED)
  // =====================================
  "terminal.integrated.fontFamily": "JetBrains Mono",
  "terminal.integrated.fontSize": 14,
  "terminal.integrated.lineHeight": 1.6,
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.defaultProfile.linux": "zsh",
  "terminal.integrated.localEchoStyle": "dim",

  // =====================================
  //  Advanced Editor Features (FIXED)
  // =====================================
  "editor.smoothScrolling": true,
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.cursorBlinking": "smooth",
  "editor.cursorStyle": "line-thin",
  "editor.multiCursorModifier": "alt",
  "editor.quickSuggestions": {
    "comments": "on",
    "strings": "on"
  },

  // =====================================
  //  Import & Navigation Fixes (ADDED)
  // =====================================
  "javascript.referencesCodeLens.enabled": true,
  "typescript.referencesCodeLens.enabled": true,
  "typescript.preferences.importModuleSpecifier": "relative",
  "typescript.preferences.autoImportFileExcludePatterns": [
    "**/node_modules/**"
  ],
  "editor.links": true,

  // =====================================
  //  Workspace Optimization
  // =====================================
  "files.autoSave": "afterDelay",
  "files.autoSaveDelay": 1500,
  "files.exclude": {
    "**/.git": true,
    "**/.svn": true,
    "**/dist": true,
    "**/vendor": true
  },
  "explorer.compactFolders": false,
  "explorer.confirmDelete": false,

  // =====================================
  //  Performance & Privacy
  // =====================================
  "telemetry.telemetryLevel": "off",
  "workbench.editor.limit.enabled": true,
  "workbench.editor.limit.perEditorGroup": 8,
  "search.useIgnoreFiles": true,
  "search.quickOpen.includeSymbols": false,

  // =====================================
  //  Framework Enhancements
  // =====================================
  "tailwindCSS.experimental.classRegex": [
    "tw`([^`]*)`",
    "tw\\([^)]*\\)",
    "cn\\(([^)]*)\\)"
  ],
  "javascript.updateImportsOnFileMove.enabled": "always",
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "blade.php": "html"
  },

  // =====================================
  //  Accessibility & UX (FIXED)
  // =====================================
  "editor.accessibilitySupport": "off",
  "workbench.settings.editor": "json",
  "workbench.tips.enabled": false,
  "debug.toolBarLocation": "docked",
  "breadcrumbs.enabled": true,
  "window.customTitleBarVisibility": "auto",
  "workbench.colorTheme": "Abyss",
  "window.titleBarStyle": "custom",
  "color-highlight.matchRgbWithNoFunction": true,
  "git.enableSmartCommit": true,
  "material-icon-theme.activeIconPack": "nest"
}
