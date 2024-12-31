# uni-packages
The official packages repo for The `uni` Package Manager

## Adding to `uni`
If it's not already there, use:
```bash
uni add-repo https://github.com/neoapps-dev/uni-packages.git
```
or,
```bash
uni init-repo
```

and thats it!

## Submitting packages to `uni-packages`
Simple Fork this repo, and add a JSON file with this structure:
```json
{
    "repo": "https://github.com/user/package.git",
    "name": "package-name",
    "version": "1.0.0",
    "maintainer": "You",
    "description": "Package description",
    "license": "MIT",
    "dependencies": [],
    "tags": []
}
```
Valid inputs for "license" are:
- MIT
- GPLv3
- GPLv2
- GPLv1
- LGPL
- AGPL
- NONE
