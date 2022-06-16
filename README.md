# minipot-server-configs

## copy-from-git-to-system

```sh
doas -u root -- .scripts/copy-from-git-to-system
```

## git commands

```sh
git fetch --progress --prune --recurse-submodules=no origin
```

```sh
git checkout main
```

```sh
git merge --ff --ff-only refs/remotes/origin/main
```

```sh
git checkout main
```

<!-- git branch -D docs -->
