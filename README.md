# Climate changes data analysis with R language

Paul-Markus Orav and Withee Poositasai

Data Analytics in R 2022, Tallinn University

**View [online notebook](https://th1nkk1d.github.io/r-climate-analysis)**

## Project structure

- `src` contain [RMarkdown](https://rmarkdown.rstudio.com) source code and related dataset.
- `.github` contain [GitHub Action](https://docs.github.com/en/actions)'s workflow file which used to render RMarkdown to HTML file and deploy to [Github Pages](https://pages.github.com) autometically when there is a new commit. Workflow history and status can be tracked from the [Actions tab](https://github.com/Th1nkK1D/r-climate-analysis/actions). The workflow contain:
  - [r-lib actions](https://github.com/r-lib/actions) to render RMarkdown
  - [Github Pages deploy action](https://github.com/JamesIves/github-pages-deploy-action)
- `renv`, `.Rprofile`, and `renv.lock` are from [renv](https://rstudio.github.io/renv/articles/renv.html) which used to manage library dependencies. It's required by r-lib actions in the workflow but we didn't use it in RMarkdown to not over-complicate the work.
