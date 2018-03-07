# gulpfile-template
My base gulpfile for starter web applications

I usually use Bootstrap for making starter apps so I can focus more on the backend API side instead 
of spending hours making a basic starter theme. I prefer SCSS over CSS so I figured I would upload
my usual setup since I end up having to refresh my memory by scouring the web for sample code. If
anyone gets use out of this then awesome... but it is mostly just for me.

Currently there is only a 'watch' since I'm just developing this on my local. I'll most likely add
other tasks once I get to later stages in development.

# The Rundown:
1. The `sass` task would have a `main.scss` with the import for Bootstrap from `node_modules` as
well as custom overrides and page specific stylesheets imports in there as well.
2. All of those stylesheets get compiled and put into the `public` directory in root; this is what the browser
will have access to.
3. The `js` task takes all necessary js files from `node_modules` that Bootstrap requires as well as
my custom js files from my `src` directory.
4. I'm not minifying my custom js files yet, just spitting them into the same `public` file.

That's all!
