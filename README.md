# test coverage for  [turf (v3.0.14)](https://github.com/turfjs/turf#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-turf.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-turf) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-turf.svg)](https://travis-ci.org/npmtest/node-npmtest-turf)
#### a JavaScript library for performing geospatial operations with GeoJSON

[![NPM](https://nodei.co/npm/turf.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/turf)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-turf/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-turf/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-turf/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-turf/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-turf/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-turf/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-turf/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-turf/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-turf/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-turf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-turf/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-turf/build/test-report.html](https://npmtest.github.io/node-npmtest-turf/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-turf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-turf/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-turf/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-turf/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-turf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-turf/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-turf/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-turf/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "morganherlocker"
    },
    "bugs": {
        "url": "https://github.com/morganherlocker/turf/issues"
    },
    "dependencies": {
        "turf-along": "^3.0.12",
        "turf-area": "^3.0.12",
        "turf-bbox": "^3.0.12",
        "turf-bbox-polygon": "^3.0.12",
        "turf-bearing": "^3.0.12",
        "turf-bezier": "^3.0.12",
        "turf-buffer": "^3.0.12",
        "turf-center": "^3.0.12",
        "turf-centroid": "^3.0.12",
        "turf-circle": "^3.0.12",
        "turf-collect": "^3.0.12",
        "turf-combine": "^3.0.12",
        "turf-concave": "^3.0.12",
        "turf-convex": "^3.0.12",
        "turf-destination": "^3.0.12",
        "turf-difference": "^3.0.12",
        "turf-distance": "^3.0.12",
        "turf-envelope": "^3.0.12",
        "turf-explode": "^3.0.12",
        "turf-flip": "^3.0.12",
        "turf-helpers": "^3.0.12",
        "turf-hex-grid": "^3.0.12",
        "turf-inside": "^3.0.12",
        "turf-intersect": "^3.0.12",
        "turf-isolines": "^3.0.12",
        "turf-kinks": "^3.0.12",
        "turf-line-distance": "^3.0.12",
        "turf-line-slice": "^3.0.12",
        "turf-meta": "^3.0.12",
        "turf-midpoint": "^3.0.12",
        "turf-nearest": "^3.0.12",
        "turf-planepoint": "^3.0.12",
        "turf-point-grid": "^3.0.12",
        "turf-point-on-line": "^3.0.12",
        "turf-point-on-surface": "^3.0.12",
        "turf-random": "^3.0.12",
        "turf-sample": "^3.0.12",
        "turf-simplify": "^3.0.12",
        "turf-square": "^3.0.12",
        "turf-square-grid": "^3.0.12",
        "turf-tag": "^3.0.12",
        "turf-tesselate": "^3.0.12",
        "turf-tin": "^3.0.12",
        "turf-triangle-grid": "^3.0.12",
        "turf-union": "^3.0.12",
        "turf-within": "^3.0.12"
    },
    "description": "a JavaScript library for performing geospatial operations with GeoJSON",
    "devDependencies": {
        "browserify": "~9.0.3",
        "disc": "^1.3.2",
        "hcat": "0.0.5",
        "jsdoc": "^3.3.0-beta1",
        "lerna": "https://github.com/kittens/lerna/archive/master.tar.gz",
        "tape": "^3.5.0",
        "uglify-js": "~2.4.16"
    },
    "directories": {},
    "dist": {
        "shasum": "eb2f4a80a2d583b8c6486bc7b5c7190466866c27",
        "tarball": "https://registry.npmjs.org/turf/-/turf-3.0.14.tgz"
    },
    "files": [
        "index.js",
        "bower.json",
        "turf.js",
        "turf.min.js"
    ],
    "homepage": "https://github.com/turfjs/turf#readme",
    "keywords": [
        "gis",
        "geo",
        "geojs",
        "geospatial",
        "geography",
        "geometry",
        "map",
        "contour",
        "centroid",
        "tin",
        "extent",
        "geojson",
        "grid",
        "polygon",
        "line",
        "point",
        "area",
        "analysis",
        "statistics",
        "stats",
        "midpoint",
        "plane",
        "quantile",
        "jenks",
        "sample"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "cspanring"
        },
        {
            "name": "cwmma"
        },
        {
            "name": "jseppi"
        },
        {
            "name": "jvrousseau"
        },
        {
            "name": "lyzidiamond"
        },
        {
            "name": "morganherlocker"
        },
        {
            "name": "mourner"
        },
        {
            "name": "tcql"
        },
        {
            "name": "tmcw"
        }
    ],
    "name": "turf",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/turfjs/turf.git"
    },
    "scripts": {
        "build": "browserify index.js -s turf > turf.js && uglifyjs turf.js -c -m > turf.min.js",
        "prepublish": "npm run build",
        "size": "browserify index.js --full-paths -s turf | uglifyjs -c -m | discify | hcat",
        "test": "echo 1"
    },
    "version": "3.0.14"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
