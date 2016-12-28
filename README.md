# Legacy homebrew tap for mongodb26

As of commit
[ffd1bac](https://github.com/Homebrew/homebrew-versions/commit/ffd1baca844f6af6771e20760d65a73ca2c4bdb7),
homebrew-versions no longer supports mongodb26. This tap provides the original mongodb26 formula
for users who may need it.

If you had an existing mongodb26 installation working with brew but has since been
broken because of its removal, you can simply tap this repo to fix your install -

```
% brew tap carymrobbins/mongodb26
```

If you do not have it installed already, after tapping the repo you will then need
to install it -

```
% brew install mongodb26
```
