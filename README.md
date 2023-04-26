# INITIALISE EU Project: guidelines

<img src="img/logo.jpeg" alt="Logo" width="50%"/>

The [website](https://initialise-eu-project.github.io/guidelines/) is automatically rendered. Here you find instructions on how to edit the website. 

**Troubleshooting:** Contact Leo Lahti in case of problems.


## Rendering the book

### Option 1: github web browser

Edit the files directly through web browser in [Github](https://github.com/INITIALISE-EU-project/guidelines).

The [website](https://initialise-eu-project.github.io/guidelines/) is automatically rendered from the Rmd files (files ending with `.Rmd`). The chapters order is defined in the file `_bookdown.yml`. Navigate to the file that you want to edit, click on the pen figure around the top right corner of the page (next to the "Raw" and "Blame" buttons), then edit the file and commit the changes (the Commit button at the bottom of the page).

An external server detects the update and renders the website. If the build is successful, it will trigger a new process in [Github Actions](https://github.com/INITIALISE-EU-project/guidelines/actions). It usually takes 1-2 minutes that the changes appear on the [website](https://initialise-eu-project.github.io/guidelines). The changes will not become visible if the build fails. 


### Option 2: command line

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

