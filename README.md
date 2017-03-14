# Angular 2 md-spinner.svg
For loading your angular 2 app (which can be around 2MB big) is pretty useful to have the material design spinner in `.svg`. So you can show loading spinner while the app is loaded. 

# Demo
You can see example [here](https://filipmolcik.com/angular-2-material-design-svg-spinner/)

# Example of usage
## In you `index.html` file
Instead of `Loadin ...` text just place md-spinner svg image.
```html
    <my-app>
        <img id="md-spinner" src="img/GENERAL/md-spinner.svg" alt="Loading ...">
    </my-app>
```

## Safari
If you want compatibility with safari use object instead img
```html
<object
   type="image/svg+xml"
   data="img/GENERAL/md-spinner.svg">
</object> 
```
instead

## In your `main.css` file (for centering the spinner)
```css
html, body {
    height: 100%;
}

body {
    display: flex;
    align-items: center;
    justify-content: center;
}

#md-spinner {
    height: 100px;
    width: 100px;
}
```
Or you can use [other ways](http://stackoverflow.com/questions/11856150/css-to-center-a-image-horizontally) for centering image ... 
