# Resume

This repository contains my constantly maintained resume, made with [JSON Resume](http://jsonresume.org/), using my custom theme, [jsonresume-theme-samk](https://github.com/samkasman/jsonresume-theme-samk).

![Screenshot](https://github.com/samkasman/Resume/blob/master/screenshot.png)

View the exported `pdf` file [here](https://github.com/samkasman/Resume/blob/master/resume.pdf).



### To Export PDF/HTML Files

Install dependencies:
`npm install`

Now, use the local version of `resume-cli` via `node` to run the export using a theme.

`pdf`: `node node_modules/resume-cli export --theme=samk resume.pdf`

`html`: `node node_modules/resume-cli export --theme=samk resume.html`
