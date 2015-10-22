This my resume in markdown format which lets me version, style and generate html and pdf formats using https://github.com/c0bra/markdown-resume-js. The current style supports printing and mobile devices.

##Install
1. Install [markdown-resume](https://github.com/there4/markdown-resume))
1. Remove existing core css files in `node_modules/markdown-resume/assets/css` and move our `resume.css` into place.

```
npm install
rm -f node_modules/markdown-resume/assets/css/resume.css
rm -f node_modules/markdown-resume/assets/css/screen.css
cp resume.css node_modules/markdown-resume/assets/css/
```
__to generate PDF's you'll also need to install: [wkhtmltopdf](https://github.com/pdfkit/pdfkit/wiki/Installing-WKHTMLTOPDF)__.


##Generate
```shell
node node_modules/markdown-resume/bin/md2resume resume.md
node node_modules/markdown-resume/bin/md2resume --pdf resume.md
```
