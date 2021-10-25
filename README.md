![Deployment Pipeline](https://github.com/holgerimbery/online_resume/actions/workflows/main.yml/badge.svg)

## Demo
see what you will get before you fork.  

[demo site](https://holgerimbery.github.io/online_resume/)

Online-resume is an easy-to-handle online resume builder, built on top of gh-pages, mkdocs material and some magic.

Features:  

* mkdocs based, to edit everything in markdown
* material theme, to make it look awesome
* incl. github action to automatically deploy to github pages, just edit, the github actions works then for you in the background
* incl. print site plugin to create pdf´s with browsers print functionality, as some need a printed one (come on, we are in the 202x years, paper is 19xx)
* incl. pdf file generation, up upload in recruiting platforms  

## Setup
* clone repository, or create a new repro (your_name.github.io) and upload the content of the zip, you can download by clicking on "code".
* adjust "mkdocs.yml" to your needs (links, repository name, etc.)
* edit docs/index.md, to make it your resume
* edit .github/workflow/main.yml to adjust to your needs (line 22)
* activate *Github actions* and wait for the first successful run. The github action will create a branch "gh-pages" with your static website.
* select "gh-pages" under settings/pages in your repository to make the resume available under "https://yourname.github.io"  

## own domain
* place a text file with the name "CNAME" with the content "your.domain.ltd" ( without "" ) in the folder docs/
* Follow the instruction under "custom domain" select under settings/pages in your repository  
 

# Credits
[mkdocs material](https://squidfunk.github.io/mkdocs-material/)  
[mkdocs print site plugin](https://timvink.github.io/mkdocs-print-site-plugin/options.html)

## Contributions are welcome
please feel free to submit a pull request