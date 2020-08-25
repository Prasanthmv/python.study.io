## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Prasanthmv/python.study.io/edit/gh-pages/docs/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block
 ## 5 Tools to Craft Better Python Code

Writing beautiful Python is harder than it seems.we can use the following tools to make our code presentable and to remove avoidable mistakes.

### 1.Black

Black is a no-compromises Python code reformatter. It will make sure that your code meets the PEP 8 recommendations.
You can get black from pypi using pip3:

`pip3 install --upgrade --user black`

Black has rich options, use black -h to print the help text.

`black -t py38 --check <yourfile>`

To make black fix the file, remove the — check option when running black.

### 2.Eradicate

Eradicate is a handy tool for finding commented out code blocks. You probably don’t need them any more!

You can get eradicate from pypi using pip3:

`pip3 install --upgrade --user eradicate`

Eradicate has few options, use eradicate -h to print the help text.

`eradicate <yourfile>`

Using the option -i will fix your code in-place.


### 3. Coverage

Coverage is the great-granddaddy of Python code analysis.

You can get coverage from pypi using pip3:

`pip3 install --upgrade --user coverage`

Coverage has very many options, here to find the line numbers of unreached code:

     coverage erase # erase previous 
     coverage run --branch <yourfile> # run a branch analysis 
     coverage report -m <yourfile> # create a report

### 4.Pycodestyle

Pycodestyle is an awesome tool for nit-picking your code formatting. It tells you where your code differs from the recommendations in PEP-8. 

You can get pycodestyle from pypi using pip3:

`pip3 install --upgrade --user pycodestyle`      

Pycodestyle has very many options, here to find the line numbers of unreached code:

`pycodestyle --show-source --statistics <yourfile>`

### 5.Pylint

Pylint is the one essential tool in this list.

You can get pylint from pypi using pip3:
`pip3 install --upgrade --user pylint`

Pylint has a huge amount of options. 

`pylint --include-naming-hint=y --load-plugins=pylint.extensions.mccabe,pylint.extensions.redefined_variable_type <yourfile>`



[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Prasanthmv/python.study.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
