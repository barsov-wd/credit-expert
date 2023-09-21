DIRECTORY MAIN STRUCTURE
-------------------

```
dist               contains finished project and pages
    blokcs/                 
        header/    contains html and css, min.css files for each block
    css/           contains common .css, .min.css
    fonts/         contains fonts for project in .woff, .woff2
    img/           contains compressed images
    js/            contains min.js files
    libs/          contains all libraries

gulp
    config         contains paths, info about plugins
    tasks          contains all tasks for project
 
node_modules       contains node modules (library root)

src
    blokcs/        contains blocks for import in files in / 
        header/    contains html and scss files for each block
    fonts/         contains fonts for project in .ttf
    img/           contains images in all format
    js/            contains js files, all files are imported into app.js in this folder
    libs/          contains all libraries that are connected in files for easy upload to the site
    scss/          contains common scss files to import, and style.scss into which all files from the blocks folder are imported    
```

<hr>

DEVELOPMENT ENVIRONMENT
-------------------
We use gulp for development. And to deploy project on local machine you need follow steps:

1. Copy project to local machine:
```
git clone
```
 
2. Load node modules:
```
npm i
```
3. Start gulp:
```
gulp --build
```
<hr>

GIT
---
We create a branch according to its name. Full example to create new branch from `dev`:
```
git checkout -b branch_name
```
