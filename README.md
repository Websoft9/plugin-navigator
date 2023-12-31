[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)
[![GitHub last commit](https://img.shields.io/github/last-commit/Websoft9/plugin-navigator)](https://github.com/Websoft9/plugin-navigator)
[![GitHub Release Date](https://img.shields.io/github/release-date/Websoft9/plugin-navigator)](https://github.com/Websoft9/plugin-navigator)
[![GitHub Repo stars](https://img.shields.io/github/stars/Websoft9/plugin-navigator?style=social)](https://github.com/Websoft9/plugin-navigator)

# Websoft9 Plugin - `navigator`

This repository is fork from [cockpit-navigator](https://github.com/45Drives/cockpit-navigator.git) which is a file System Browser for Cockpit-remotely browse, manage, edit, upload, and download files on your server through your web browser.

## Features

With no command line use needed, you can:

- Navigate the entire filesystem,
- Create, delete, and rename files,
- Edit file contents,
- Edit file ownership and permissions,
- Create symbolic links to files and directories,
- Reorganize files through cut, copy, and paste,
- **Upload files by dragging and dropping**,
- **Download files and directories**.

| Browsing Filesystem                      |
| ---------------------------------------- |
| ![User Interface](./src/doc/ui_root.png) |

| Editing Content                           | Editing Properties                          |
| ----------------------------------------- | ------------------------------------------- |
| ![Edit Contents](./src/doc/ui_editor.png) | ![Edit Preferences](./src/doc/ui_prefs.png) |

## Install and Upgrade

This plugin is a part of [Websoft9](https://github.com/Websoft9/websoft9) which is a web-based PaaS platform.

You can install or upgrade it by below command:

```
wget https://websoft9.github.io/websoft9/scripts/update_zip.sh && bash ./update_zip.sh --channel release --package_name "navigator-latest.zip" --sync_to "/usr/share/cockpit/navigator"
```

## How to contribute it?

We greatly welcome community contributions to provide suggestions and improvements to our project:

1. Reporting bugs
   If you find a bug, please tell us so we can triage it. All bugs are managed in this [GitHub repo](https://github.com/45Drives/cockpit-navigator/issues/new/choose).

2. Feature requests
   You can request new features in this [GitHub repo](https://github.com/Websoft9/plugin-navigator/issues/new?assignees=&labels=enhancement&projects=&template=feature_request.md&title=enhancement+title+for+%5Bappname%5D).

3. Contributing to the navigator codebase, some times will have reward for it  
   Please follow our [contribution guidelines](CONTRIBUTING.md) when making a contribution.

## License

**plugin-navigator** is maintained by [Websoft9](https://www.websoft9.com) and released under the GPL3 license.
