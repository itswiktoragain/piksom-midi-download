# Piksom source releases

The `code` branch stores each independent release in a **separate root folder** named by its compact version identifier. Never overwrite a prior release.

- `d` = desktop Java app; `m` = Android mobile app.
- `s` = Scarlet development era.
- Trailing integer = whole-number build within that era; no decimal or patch builds.
- Current versions: `ds11` and `ms11`, each in its own folder.
- Future Scarlet versions: `ds12`, `ms12` and so on.
- When an era ends, use the new era's identifying letter and restart at **1**. The future era letter will be chosen when that era is named.

Examples:

```text
code branch
├── VERSIONS.md
├── ds11/   # Desktop Scarlet 11 source
└── ms11/   # Mobile Scarlet 11 source
```

The branch `page` is the download website; source belongs on `code` only.
