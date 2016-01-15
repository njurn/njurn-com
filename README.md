# Dependency
```
npm install -g browserify
npm install --save react react-dom babelify babel-preset-react
browserify -t [ babelify --presets [ react ] ] main.js -o bundle.js
```
