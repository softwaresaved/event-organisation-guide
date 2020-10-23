# Style
We detail language and markup considerations for working with the EOG.

## Titles
Document titles should be in [title case](https://grammar.yourdictionary.com/capitalization/rules-for-capitalization-in-titles.html). Headings and subheadings should be in [sentence case](https://proofreadmyessay.co.uk/writing-tips/title-case-sentence-case-headings/).

## Bulleted lists
For bullet pointed lists, use dash ('-') to denote the list items. Sub-lists should be indented with three spaces. For example:
- list item
   - sub item 1
   - sub item 2
     - sub sub item 2.1
     - sub sub item 2.2
   - sub item 3
  
## Bulleted lists punctuation
If your bulleted lists contain sentence fragments, as a style choice we require capitalisation but no full stop at the end. See [this for reference](https://www.grammarly.com/blog/bullet-points/).

## On links
Look at how links are contructed in different scenarios and copy their usage
- external links (see [external links](https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html#hyperlinks) in the Sphinx documentation), see [introduction](docs/eog/introduction.rst) in the EOG
   - if the same link text is used multiple times in one file then you need to us __ as the target, see [authors](docs/eog/authors.rst) in the EOG
- internal / relative links (see [internal links](https://www.sphinx-doc.org/en/master/usage/restructuredtext/roles.html#ref-role) in the Sphinx documentation), see [finance](docs/eog/eps-finance.rst) for other documents or [risk assessment](docs/eog/eps-risk-assessment.rst) for figures in the EOG
