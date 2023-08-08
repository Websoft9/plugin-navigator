[![](https://lab.frogg.it/lydra/yunohost/ansible-yunohost/badges/main/pipeline.svg)](https://github.com/Websoft9/plugin-navigator/actions)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)
[![GitHub last commit](https://img.shields.io/github/last-commit/Websoft9/plugin-navigator)](https://github.com/Websoft9/plugin-navigator)
[![GitHub Release Date](https://img.shields.io/github/release-date/Websoft9/plugin-navigator)](https://github.com/Websoft9/plugin-navigator)
[![GitHub Repo stars](https://img.shields.io/github/stars/Websoft9/plugin-navigator?style=social)](https://github.com/Websoft9/plugin-navigator)

# Websoft9 Plugin - `navigator`

A Featureful File System Browser for Cockpit-remotely browse, manage, edit, upload, and download files on your server through your web browser.

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

## Installation and update

Your server must be have [Websoft9](https://github.com/Websoft9) installed.

```
cd /usr/share/cockpit
wget https://artifact.azureedge.net/release/websoft9/plugin/navigator/navigator-latest.zip && unzip navigator-latest.zip && rm -f navigator-latest.zip
```

## Development

Very special, we will not make any modifications to the code in principle. We only pull the content of the upstream project to release and upload artifacts.

So if you have a better idea or discover a bug, you can submit an [issue on upstream project](https://github.com/45Drives/cockpit-navigator/issues/new/choose).

## DevOps principle

DevOps thinks the same way **[5m1e](https://www.dgmfmoldclamps.com/what-is-5m1e-in-injection-molding-industry/)** for manufacturing companies

We follow the development principle of minimization, rapid release

## License

**plugin-navigator** is maintained by [Websoft9](https://www.websoft9.com) and released under the GPL3 license.
