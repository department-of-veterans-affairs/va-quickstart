# va-quickstart
Front end packaging for VA applications!

To install using bower, use
  ```html
    bower install va-quickstart
  ```

To compile using grunt, use
```html
  grunt
```

To compile in a rails app, migrate the scss files and assets to the appropriate assets directory. Note: urls for things like fonts will have to be updated from:
```html
  url(yourfont.otf)
```

to:

```html
  font-url(yourfont.otf)
```

in order to work with the rails asset pipeline. Additional Foundation components can be added / managed using the app.scss file.
