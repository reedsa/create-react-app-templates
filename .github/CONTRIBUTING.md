# Contributing to create-react-app-templates

Want to add a content or a new template to the list? We appreciate any contributions to this repository.

## Adding a Template

We are happy to review additional templates to add into this repository. New templates should reside in a folder under [templates](../templates) and contain the necessary files outlined below. To have your template reviewed by a maintainer, please open a pull request and fill out the [pull request template](./PULL_REQUEST_TEMPLATE) provided.

## Template Folder Structure

All templates are required to start with the default template. Please name your template appropriately to encapsulate the features it provides as best as possible.

* `.template.dependencies.json` is used by the custom react-scripts to generate a `package.json` file in the output.
> The template can contain standard `package.json` definitions for `dependencies`, `devDependencies`, `scripts`, and `lint-staged`
* `public` folder has assets including the `index.html`, `favicon.ico` and other files that should not be processed by Webpack.
* `src` folder contains all the JavaScript for your React app.
* `README.md` is necessary to describe how to run the app and what features it contains.
* `gitignore` can be provided to ignore certain files by default.
> Note that the `gitignore` excludes the dot `.` to accommodate a workaround with npm processes. See [this issue](https://github.com/npm/npm/issues/1862) for more information.
