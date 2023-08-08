[![](https://lab.frogg.it/lydra/yunohost/ansible-yunohost/badges/main/pipeline.svg)](https://lab.frogg.it/lydra/yunohost/ansible-yunohost/-/pipelines)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)
[![GitHub last commit](https://img.shields.io/github/last-commit/LydraFr/ansible-yunohost)](https://github.com/LydraFr/ansible-yunohost)
[![GitHub Release Date](https://img.shields.io/github/release-date/LydraFr/ansible-yunohost)](https://github.com/LydraFr/ansible-yunohost)
[![GitHub Repo stars](https://img.shields.io/github/stars/LydraFr/ansible-yunohost?style=social)](https://github.com/LydraFr/ansible-yunohost)

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

| Browsing Filesystem                    |
| -------------------------------------- |
| ![User Interface](src/doc/ui_root.png) |

| Editing Content                         | Editing Properties                        |
| --------------------------------------- | ----------------------------------------- |
| ![Edit Contents](src/doc/ui_editor.png) | ![Edit Preferences](src/doc/ui_prefs.png) |

## Installation and update

Your server must be have [Websoft9](https://github.com/Websoft9) installed.

```
cd /usr/share/cockpit
wget https://artifact.azureedge.net/release/websoft9/plugin/navigator/navigator-latest.zip && unzip navigator-latest.zip && rm -f navigator-latest.zip
```

## Development

Very special, in principle, we will not make any modifications to the code itself. The [source code](./src) in the project is currently only used as a reference. When there is a update in the [upstream project](https://github.com/45Drives/cockpit-navigator), we will first pull the latest content of the upstream project and merge necessary document files to release the source code package and artifacts.

So if you have a better idea or discover a bug, you can submit an [issue on upstream project](https://github.com/45Drives/cockpit-navigator/issues/new/choose).

## DevOps principle

DevOps thinks the same way **[5m1e](https://www.dgmfmoldclamps.com/what-is-5m1e-in-injection-molding-industry/)** for manufacturing companies

We follow the development principle of minimization, rapid release

### Version

Synchronize version of [upstream project](https://github.com/45Drives/cockpit-navigator)

### Artifact

Websoft9 use below [Artifact](https://jfrog.com/devops-tools/article/what-is-a-software-artifact/) for different usage:

- **Azure Storage for files**: Access [packages list](https://artifact.azureedge.net/release?restype=container&comp=list) at [Azure Storage](https://learn.microsoft.com/en-us/azure/storage/storage-dotnet-how-to-use-blobs#list-the-blobs-in-a-container)

## License

**plugin-navigator** is maintained by [Websoft9](https://www.websoft9.com) and released under the GPL3 license.
