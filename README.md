# jamdox
Electron app for the discovery and exploration of music hosted by Archive.org

```sh
npm install
npm start
```

todo
[] for hot reloading angular within electron it looks like webpack or gulp may be necessary. not essential but would be nice.

[] debug setting typescript compiler to ES6 target

[] for nested ./root/app and multiple package.json's, debug recursive npm install to main package.json for /src (choking on typings install) and recursive npm start dropping the typescript compile
```sh
"install": "npm --prefix ./src install ./src"
```
