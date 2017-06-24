# typescript-gulp-template
This is a ready to use template for any typescript serverside node application.

I have also included my .vscode folder for use in Visual Studio Code. Press F5 to run your application after compiling!

## Commands
- `gulp scripts`: compiles all code in the ./src/ directory, outputs to ./dist/ (with source maps)
- `gulp watch`: watches the ./src/ directory for any changes in .ts files, then automatically runs gulp scripts
- `npm start`: runs your compiled code in the ./dist/ folder
- `npm run scripts`: alias for gulp scripts
- `npm run watch`: alias for gulp watch