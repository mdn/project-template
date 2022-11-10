# project-template

A project template repository based on the [template repository](https://github.com/cncf/project-template) by the [Cloud Native Computing Foundation](https://github.com/cncf).

## Using this template

To get started, follow these steps:

1. Click the "Use this template" button at the top of the repository.
2. Choose `MDN` as an owner, give the repository a name and select "Create repository from template".
3. Copy the contents of `README-template.md` into the `README.md` file and adjust it to the project.
4. Check for TODOs in the repository and adjust them to the project.

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
