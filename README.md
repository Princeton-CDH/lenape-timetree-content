# Lunaapahkiing Princeton Timetree

[![CC BY 4.0][cc-by-shield]][cc-by] [![Hugo](https://img.shields.io/badge/hugo-0.117-blue.svg)](https://gohugo.io) ![Node version](https://img.shields.io/badge/node-18-blue)

This repository includes text and media content for the CDH-sponsored [Lunaapahkiing Princeton Timetree](https://cdh.princeton.edu/projects/lenape-timetree/) research project.
It uses a custom Hugo theme, available at [Princeton-CDH/lenape-timetree](https://github.com/Princeton-CDH/lenape-timetree).

Note: this project was originally developed in a single git repository; in September 2023 the repository was split out to separate content and code to simplify maintenance and ownership. An archive of the original git repository with the combined history up to that point is available at [Princeton-CDH/lenape-timetree-archive](https://github.com/Princeton-CDH/lenape-timetree-archive).

* * * 

All factual data included this project is [Public Domain](http://creativecommons.org/publicdomain/mark/1.0/). Site content is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

All images are used with permission or available in the public domain.

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg


## Developer + contributor setup instructions

For instructions on editing site content, refer to [CONTRIBUTING](CONTRIBUTING.md).
Local setup is not required for content editing.

### Hugo setup

To set the site up locally for development or content editing,
first follow the [instructions to install Hugo](https://gohugo.io/installation/).
You can check that Hugo is installed with:

```sh
hugo version
```

This should result in output something like this:

> hugo v0.101.0+extended darwin/amd64 BuildDate=unknown

Make sure the version you installed is at least as new as the version shown in the Hugo badge at the top of the project readme (this file).

Once hugo is installed, you'll need to install the javascript dependencies that are used to compile the site's javascript and scss resource files. To check if you have node installed:

```sh
node --version
```

This should output a version string that is at least as new as the version shown in the node badge at the top of this file. To install dependencies, run npm in the project's root directory:

```sh
npm install
```

If the install completes without errors, you're ready to run the site locally.

### Serving locally

To run a development server with auto-reload:

```sh
hugo server
```

You should see some debug output, followed by:

> Web Server is available at http://localhost:1313/ (bind address 127.0.0.1)
> Press Ctrl+C to stop

Open a web browser to the above address to see a local version of the site. When you make changes and save files locally, hugo will automatically refresh the page.

