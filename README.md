# vercel-reset-test

# Steps to Reproduce

1. `main/master` = preview branch.
2. `production` = production branch.

To make a "production" deployment, you need to attempt the following in the `production` branch:

```
git reset --hard master; git push --force
```

Does it create a deployment?
