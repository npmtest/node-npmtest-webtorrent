# npmtest-webtorrent

#### basic test coverage for  [webtorrent (v0.98.18)](https://webtorrent.io)  [![npm package](https://img.shields.io/npm/v/npmtest-webtorrent.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-webtorrent) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-webtorrent.svg)](https://travis-ci.org/npmtest/node-npmtest-webtorrent)

#### Streaming torrent client

[![NPM](https://nodei.co/npm/webtorrent.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/webtorrent)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-webtorrent/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-webtorrent/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-webtorrent/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-webtorrent/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-webtorrent/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-webtorrent/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-webtorrent/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-webtorrent/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-webtorrent/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-webtorrent/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-webtorrent/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-webtorrent/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-webtorrent/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-webtorrent/build/test-report.html](https://npmtest.github.io/node-npmtest-webtorrent/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-webtorrent/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-webtorrent/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-webtorrent/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-webtorrent/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-webtorrent/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-webtorrent/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-webtorrent/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-webtorrent/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "WebTorrent, LLC",
        "url": "https://webtorrent.io"
    },
    "browser": {
        "./lib/server.js": false,
        "./lib/tcp-pool.js": false,
        "bittorrent-dht/client": false,
        "fs-chunk-store": "memory-chunk-store",
        "load-ip-set": false,
        "net": false,
        "os": false,
        "ut_pex": false
    },
    "browserify": {
        "transform": [
            "package-json-versionify"
        ]
    },
    "bugs": {
        "url": "https://github.com/webtorrent/webtorrent/issues"
    },
    "dependencies": {
        "addr-to-ip-port": "^1.4.2",
        "bitfield": "^1.1.2",
        "bittorrent-dht": "^7.2.2",
        "bittorrent-protocol": "^2.1.5",
        "chunk-store-stream": "^2.0.2",
        "create-torrent": "^3.24.5",
        "debug": "^2.2.0",
        "end-of-stream": "^1.1.0",
        "fs-chunk-store": "^1.6.2",
        "immediate-chunk-store": "^1.0.8",
        "inherits": "^2.0.1",
        "load-ip-set": "^1.2.7",
        "memory-chunk-store": "^1.2.0",
        "mime": "^1.3.4",
        "multistream": "^2.0.5",
        "package-json-versionify": "^1.0.2",
        "parse-torrent": "^5.8.0",
        "pump": "^1.0.1",
        "random-iterate": "^1.0.1",
        "randombytes": "^2.0.3",
        "range-parser": "^1.2.0",
        "readable-stream": "^2.1.4",
        "render-media": "^2.8.0",
        "run-parallel": "^1.1.6",
        "run-parallel-limit": "^1.0.3",
        "safe-buffer": "^5.0.1",
        "simple-concat": "^1.0.0",
        "simple-get": "^2.2.1",
        "simple-peer": "^8.0.0",
        "simple-sha1": "^2.0.8",
        "speedometer": "^1.0.0",
        "stream-to-blob": "^1.0.0",
        "stream-to-blob-url": "^2.1.0",
        "stream-with-known-length-to-buffer": "^1.0.0",
        "torrent-discovery": "^8.1.0",
        "torrent-piece": "^1.1.0",
        "uniq": "^1.0.1",
        "unordered-array-remove": "^1.0.2",
        "ut_metadata": "^3.0.8",
        "ut_pex": "^1.1.1",
        "xtend": "^4.0.1",
        "zero-fill": "^2.2.3"
    },
    "description": "Streaming torrent client",
    "devDependencies": {
        "bittorrent-tracker": "^9.0.0",
        "brfs": "^1.4.3",
        "browserify": "^14.0.0",
        "cross-spawn": "^5.0.1",
        "electron-prebuilt": "^0.37.8",
        "finalhandler": "^1.0.0",
        "network-address": "^1.1.0",
        "run-series": "^1.1.4",
        "serve-static": "^1.11.1",
        "standard": "*",
        "tape": "^4.6.0",
        "uglify-js": "^2.7.0",
        "webtorrent-fixtures": "^1.5.0",
        "zuul": "^3.10.1"
    },
    "directories": {},
    "dist": {
        "shasum": "d8e0e04a52af884e9cffa361cbe8c159a4cb6f98",
        "tarball": "https://registry.npmjs.org/webtorrent/-/webtorrent-0.98.18.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "eb7ef40d80ebf7fa29188efe0580f2b0c5f3c95c",
    "homepage": "https://webtorrent.io",
    "keywords": [
        "bittorrent",
        "bittorrent client",
        "download",
        "mad science",
        "p2p",
        "peer-to-peer",
        "peers",
        "streaming",
        "swarm",
        "torrent",
        "web torrent",
        "webrtc",
        "webrtc data",
        "webtorrent"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "feross"
        }
    ],
    "name": "webtorrent",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/webtorrent/webtorrent.git"
    },
    "scripts": {
        "build": "browserify -s WebTorrent -e ./ | uglifyjs -c warnings=false -m > webtorrent.min.js",
        "build-debug": "browserify -s WebTorrent -e ./ > webtorrent.debug.js",
        "size": "npm run build && cat webtorrent.min.js | gzip | wc -c",
        "test": "standard && node ./bin/test.js",
        "test-browser": "zuul -- test/*.js test/browser/*.js",
        "test-browser-headless": "zuul --electron -- test/*.js test/browser/*.js",
        "test-browser-local": "zuul --local -- test/*.js test/browser/*.js",
        "test-node": "tape test/*.js test/node/*.js",
        "update-authors": "./bin/update-authors.sh"
    },
    "version": "0.98.18",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
