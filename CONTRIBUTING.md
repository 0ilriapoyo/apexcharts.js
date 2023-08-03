# Contributing

To contribute to `apexcharts.js`, fork the repository and clone it to your machine. [See this GitHub help page for what forking and cloning means](https://help.github.com/articles/fork-a-repo/)

## Setup packages

Install this package's dependencies with `npm`:

```sh
npm install
```

## Build

Run the following to build this library and watch its source files for changes:

```sh
npm run dev
```

You will now have a fully functioning local build of this library ready to be used. **Leave the `start` script running**, and continue with a new Terminal/shell window.

## Work on a fix or feature

To work on a fix or feature and be able to view changes, use samples included, or start a new project with modified Apexcharts as a dependency.

### View included samples

The project includes many samples which can be used as a quick start for working on contributions.

Start an HTTP server with the Apexchart root directory set as a base path to run them. A lightweight HTTP server, like [http-server](https://www.npmjs.com/package/http-server), can be used.

Samples are located under `/samples` path, like `/samples/vanilla-js/timelines/simple.html`.

To preview changes, have a [Build](#build) process running. After a change in Apexcharts source code, wait a moment for a build to complete and refresh the browser (command + shift + r).

## Add tests for your changes

As of now, we have very less tests, and from now on, would like to pay extra attention to it. It would be great if the changes you did could be tested somehow. Our tests live inside the `tests` directory, and they can be run with the following command:

```sh
npm run test
```

## Send your changes back to us! :revolving_hearts:

We'd love for you to contribute your changes back to `apexcharts.js`! To do that, it would be great if you could commit your changes to a separate feature branch and open a Pull Request for those changes.

Point your feature branch to use the `main` branch as the base of this PR. The exact commands used depends on how you've setup your local git copy, but the flow could look like this:

```sh
# Inside your own copy of `apexcharts.js` package...
git checkout --branch feature/branch-name-here upstream/main
# Then hack away, and commit your changes:
git add -A
git commit -m "Few words about the changes I did"
# Push your local changes back to your fork
git push --set-upstream origin feature/branch-name-here
```

After these steps, you should be able to create a new Pull Request for this repository. If you hit any issues following these instructions, please open an issue and we'll see if we can improve these instructions even further.
