# Run git flow init
```
git flow init
```

Which branch should be used for bringing forth production releases?
   - main
Branch name for production releases: [main]
Branch name for "next release" development: [develop] dev

How to name your supporting branch prefixes?\
Feature branches? [feature/] feat\
Release branches? [release/]\
Hotfix branches? [hotfix/]\
Support branches? [support/]\
Version tag prefix? []\


**Check what branches available**
```
git branch -a
```

**Check what tags available**
```
git tag -l
```

**Document initialization**
```
git flow feature start create-guidline-for-git-flow-initialization
```

```
Switched to a new branch 'featcreate-guidline-for-git-flow-initialization'

Summary of actions:
- A new branch 'featcreate-guidline-for-git-flow-initialization' was created, based on 'dev'
- You are now on branch 'featcreate-guidline-for-git-flow-initialization'

Now, start committing on your feature. When done, use:

     git flow feature finish create-guidline-for-git-flow-initialization
```
**Add - Commit - Push**
```
git add .
git commit -m "implement guidline to git flow initialization"
git push
```

**Finish feature branch**
```
git flow feature finish create-guidline-for-git-flow-initialization
```

```
Switched to branch 'dev'
Merge made by the 'ort' strategy.
 Initialize.md | 55 +++++++++++++++++++++++++++++++++++++++++++++++++++++++
 1 file changed, 55 insertions(+)
 create mode 100644 Initialize.md
Deleted branch featcreate-guidline-for-git-flow-initialization (was 830cb71).

Summary of actions:
- The feature branch 'featcreate-guidline-for-git-flow-initialization' was merged into 'dev'
- Feature branch 'featcreate-guidline-for-git-flow-initialization' has been removed
- You are now on branch 'dev'
```
