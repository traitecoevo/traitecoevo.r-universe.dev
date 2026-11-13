R-universe Repo for Traitecoevo

`packages.json` lists the R packages that [R-universe](https://traitecoevo.r-universe.dev) builds for the traitecoevo organisation. Each entry gives the package name (as in its `DESCRIPTION`, which can differ from the repository name) and the repository URL.

Install any of them with:

```r
install.packages("austraits", repos = c("https://traitecoevo.r-universe.dev", "https://cloud.r-project.org"))
```

When you add a package here, also add or update its card on the front page, [traitecoevo.github.io](https://traitecoevo.github.io) (source: [traitecoevo/traitecoevo.github.io](https://github.com/traitecoevo/traitecoevo.github.io)), with `universe: true`.
