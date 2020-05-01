# Website source for _Microsoft Azure 2nd Edition_

To build this site as an owner

## Prerequisites

- Python 3 with pip installed
- `git` client or command line (shown here is command line)


## Install Python libraries

```
pip install mkdocs
pip install mkdocs-material
```

## Modify website docs


Checkout the GitHub repo, e.g., 

```
git chekcout git@github.com:harris-soh-copeland-puca/harris-soh-copeland-puca.github.io.git
```

Change or add docs to the `docs` folder and update the `mkdocs.yml` to reflect the new structure.  See https://www.mkdocs.org/ for instructions.

## Build the site

First, check the site locally,

```
mkdocs serve
```


To build the site, on the command line:

```
mkdocs build
cp -r site/* .
```

## Check in site

```
git add .
git commit -m "Update to site"
git push origin master
```

And you are done!
