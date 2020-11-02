# [petewilliams.space](http://petewilliams.space)
A simple Bootstrap website built using npm + gulp to get by.

Based on [Start Bootstrap - Resume](https://startbootstrap.com/template-overviews/resume/) by David Miller under the [MIT](https://github.com/BlackrockDigital/startbootstrap-resume/blob/gh-pages/LICENSE) license.

### Build

* `npm install` - builds node_modules folder, compiles scss, minifies `resume.css`/`resume.js`
* `npm start` - Runs a node server on 3000, browserSync will hot update any changes. `gulpfile.js` currently drives this called by `npm` from `package.json`.

`/public` contains the deployed site. Currently the build process does not deploy to this folder `//TODO`

### Hosting
[![Netlify Status](https://api.netlify.com/api/v1/badges/ceb8718d-b523-4521-a00c-b670bfc6c16f/deploy-status)](https://app.netlify.com/sites/petewilliamsdotspace/deploys)  

Currently manually deployed to [netlify](https://netlify.com) via the `netlify deploy` CLI. 


Copyright 2020 Pete Williams. Code released under the [MIT](https://opensource.org/licenses/MIT) license.
