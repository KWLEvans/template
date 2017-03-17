# App Name

Catchy tagline

**An app by Keith Evans**

More in depth description paragraph.

## Installation

Requires **npm** and **bower** installed in order to run.

Step 1: **Clone this repository to your local computer**

```console
git clone [url]
```

Step 2: **Install all development and production dependencies from the project root directory**

```console
npm install
```
```
bower install
```

Step 3: **Create a file called `.env` in your root directory and export your API key as `apiKey`**

```js
exports.apiKey = "YOUR KEY HERE";
```

Step 4: **Use _gulp_ to build compile the app**

```console
gulp build
```

**Note:** You can create a minified production build of the app by adding the `--production` tag

```console
gulp build --production
```

Step 5: **Use _Browser Sync_ to run a local server instance**

```console
gulp serve
```

## Planning

1. Configuration/dependencies
  * This should include ALL dependencies.
  * It should also include WHERE they are defined and used in the project
  * It could include a short description of what each does for you

2. Specs
  * Spec 1: Description, input, output.
  * Spec 2: Description, input, output.

3. Integration
  * Initial routes or index pages with all dependencies in Controller/index.html head
  * Template/html page for ...
  * Template/html page for ...
  * Template/html page for ... (one for each route/integrated user story)
  * Display...
  * Integrate feature that...

4. UX/UI
  * Include and modify bootstrap/materialize/Sass etc.
  * Develop custom style

5. Polish
  * Refactor minor portion of...
  * Delete unused...
  * Make README awesome

## Known Bugs



## License

MIT License. Copyright 2017 Keith Evans
