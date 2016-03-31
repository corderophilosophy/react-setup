# React / Webpack (Testing)
Baseline testing to optimize js files for 'Production' use.  

Note this is not a React Starter boilerplate.  It's an experiment to test Webpack output pre-compression (gzip etc...)

#Production Output
```
+-- dist
|   +-- bundle.js (546 bytes)
|   +-- index.html (219 bytes)
|   +-- vendors.js (189 KB) 👎
```

#Build
npm run build (output to production dir)


