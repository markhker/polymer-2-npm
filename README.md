# Polymer 2, Webpack and PostCSS 
##### ...and not everything within a file
> This is an example on how to organize a project (or an element) to develop with Webpack and PostCSS, on top of Polymer 2 and Web Components.

#### NOTE on Polymer 2 no-flat
I'm using a modified version of Polymer 2, removing the `flat` property from the package.json. I have problems with dependencies `import` while using `webpack` due to that evil property.