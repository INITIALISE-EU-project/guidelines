# INITIALISE EU Project: guidelines

<img src="img/logo.jpeg" alt="Logo" width="50%"/>


## Automated build

Edit the Rmd files for content, and commit. The website should render
automatically. You can view the progress at [Github Actions](https://github.com/INITIALISE-EU-project/guidelines/actions).

## Rendering the book

You can edit this website via [Github](https://github.com/INITIALISE-EU-project/guidelines).

1. Clone the repository

2. Edit the files

3. Generate and view the book locally in R with:

```{r serve}
bookdown::serve_book()
```

You can render the book locally in R with:

```{r render}
bookdown::render_book()
``` 

4. Commit and push your changes to Github.


Automation for the process can be added.

