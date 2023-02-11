# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 1.0.0

- Initial release

## 2.0.0

- Removed unused `package-lock.json`
- Removed *Auto Rename Tag*.

### Auto Rename Tag

VSCode released the [Auto update tags](https://code.visualstudio.com/Docs/languages/html#_auto-update-tags), which makes unnecessary the usage of an extra extensions for this.

It is worth noting that this option is disabled by default. It can be enabled by setting:
```json
"editor.linkedEditing": true
```
