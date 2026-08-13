Icons
=====


KDE
---

	System Settings -> File Associations

Add a text file association for:

	*.agd

Description:

	Silver data

Click on the icon editor, click `Browse...` (bottom left) and choose:

	path-to/silver-workspace/icon-simplified.svg

Application preference eg Kate



VScode - Material Icon theme
----------------------------

Add symlink to a copy of the icon:
Eg
	~/.vscode-oss/extensions/pkief.material-icon-theme-5.37.0-universal/icons/silver.svg
pointing to:
	path-to/silver-workspace/vscode-icon.svg


Then add the association for silver:

```json
    "material-icon-theme.files.associations": {
        "*.agd": "silver"
    }
```

Vscode doesn't seem to support `prefers-color-scheme` for its icons so the file is simplified to look okay in light/dark.