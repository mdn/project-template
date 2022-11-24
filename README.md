# MDN repository template

Welcome! This is starter-kit repository template for you to start any project on MDN. This template defines the required files, such as [Licence](https://github.com/mdn/project-template/blob/main/LICENSE.md), [Security](https://github.com/mdn/project-template/blob/main/SECURITY.md), and [Code of conduct](https://github.com/mdn/project-template/blob/main/CODE_OF_CONDUCT.md) files, that you need to have in your respository for consistency across the MDN GitHub org. You can fine tune other files as needed in your project.

### Getting started

1. Click the "Use this template" button at the top of the repository, and choose "Create a new respository".

    This will open the "Create a new repository from project-template" form.

2. Choose `mdn` in the "Owner" drop-down, give the repository a name in the "Repository name" field, and click the "Create repository from template" button.
3. Copy the contents of `README-template.md` into the `README.md` file and adjust it to your project.
4. Check for TODOs in the repository and adjust them to your project.

```bash
git clone git@github.com:mdn/<repo-name>.git && cd <repo-name>
mv README-template.md README.md
grep -r TODO .
```

### Configuring GitHub actions

For the `auto-merge` workflow, you need to add a personal access token to the repository.
For more details, see the [documentation for the action](https://github.com/mdn/workflows#auto-merge).

## Attribution

This template is on based on the [CNCF project template](https://github.com/cncf/project-template) distributed under an [Apache license 2.0](https://github.com/cncf/project-template/blob/main/LICENSE).
