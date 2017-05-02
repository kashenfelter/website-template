# website-template

The [gh-pages](https://github.com/javaee/website-template/tree/gh-pages) branch of this repo contains all the initial assets for a simple website.

* Clone your project repo

:warning: **Make sure the master branch of your project contains both CONTRIBUTING.md** (see [here](https://github.com/javaee/website-template/blob/gh-pages/CONTRIBUTING.md)) and **LICENSE.md** (see [here](https://github.com/javaee/website-template/blob/gh-pages/LICENSE.md) for the standard GF GPVv2/CDDL/CPE).

* Create the orphan _gh-pages_ branch that will host your site

```bash
git checkout --orphan gh-pages
```

* You might want to delete unnecessary files (but do **keep CONTRIBUTING.MD and LICENSE.md in both branches!**)

```bash
git rm --cached -r stuff_to_delete
```

* Grab the initial assets from this repo [_gh-pages_](https://github.com/javaee/website-template/tree/gh-pages) branch and push them to your repo _gh-pages_ branch.
```bash
git add *
git commit
git push --set-upstream origin gh-pages  
```

* Configure your website, edit README.md (the main page) and _config.yml which contains project specific values (project name, repo URL...)

* Test your site (check the setting tabs to check the site build status and URL).
