# markdown2hub
converts Markdown to Hub XML. This Readme can be used for testing, too. 

## usage

```bash
$ saxon -xsl:xsl/markdown2hub.xsl -it:main href=file:/home/markdown2hub/README.md -o:file.hub.xml
```
## support

We support Markdown in the CommonMark flavour. Currently, the following elements are implemented:

* section hierarchy
* tables
* lists
** nested lists
** enumerated and itemized lists
** numbering: 1., 1.1 etc
* images
* program listings
* blockquotes
* bold, italic
* hyperlinks

## maintainer, license

 maintainer | license
--- | ---
[@mkraetke](https://github.com/mkraetke)   | FreeBSD
