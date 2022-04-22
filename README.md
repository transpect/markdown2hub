# markdown2hub
converts Markdown to Hub XML. This Readme can be used for testing, too. 

## usage

```bash
$ saxon -xsl:xsl/markdown2hub.xsl -it:main href=file:/home/markdown2hub/README.md -o:file.hub.xml
```
## support

We support Markdown in the CommonMark flavour. Currently, the following elements are implemented:

### section hierarchy
* lists
* images ![transpect](https://raw.githubusercontent.com/transpect/transpect.github.io/master/icons/favicon-32x32.png)
* **bold**, _italic_
* [hyperlinks](https://github.com/transpect/markdown2hub)
> blockquotes
```
program listings
```
tables |
   --- | 
...    |


