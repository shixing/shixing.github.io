* TOC here
{:toc}

## Write blog using markdown

1. Create a file under `/_post` with name pattern `YYYY-MM-DD-Your-File-Name.md`
2.  Here is the starter for *.md file:

	\-\-\-
	layout: post
	title:  "Your Post Title"
	date:   2014-06-17 00:55:00
	categories: cate1 cate2
	\-\-\-
	* TOC here
	{:toc}

3.  Write your kramdown below the starter
4. The final post will be under `/_site/cate1/cate2/2015/6/17/index.html`
5. About MathJax
	1. Kramdown's both default inline and block equations are surrounded by `$$`. If an equation itself is a paragraph, it's block. Otherwise it's inline. 
	2. A single `\n` doesn't mean newline. You should use a blank line to start a new paragraph. 

## Change of *.html

Every `*.html`, e.g. `dashboard.html`, will finally become `/_site/dashboard/index.html`

## Publish to web

1.`>$ Jekyll build` in Command Line
2.Then push to github.

## Useful Links:

1. [Jekyll Usage](http://jekyllrb.com/docs/usage/)
2. [Jekyll Doc Structure](http://jekyllrb.com/docs/structure/)
3. [Kramdown Syntax CheatSheet](http://daringfireball.net/projects/markdown/dingus)

