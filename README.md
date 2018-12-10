Del/Ins Extension for Python-Markdown
=====================================

Wraps the inline content with `ins` and `del` tags.


Installation
------------
    
    copy mdx_del_ins_markdown_3_0_1.py as a module

Usage
-----

    >>> import markdown
    >>> from mdx_del_ins_markdown_3_0_1 import DelInsExtension

    >>> src = """This is ++added content++ and this is ~~deleted content~~""" 
    >>> html = markdown.markdown(src, extensions=[DelInsExtension()])
    >>> print(html)
    <p>This is <ins>added content</ins> and this is <del>deleted content</del>
    </p>


Dependencies
------------

* [Markdown 3.0.1](http://www.freewisdom.org/projects/python-markdown/)


Copyright
---------

2011, 2012, 2018 [The active archives contributors](http://activearchives.org/)
All rights reserved.

This software is released under the modified BSD License. 
See LICENSE.md for details.
