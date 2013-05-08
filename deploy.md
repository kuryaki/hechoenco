To deploy the actual page

> git subtree push --prefix dist origin gh-pages
or
> git push origin `git subtree split --prefix dist master`:gh-pages --force
