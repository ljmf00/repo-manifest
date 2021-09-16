# Repositories manifest

This collection of repositories represents the projects I use, maintain or
created. To easily fetch them, I use
[git-repo](https://gerrit.googlesource.com/git-repo/) from Google.

## Fetch

To fetch them run:

```bash
repo init -u git@github.com:ljmf00/repo-manifest.git -b master
```

If you want to fetch only a certain group, run:

```bash
repo init -u git@github.com:ljmf00/repo-manifest.git -b master -g dlang-org
```

## Sync

```bash
repo sync
```
