# The Event Organisation Guide (EOG)
The EOG is a guide dedicated to help the Software Sustainaiblity Institute share the way they it organises events.

The guide welcomes contributions from others. We are are interested in what people have actually done/tried rather than theoretical considerations. Although suggesting experiences or even theoretical considerations is useful for us to include as references. 

## Technical matters
EOG is a [sphinx project](www.sphinx-doc.org) and we host the EOG on [Read the Docs](https://event-organisation-guide.readthedocs.io/)

## Getting setup
[Install sphinx](http://www.sphinx-doc.org/en/master/usage/installation.html) if it is not already installed.

Clone the git repo locally.

`git clone https://github.com/softwaresaved/event-organisation-guide.git`

### setting up sphinx readthedocs theme link
This is needed so you can build and test the documentation locally.

`git clone https://github.com/readthedocs/sphinx_rtd_theme.git`

`cd event-organisation-guide/docs/_themes`

`ln -s ../../../sphinx_rtd_theme/sphinx_rtd_theme sphinx_rtd_theme`

`cd ..`

## install dependencies

`pip install sphinx`

## make

`make html`

## view

Open the file `./_build/html/index.html` in a web-browser.

## note

If you make changes to the .rst files or do a `git pull` to get updates then you need to do a `make clean` before you do a `make html` as otherwise the navigation pages sometimes don't behave or work. 



