# va-quickstart
Front end packaging for VA applications. To compile files locally using grunt, make sure both bower and Node are install / up-to-date.

1. Install using bower:
  ```html
    bower install va-quickstart
  ```

2. cd to the "va-quickstart" directory, then:
  ```html
    npm install
  ```

3. Compile local assets using grunt, run:
```html
  grunt
```

To run use in a rails app, simply install using bower (step 1), then move the assets to your Rails application. Note: asset urls will need to be updated. For example:

```html
  url(yourfont.otf)
```

to:

```html
  font-url(yourfont.otf)
```

Additional Foundation components can be added / managed using the app.scss file.
