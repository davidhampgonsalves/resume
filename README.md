This my resume in markdown format which lets me version, style and generate html and pdf formats using https://github.com/c0bra/markdown-resume-js.

##setup
* first: npm install 
* second: use the css files here to overwrite the core ones at node_modules/markdown-resume/assets/css	

##generate 
```shell
node node_modules/markdown-resume/bin/md2resume resume.md
node node_modules/markdown-resume/bin/md2resume --pdf resume.md
```