# Welcome to 'Template for a new repository'

- [Benefits of this repository?](#benefits-of-this-repository)
- [How to use to this repository](#how-to-use-to-this-repository)
- [Getting started](#getting-started)

## Benefits of this repository?

This repository is used as a template, for new repositories on GitHub. So thats not all must created by scratched. 😀

## How to use to this repository

You can clone this repository or download it as archive.

Clone via SSH

```sh
git clone git@github.com:DJBlackEagle/template_for_new_repository.git
```

Clone via HTTPS

```sh
git clone https://github.com/DJBlackEagle/template_for_new_repository.git
```

Clone via GitHub CLI

```sh
gh repo clone DJBlackEagle/template_for_new_repository
```

As Zip archive

```
https://github.com/DJBlackEagle/template_for_new_repository/archive/refs/heads/main.zip
```

## Getting started

### Folder

- `templates/repository` is for new repositories and have all files which is needed (README.md etc.).

### Template Variables

Some files, which have a package name, URL in there. For this, exists some template variables. So you need only search and replace. 😀

List of the template variables:
| Template Variable | Example | Description |
| --------------------------- | --------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| {TPL^URL_GIT} | https://github.com/DJBlackEagle/shared-project-tools | The URL to the GIT repository. |
| {TPL^URL_CONTRIBUTING} | https://github.com/DJBlackEagle/shared-project-tools/blob/main/CONTRIBUTING.md | The URL to the contributing file. |
| {TPL^URL_README} | https://github.com/DJBlackEagle/shared-project-tools/blob/main/README.md | The URL to the readme. |
| {TPL^URL_CHANGELOG} | https://github.com/DJBlackEagle/shared-project-tools/blob/main/CHANGELOG.md | The URL to the changelog. |
| {TPL^URL_CODE_OF_CONDUCT} | https://github.com/DJBlackEagle/shared-project-tools/blob/main/CODE_OF_CONDUCT.md | The URL to the 'Code of Conduct' file. |
| {TPL^URL_LICENSE} | https://github.com/DJBlackEagle/shared-project-tools/blob/main/LICENSE | The URL to the license file. |
| {TPL^URL_SECURITY} | https://github.com/DJBlackEagle/shared-project-tools/blob/main/SECURITY.md | The URL to the security file. |
| {TPL^URL_ISSUES} | https://github.com/DJBlackEagle/shared-project-tools/issues | The URL to the list of issues. |
| {TPL^URL_NEW_ISSUE} | https://github.com/DJBlackEagle/shared-project-tools/issues/new/choose | The URL of creating a new issue. |
| {TPL^URL_PULLREQUEST} | https://github.com/DJBlackEagle/shared-project-tools/pulls | The URL to the pull requests. |
| {TPL^URL_COMMITS} | https://github.com/DJBlackEagle/shared-project-tools/commits/main | The URL to the commit of the GIT repository. |
| {TPL^URL_VULNERABILITY} | https://github.com/DJBlackEagle/shared-project-tools/security/advisories | The URL to the vulnerability. |
| {TPL^URL_NEW_VULNERABILITY} | https://github.com/DJBlackEagle/shared-project-tools/security/advisories/new | The URL of creating a new vulnerability. |
| {TPL^PACKAGE_NAME} | shared-project-tools | Package name of this project. |
| {TPL^PACKAGE_FULLNAME} | @djblackeagle/shared-project-tools | The full package name of this project. |
| {TPL^PACKAGE_SCOPE} | @djblackeagle/shared-project-tools | The full package name of this project. |
| {TPL^PACKAGE_FULLNAME_MD_LINK} | djblackeagleshared-project-tools | The full package name of this project. |
| {TPL^ASSIGNEE_ISSUE} | DJBlackEagle | The default assignee for new issues. It's stays in the issue template files. |
| {TPL^ASSIGNEE_DEPENDABOT} | DJBlackEagle | The default assignee, then the dependabot makes a pull request. |
| {TPL^EMAIL_COD} | test@localhost.local | The e-mail address in 'Code of Conduct'. |
| {TPL^EMAIL_OWNER} | test@localhost.local | The e-mail address of the owner of this project and repository. |
| {TPL^USER_CODE_OWNER} | @DJBlackEagle | The 'Code Owner' of the repository (full). |
