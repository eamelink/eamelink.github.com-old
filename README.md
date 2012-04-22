eamelink.nl Jekyll site
=======================

This is the repository for the eamelink.nl website, a Jekyll site hosted by Github Pages.


Usage
=====

Running the site locally
------------------------

You need the following things
 
 * jekyll (gem install jekyll) for generation of pages
 * pygments (easy_install pygments) for syntax highlighting
 * RedCloth (gem install RedCloth) for textile processing
 * watch (gem install watchr) for file monitoring

Run `jekyll --server --auto`

The `--server` option starts a webserver, you can reach it at http://0.0.0.0:4000/

The `--auto` command regenerates the site when a file changes. This needs the `watchr` gem. 

Generating the pygments css
---------------------------

Run `pygmentize -S trac -f html > pygments.css`

Optionally replace `trac` by a different theme.


