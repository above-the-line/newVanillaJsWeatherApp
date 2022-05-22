# newVanillaJsWeatherApp
A HTML, CSS and JS weather app.


# development
```
npm run serve
```


Webpack does the following 

1. compiles scss and sass to css
2. injects the compiled css into JS but then extracts it into its own file and injects it into the head of the HTML file, removing the need for conventional HTML imports.
3. uses babel to compile JS into es2015
4. bundles all js files into one 'bundle.js' file and then injects them below the HTML body section
5. minifies JS for production
6. copys images into an img folder
7. copys the index.html file

