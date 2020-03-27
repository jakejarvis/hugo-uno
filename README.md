# Hugo Uno

[![Netlify Status](https://api.netlify.com/api/v1/badges/0e14eafe-8a66-4816-97b2-3db19fc1048c/deploy-status)](https://app.netlify.com/sites/hugo-uno/deploys)

## Features

- [Hugo (extended)](https://github.com/gohugoio/hugo) via NPM
- _Very_ barebones theme (based on [Vimux/blank](https://github.com/Vimux/blank))
- Netlify defaults ([better alias redirects](layouts/index.redirects), [security headers](layouts/index.headers), deploy previews, etc.)
- [SCSS/SASS](assets/sass) → PostCSS & Autoprefixer
- Dozens of embed [shortcodes](layouts/shortcodes)

<p align="center"><img src="https://user-images.githubusercontent.com/1703673/77758048-b2cc3c80-7008-11ea-864a-f799b3e22509.png" width="160"></p>

## Usage

No need to download Hugo yourself! Just run `npm install` from this directory and the correct version for your OS will be fetched.

To start live server: `npm start` and open [http://localhost:1313](http://localhost:1313).

To build static files: `npm run build` and upload `./public`.

## Deploy to Netlify

You can deploy directly to Netlify using this button:

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/jakejarvis/hugo-uno)

## License

This project is distributed under the [MIT license](LICENSE.md).
