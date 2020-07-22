# Technical matters
EOG is a [sphinx project](www.sphinx-doc.org) and we host the EOG on [Read the Docs](https://event-organisation-guide.readthedocs.io/)

## Getting setup
[Install sphinx](http://www.sphinx-doc.org/en/master/usage/installation.html) if it is not already installed.

Clone the git repo locally.

`git clone https://github.com/softwaresaved/event-organisation-guide.git`

### Setting up sphinx readthedocs theme link
This is needed so you can build and test the documentation locally.

`git clone https://github.com/readthedocs/sphinx_rtd_theme.git`

`cd event-organisation-guide/docs/_themes`

`ln -s ../../../sphinx_rtd_theme/sphinx_rtd_theme sphinx_rtd_theme`

`cd ..`

## Install dependencies
`pip install sphinx`

## Make
From the `docs` folder of the project do:

```
make clean
make html
```

## View
Open the file `./_build/html/index.html` in a web-browser.

## Note
If you make changes to the .rst files or do a `git pull` to get updates then you need to do a `make clean` before you do a `make html` as otherwise the navigation pages sometimes don't behave or work. 
