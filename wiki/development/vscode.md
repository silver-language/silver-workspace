VSCode
======


Material Icons
--------------

Add symlink to a copy of the icon:
Eg
	~/.vscode-oss/extensions/pkief.material-icon-theme-5.37.0-universal/icons/silver.svg
pointing to:
	path-to/silver-workspace/icon-simplified.svg


Then add the association for silver:

```json
    "material-icon-theme.files.associations": {
        "*.agd": "silver"
    }
```

Vscode doesn't seem to support `prefers-color-scheme` for its icons so the file is simplified to look okay in light/dark.