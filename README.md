# lightning-talk

* **[Latest release](https://github.com/georgejkaye/lightning-talk/releases/latest)**
## Setting up

This project uses *submodules* to share diagrams and things between repos.
To make sure you have them all pulled, do this to initialise them:

```sh
git submodule update --init
```

Occasionally you might want to do this to update the submodules:

```sh
git submodule foreach git pull origin main
```

## GitHub Actions

Every time you push a commit starting with `[build]`, it will be compiled and put in a release.

