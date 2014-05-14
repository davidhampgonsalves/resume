This my resume in markdown format which lets me version, style and generate html and pdf formats using https://github.com/c0bra/markdown-resume-js. The current style supports printing and mobile devices.

##setup
* first: npm install (which installs [markdown-resume](https://github.com/there4/markdown-resume))
* second: use the css files in the root directory to overwrite the core ones at node_modules/markdown-resume/assets/css

__to generate PDF's you'll also need to install: [wkhtmltopdf](https://github.com/pdfkit/pdfkit/wiki/Installing-WKHTMLTOPDF)__.

##generate
```shell
node node_modules/markdown-resume/bin/md2resume resume.md
node node_modules/markdown-resume/bin/md2resume --pdf resume.md
```