# Vacademy developer docs

Published by Mintlify at https://vacademy-platform.mintlify.site/.

**Source of truth:** [`vacademy_platform/vacademy-docs`](https://github.com/Vacademy-io/vacademy_platform/tree/main/vacademy-docs),
next to the API code. Edit the docs there, then copy them here:

```bash
rsync -a --delete --exclude .git --exclude .mintignore --exclude README.md \
  ../vacademy_platform/vacademy-docs/ ./
git add -A && git commit -m "docs: sync from vacademy_platform" && git push
```
