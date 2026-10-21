# AI Native Development Practice

Practice and homework repo for AI Dev Tools Zoomcamp.

## Projects

| Project | Location |
| --- | --- |
| Household task & schedule manager | [`household-chore-app`](https://github.com/Robyrogers/household-chore-app) — git submodule |

Each project is its own repository with its own issue tracker. This repo only
records which commit of each project is included.

## Cloning

```bash
git clone --recurse-submodules https://github.com/Robyrogers/ai-native-development-practice.git
```

If you already cloned without submodules:

```bash
git submodule update --init --recursive
```

## Working on a project

Commit inside the project directory, which is its own repository:

```bash
cd household-chore-app
git switch main
# make changes
git commit -am "feat: ..."
git push
```

Then record the new commit in this repo:

```bash
cd ..
git add household-chore-app
git commit -m "chore: bump household-chore-app"
git push
```
