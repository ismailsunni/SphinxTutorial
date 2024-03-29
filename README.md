Restructured Text Primer
========================

Basic markup
------------

Bold and Italics
................

This is how you write **bold**.

This is how you write *italics*.

This is how you do a hyperlink: http://google.com

For RST reference: http://docutils.sourceforge.net/rst.html

Bullets
.......

A bullet list:

* Item foo
* Item bar

A numbered list:

#. Item one
#. Item two

Tables
......

Here is how to make a simple table:

+--------------------+--------------------------+
| **Name**           | **Job**                  |
+--------------------+--------------------------+
| Tim                | CEO of Microsoft         |
+--------------------+--------------------------+

This is how you show a program listing or some preformatted text::

    shrub:SphinxTutorial timlinux$ ls -lah
    total 8
    drwxr-xr-x   4 timlinux  staff   136B Apr  8 09:55 .
    drwxr-xr-x  19 timlinux  staff   646B Apr  8 09:27 ..
    drwxr-xr-x  14 timlinux  staff   476B Apr  8 10:00 .git
    -rw-r--r--   1 timlinux  staff   206B Apr  8 09:59 README.rst


How to install git on Ubuntu::

    sudo apt-get install git
