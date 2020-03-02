# Resume

This repository contains my constantly maintained resume, built with [JSON Resume](http://jsonresume.org/) using my [custom theme](https://github.com/samkasman/jsonresume-theme-samk)

![Screenshot](https://github.com/samkasman/Resume/blob/master/screenshot.png)

To View the full **PDF** version, click [here](https://github.com/samkasman/Resume/blob/master/resume.pdf).

### To Install:

- `git clone` this repository
- Install dependencies: `npm install`

#### To Update Resume Content:

- Edit `resume.json` file

#### To Export PDF/HTML Files:

Use the local version of `resume-cli` we just installed, via `node`, to run the export using the theme.

- **PDF**: `node node_modules/resume-cli export --theme=samk resume.pdf`
- **HTML**: `node node_modules/resume-cli export --theme=samk resume.html`

#### Check for Theme Updates

- `npm update`


### License

Available under [the MIT license](https://github.com/samkasman/Resume/blob/master/LICENSE).
