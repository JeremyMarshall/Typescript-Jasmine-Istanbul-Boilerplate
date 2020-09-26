# Typescript-Jasmine-Istanbul-Boilerplate

[![codecov](https://codecov.io/gh/JeremyMarshall/Typescript-Jasmine-Istanbul-Boilerplate/branch/master/graph/badge.svg)](https://codecov.io/gh/JeremyMarshall/Typescript-Jasmine-Istanbul-Boilerplate)

An example node project to produce coverage of TypeScript sources to [codecov.io](https://codecov.io) using:

- Jasmine
- nyc (Istanbul)
- tsc
- npm scripts

The coverage report shows the typescript (rather than transpiled) code. That is, sourcemaps are properly handled.

    $ npm install -g codecov
    $ npm run coverage
    $ npm run codecov
    $ codecov
        
Or look at the [travis-ci.org](https://travis-ci.org/github/JeremyMarshall/Typescript-Jasmine-Istanbul-Boilerplate) plan
[travis.yml](./.travis.yml)