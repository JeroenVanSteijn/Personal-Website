# Jeroen van Steijn personal website

[![Build Status](https://travis-ci.org/jeroenvansteijn/Personal-Website.svg?branch=master)](https://travis-ci.org/jeroenvansteijn/Personal-Website)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Jeroen van Steijn's personal website built in [Hugo](https://gohugo.io).

## Development

For development, run `hugo server`. The development environment is now accessable on `localhost:1313`.

You can also just use `open http://localhost:1313 && hugo server`, but not all systems support this.

## Production

As Hugo is a static website builder, you can just host the website on any hosting service. To build the static files, run `rm -rf build && hugo -d build -b [url]`.

I run `hugo -d build -b https://jeroenvansteijn.nl`.

Now upload the contents of the `build` folder to the webhost and you're done.

## Make

The `make` command can also be used:

| Command | Functionality |
| ------- | ------------- |
| `make server` | Runs hugo server |
| `make dev` | Runs hugo server and opens `localhost:1313` in browser |
| `make build` | Runs hugo build command as explained under the "production" header |

### License

MIT

### TODO

- Add info on topics I find interesting
- Add grades (in a fun way)
- Add expertise on Phonegap/Ionic, Php frameworks like idiorm and paris, Server management, API's and websockets, Chatbots (Rasa) etc.