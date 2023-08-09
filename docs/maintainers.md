# maintainers Guidelines

## DevOps principle

DevOps thinks the same way **[5m1e](https://www.dgmfmoldclamps.com/what-is-5m1e-in-injection-molding-industry/)** for manufacturing companies

We follow the development principle of minimization, rapid release

### Version

Version is connect by [navigator.json](../navigator.json), it will be synchronized by the version of [upstream project](https://github.com/45Drives/cockpit-navigator). DevOps is also triggered by modifying this version of the file.

### Artifact

Websoft9 use below [Artifact](https://jfrog.com/devops-tools/article/what-is-a-software-artifact/) for different usage:

- **Azure Storage for files**: Access [packages list](https://artifact.azureedge.net/release?restype=container&comp=list) at [Azure Storage](https://learn.microsoft.com/en-us/azure/storage/storage-dotnet-how-to-use-blobs#list-the-blobs-in-a-container)

### WorkFlow

Websoft9 use the [Production branch with GitLab flow](https://cm-gitlab.stanford.edu/help/workflow/gitlab_flow.md#production-branch-with-gitlab-flow) for development collaboration
