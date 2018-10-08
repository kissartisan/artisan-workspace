    [
        /** Pane manipulations */
        { "keys": ["ctrl+'", "ctrl+up"], "command": "travel_to_pane", "args": {"direction": "up"} },
        { "keys": ["ctrl+'", "ctrl+right"], "command": "travel_to_pane", "args": {"direction": "right"} },
        { "keys": ["ctrl+'", "ctrl+down"], "command": "travel_to_pane", "args": {"direction": "down"} },
        { "keys": ["ctrl+'", "ctrl+left"], "command": "travel_to_pane", "args": {"direction": "left"} },

        /* ORIGAMI: CREATING a pane */
        { "keys": ["ctrl+.", "ctrl+up"], "command": "create_pane", "args": {"direction": "up", "give_focus": true } },
        { "keys": ["ctrl+.", "ctrl+right"], "command": "create_pane", "args": {"direction": "right", "give_focus": true } },
        { "keys": ["ctrl+.", "ctrl+down"], "command": "create_pane", "args": {"direction": "down", "give_focus": true } },
        { "keys": ["ctrl+.", "ctrl+left"], "command": "create_pane", "args": {"direction": "left", "give_focus": true } },

        /* ORIGAMI: DESTROYING the current pane */
        { "keys": ["ctrl+.", "ctrl+."], "command": "destroy_pane", "args": {"direction": "self"} },

        /* PHP COMPANION */
        { "keys": ["alt+f"], "command": "find_use" },
        { "keys": ["alt+i"], "command": "implement" },
        { "keys": ["alt+c"], "command": "insert_php_constructor_property" },
        { "keys": ["alt+e"], "command": "expand_fqcn" },
    ]
