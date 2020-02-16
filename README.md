# scripts
Some of my everyday scripts. Maybe some of those are of use to others.

## citagra

Takes a bibtex file as created by Mendeley and outputs the dot file of the
corresponding citation graph. The main purpose of this script is to provide
a quick overview of how papers are connected.

It depends on graphviz, bibtexparser and pdftotext.

## rename-papers

Browsing for papers I often find my download directory filled with cryptic
pdf titles, often just a bunch of numbers.
I browse my papers with dmenu most of the time so I need proper names.
This script tries to fetch the paper names and renames the files accordingly.
If it can't figure out the name, it falls back to an interactive mode.

The script depends on vipe, vim, pdftotext and pdftitle.

