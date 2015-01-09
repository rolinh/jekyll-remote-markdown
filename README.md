# Jekyll-remote-markdown - Remote markdown file plugin for Jekyll

This [Jekyll](http://jekyllrb.com/) plugin allows you to use remote markdown
files content using a [Liquid](http://liquidmarkup.org/) tag in your local
markdown file.

## Usage

To install this plugin, simply drop the `remote_markdown.rb` file into the
`_plugins` folder at the root of your Jekyll site (create the folder if it does
not yet exist). The file will be loaded before Jekyll generates your site.

To use it, simply use the `remote_markdown` tag in your local markdown file,
like this example:

```Markdown
<!-- load remote readme file from github -->
{% remote_markdown https://raw.githubusercontent.com/Rolinh/jekyll-remote-markdown/master/README.md %}
```
