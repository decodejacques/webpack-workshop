## Description
I've included a file called library.js  
Don't try to understand it! Just try to understand what it exports

Your job: 
1. Create a javascript file that imports the run function library.js
2. Create a webpack configuration file
3. Run webpack so that it can bundle your javascript file and library.js into the same file
4. Create an HTML file that loads your bundle
5. Load the HTML file in your browser and do what it says

## Reference

Your webpack config should look something like this

```
module.exports = {
   entry: './app.js',
   output: {
     path: __dirname,
     filename: 'bundle.js'
   }
 };
```

Where app.js is the name of the javascript file you created.  
To load a javascript file in an HTML file, use the `script` tag.  The script tag goes at the end of the body element. For example:

```
<body>
  ...
  <script ...></script>
</body>
```
