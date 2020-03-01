# Resume

This is my professional resume, made with [JSON Resume](http://jsonresume.org/), using my custom theme, [jsonresume-theme-samk](https://github.com/samkasman/jsonresume-theme-samk).

For some reason, you need to install `resume-cli` locally and run that via `node`, instead of using the `resume` command from the global package like you're supposed to.

So, install dependencies:
`npm install`

Now, use the local version of `resume-cli` via `node` to run the export using a theme.

`pdf`: `node node_modules/resume-cli export --theme=samk resume.pdf`
`html`: `node node_modules/resume-cli export --theme=samk resume.html`
