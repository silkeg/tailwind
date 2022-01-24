# tailwind

Git clone repostitory

npm init

npm install --save-dev tailwindcss

https://tailwindcss.com/docs/installation

https://tailwindcss.com/docs/content-configuration

https://levelup.gitconnected.com/setup-tailwind-css-with-webpack-3458be3eb547

Ordnerstruktur:

dist -> style.css + index.html
src -> style.css

npx tailwindcss init

module.exports = {
content: [
'./src/*.{html,js}'
],
theme: {
extend: {},
},
plugins: [],
}

"scripts": {
"test": "echo \"Error: no test specified\" && exit 1",
"build": "tailwindcss -i ./src/style.css -o ./dist/style.css --watch"
},
