# Senior Frontend Developer Task

Task instructions will be provided separately. Here are a few useful things in order to run the project.

## Running local dev server

Ensure you have a recent version of node.js installed. Then run:

`npx @11ty/eleventy --serve`

(this will also install dependencies the first time it is run)

## General information

### HTML

Lives in the `index.njk` file. This uses the [Nunjucks templating language](https://mozilla.github.io/nunjucks/templating.html) which is very similar to other templating languages such as Jinja. An example of how to use this is provided.

### CSS

Lives in `public/styles.css`.

### JavaScript

Lives in `public/scripts.js`.

### Other assets

You will also find icons and fonts in the `/public` folder.

### Data

The data is provided at `_data/models.js`. Instructions on how to access this are provided in the `index.njk` file.
