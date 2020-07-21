# The Software Sustainability Institute's Event Organisation Guide (SSI-EOG)
The SSI-EOG (or EOG for short) is a guide dedicated to the way the Software Sustainaiblity Institute, related individuals and the wider research software community share the way they organises events.

## Contributing
The guide welcomes contributions from others. We are are interested in what people have actually done/tried rather than theoretical considerations.
Please see the the [contributing guidelines](https://github.com/softwaresaved/event-organisation-guide/blob/master/CONTRIBUTING.md) for further information.

## Code of Conduct
We have a [Code of Conduct](https://github.com/softwaresaved/event-organisation-guide/blob/master/CODE_OF_CONDUCT.md), please adhere to this in your interactions on this project.

## Technical matters
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

### Style
Document titles should be in [title case](https://grammar.yourdictionary.com/capitalization/rules-for-capitalization-in-titles.html). Headings and subheadings should be in [sentence case](https://proofreadmyessay.co.uk/writing-tips/title-case-sentence-case-headings/).

For bullet pointed lists, use dash ('-') to denote the list items. Sub-lists should be indented with tabs. For example:
- list item
  - sub item 1
  - sub item 2
    - sub sub item 2.1
     - sub sub item 2.2
  - sub item 3

## License
The EOG material is available under the Creative Commons Attribution-NonCommercial 4.0 Licence. Please see the [human-readable summary](https://creativecommons.org/licenses/by-nc/4.0/) of the CC BY-NC 4.0 and the full [legal text](https://creativecommons.org/licenses/by-nc/4.0/legalcode) for further information.
