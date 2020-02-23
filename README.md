# Homepage
A customizable homepage for your web-browser.
## Configuration
Install NPM packages.
```
npm install
```
Build the project.
```
node_modules\.bin\browserify -t vueify -e app.js -o release/bundle.js
```
Build the project w/ hot-relead.
```
node_modules\.bin\watchify -t vueify -p browserify-hmr -e app.js -o release/bundle.js
```
