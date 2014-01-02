Date: 2014-01-02
Title: Markdown note
Slug: markdown
Tags: note,web 

#### Basic
- the block-level HTML element in markdown tag should be seperated by blank line and the start and end of element should not be indented.
- the span-level HTML element has no restriction
- **break line** = end a line with tow spaces and a return
- **Horizontal rules** = -----------

----------

#### Lists
- examples

		- unordered list
		- unordered list
		1. orderred list
		2. orderred list
		4. orderred list

- the actual numbers in list have no effect on HTML output 

----------

#### Code Blocks
- start with one tabs, continute until it reach a line with no indentity
- \`printf()\` will produce a code span `printf()` 
- `, &` will be translated to HTML entity automatically

----------

#### Headers
- examples

		# First Level Header
		## Second Level Header
		### Third Level Header
		###### Sixth Level Header

----------

#### Emphasis
- examples

		- *em*
		- **strong**
		- * em *

- *em*
- **strong**
- \* em *  = \* will be treated as a literal asterisk if it surrounded with space

----------

#### Paragraphs 
- sperated by one or more blank lines

----------

#### Link
- examples
		
		- This is [google](http://google.com "The google link"), an inline link. 
		- This is [reference][ref] reference-style link
		- [ref]: http://google.com "The google link"		
		- auto link = <http://google.com>

- This is [google](http://google.com "THe google link"), an inline link. 
- This is [reference][ref] reference-style link
- **auto link** = <http://google.com>

[ref]: http://google.com "The google link"

----------

#### Images
- examples

		- ![Alt text](/path/to/img.jpg "Optional Title")
		- ![Alt text][id]

