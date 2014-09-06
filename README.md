# Create backup copy

## Overview

This is a simple Sublime Text 3 package that adds a hotkey and command to create a time-stamped copy of the current file.

Backups follow the simple format `<basename>_YYYY-MM-DD_HHMMSS.<extension>` and are saved in a hidden `.sublime-backup` subdirectory next to the original. **Note:** The directory won't be hidden on Windows.

## Usage

The hotkey defaults to <kbd>Alt</kbd> + <kbd>Shift</kbd> + <kbd>B</kbd>. Use the `create_backup_copy` command in your key bindings to customize it, e.g.:


```json
[
    { 
      "keys": ["alt+shift+b"], "command": "create_backup_copy"
    }
]
```

In addition to the hotkey, you can access the plugin via the command palette (command: *Create backup copy of file*).

## License

This plugin is licensed under the [GNU GPLv3](http://www.gnu.de/documents/gpl-3.0.en.html). A copy of the license is included in the LICENSE file that accompanies this README.

*Copyright 2014 Glutanimate*.