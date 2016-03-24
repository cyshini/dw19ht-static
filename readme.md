# Dw19ht Static

[![devDependency Status](https://david-dm.org/zurb/foundation-zurb-template/dev-status.svg)](https://david-dm.org/zurb/foundation-zurb-template#info=devDependencies)

Static prototype for Dw19ht's blog, with the help of ZURB Template (using Gulp) from [Foundation for Sites](http://foundation.zurb.com/sites). Some great features here:

- Handlebars HTML templates with Panini
- Sass compilation and prefixing
- JavaScript concatenation
- Built-in BrowserSync server
- For production builds:
  - CSS compression
  - JavaScript compression
  - Image compression

## Requirements

To use this template, your computer needs:

- [NodeJS](https://nodejs.org/en/) (0.12 or greater)
- [Git](https://git-scm.com/)

### Setup

To set up the template, first download it with Git:

```bash
git clone https://github.com/cyshini/dw19ht-static projectname
```

Then open the folder in your command line, and install the needed dependencies:

```bash
cd projectname
npm install
bower install
```

Finally, run `npm start` to run Gulp. Your finished site will be created in a folder called `dist`, viewable at this URL:

```
http://localhost:8000
```

To create compressed, production-ready assets, run `npm run build`.
To deploy these assets on a gh-pages branch (for Github Pages hosting), just run `npm run deploy`.
