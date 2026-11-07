# Andromeda's Create — Modpack Update Checker Data

This repository hosts the [Modpack Update Checker](https://modpack-update-checker.github.io/wiki/) remote metadata and changelogs for **Andromeda's Create**.

## Configuration

In `config/modpack-update-checker/config.json`:

```json
{
  "schemaVersion": 9,
  "currentVersion": "0.3.2-patch3",
  "modpackName": "Andromeda's Create",
  "modpackAuthor": "TheAndromedaCat",
  "modpackReleaseType": "stable",
  "updateCheckerId": "https://raw.githubusercontent.com/A-Little-Bit-of-Everything/ac-update-checker/main/",
  "advanced": {
    "bccEnabled": false,
    "expandButton": false,
    "updateCheckerType": 2,
    "retroWarning": false,
    "modpackMods": []
  }
}
```

## Structure

- `meta.json`: Core version registry, release timestamps, and download links.
- `versions/<id>/changelog.txt`: Markdown changelog displayed in-game when an update is available.
