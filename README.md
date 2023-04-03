# pz-lsst-inkind-doc 

#### Central repository for documentation related to Section S4 of the BRA-LIN in-kind contribution program. 

The contents of this repository in published as github pages with the Read the Docs theme [here](https://linea-it.github.io/pz-lsst-inkind-doc/).

Links to technical documentation and user guides will be added to that page during the project excecution as soon as they become available, so it is to be considered a live document.  

**Contribution Lead:** Julia Gschwend ([julia@linea.org.br](mailto:julia@linea.org.br))  


## How to contribute

This documentation repository uses **mkdocs** to build the HTML pages.

To install mkdocs: 

``` 
pip install mkdocs
``` 
Open a new git branch and make your changes there. After editing the text, to see the changes locally, go to the directory with the `mkdocs.yml` file and run: 

```
mksocs serve
```

The prompt will return a local address (e.g.: http://127.0.0.1:8000/). Copy and paste this address in your browser to navigate through the pages. 

After finishing with the text editing, open a pull request on github and, after aproved, merge the new branch to the main branch. 


To update the contents on GitHub pages, run:  


```
git checkout main 
git pull 
mkdocs gh-deploy 
``` 


