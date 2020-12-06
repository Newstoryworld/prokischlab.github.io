# Template of Prokischlab web page

This is a template (and tutorial) for creating your website with R Markdown in minutes.

The official document from RStudio can be found [here](http://rmarkdown.rstudio.com/rmarkdown_websites.html).

## Procedure

### Prerequisites

- Make sure that you have the latest versions of R, RStudio and package rmarkdown. I had problems of encoding because of that. 

- Make sure that you have enabled Git in RStudio. More information can be found [there](https://privefl.github.io/advr38book/good-practices.html#git).

- You need a GitHub account.

### Make the first version of your website

- Fork this repo (top-right) and rename it to be 'YOURGITHUB.github.io' (in Settings of your brand new repo).

- Get the link from cloning the repo. Use the green button "Clone" and make sure you use SSH, not HTTPS. Then, go to RStudio, create a New Project > Version Control > Git and copy this link. You have cloned your new repo as an R project.

- Build the website by running `rmarkdown::render_site(encoding = "UTF-8")` or just `Ctrl/Cmd + Shift + B`.

- Commit and push everything from RStudio.

- Go see your new website at https://prokischlab.github.io/index.html

### Change the content of your website

- Modify `_site.yml`, `index.Rmd`, `about.Rmd`, `cv.Rmd` and `CV.pdf` with your own content. 
- Build your website again. At any moment, you can preview your website locally, by rendering your site and viewing any of your local html file in your Web Browser. 

- Commit and push everything from RStudio.

- Go see your new website with your own content at https://YOURGITHUB.github.io/.


