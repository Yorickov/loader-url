# page loader

[![Build Status](https://travis-ci.org/Yorickov/loader-url.svg?branch=master)](https://travis-ci.org/Yorickov/loader-url)
[![Maintainability](https://api.codeclimate.com/v1/badges/055c996cec56e5d54631/maintainability)](https://codeclimate.com/github/Yorickov/loader-url/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/055c996cec56e5d54631/test_coverage)](https://codeclimate.com/github/Yorickov/loader-url/test_coverage)

CLI-utility, downloads web page with resourses

*Educational project hexlet.io, Javascript/Back-End, p.3*

## Technologies
- Npm / Babel / ESLint
- Jest
- commander
- axios
- cheerio
- listr

## Feautures
- file system I/O
- nodejs: fs, url, path, etc.
- error handling
- debug
- DOM: basic manipulations
- asynchronous programming: promises, async/await
- HTTP
- test-driven development: mock/stub

## Setup
`make install`

*`npm install -g loader-url`*

## Usage
`$ page-loader --output [path/to/dir] [url]`

## Example
$ page-loader --output /var/tmp https://redmine.org/projects

$ open /var/tmp/redmine-org-projects.html
