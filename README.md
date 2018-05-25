# oracledb-electron-rebuild

`oracledb-electron-rebuild` is an example of an electron app that uses
[electron-rebuild](https://www.npmjs.com/package/electron-rebuild) to build the
native module [oracledb](https://www.npmjs.com/package/oracledb).


# Requirements

- See the requirements for
  [node-gyp](https://github.com/nodejs/node-gyp#installation)

- Include `nan` v2.8+ as a dev dependency


# Install

```
npm install
```

Note that `npm install` invokes `electron-rebuild` at the postinstall step (as
defined in `package.json`).


# Run

```
nmp start
```
