    // Place your key bindings in this file to overwrite the defaults
    [
        {
            "key": "ctrl+k ctrl+b",
            "command": "workbench.action.toggleSidebarVisibility"
        },
        {
            "key": "ctrl+r",
            "command": "workbench.action.gotoSymbol"
        },
        {
            "key": "ctrl+shift+r",
            "command": "workbench.action.showAllSymbols"
        },
        {
            "key": "ctrl+shift+down",
            "command": "workbench.action.terminal.focusNext"
        },
        {
            "key": "ctrl+shift+up",
            "command": "workbench.action.terminal.focusPrevious"
        },
        {
            "key": "ctrl+shift+g",
            "command": "workbench.view.scm",
            "when": "gitlens:enabled && gitlens:keymap == 'chorded'"
        },
        {
            "key": "shift+f1",
            "command": "settings.action.focusPreviousSetting",
            "when": "inSettingsSearch"
        },
        {
            "key": "shift+enter",
            "command": "-settings.action.focusPreviousSetting",
            "when": "inSettingsSearch"
        },
        {
            "key": "alt+enter",
            "command": "editor.action.showContextMenu",
            "when": "textInputFocus"
        },
        {
            "key": "shift+f10",
            "command": "-editor.action.showContextMenu",
            "when": "textInputFocus"
        },
        {
            "key": "shift+f2",
            "command": "debug.openBreakpointToSide",
            "when": "breakpointsFocused"
        },
        {
            "key": "alt+enter",
            "command": "-debug.openBreakpointToSide",
            "when": "breakpointsFocused"
        },
        {
            "key": "shift+f3",
            "command": "editor.action.selectAllMatches",
            "when": "editorFocus && findWidgetVisible"
        },
        {
            "key": "alt+enter",
            "command": "-editor.action.selectAllMatches",
            "when": "editorFocus && findWidgetVisible"
        },
        {
            "key": "alt+f",
            "command": "namespaceResolver.import",
            "when": "editorTextFocus"
        },
        {
            "key": "ctrl+alt+i",
            "command": "-namespaceResolver.import",
            "when": "editorTextFocus"
        },
        {
            "key": "alt+e",
            "command": "namespaceResolver.expand",
            "when": "editorTextFocus"
        },
        {
            "key": "ctrl+alt+e",
            "command": "-namespaceResolver.expand",
            "when": "editorTextFocus"
        },
        {
            "key": "ctrl+f11",
            "command": "workbench.action.toggleMaximizedPanel"
        }
    ]
