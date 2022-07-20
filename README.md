# Tailwind Dokumentation

https://www.youtube.com/tailwindlabs

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

```js
module.exports = {
  content: ["./dist/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

```js
"scripts": {
    "build": "tailwindcss -i ./src/style.css -o ./dist/style.css --watch"
},
```

http://hny.surge.sh/  
npm install --save-dev surge (npm install --global surge)

```js
"scripts":{
    "surge-deploy": "surge -p dist -d s-tailwind.surge.sh" (-p=project -d=domain)
}
```

https://s-tailwind.surge.sh/
