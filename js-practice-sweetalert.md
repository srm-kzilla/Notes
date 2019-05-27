# Javascript Sessions | SRMKZILLA
##### Library: SweetAlert
SweetAlert makes popup messages easy and pretty.

## Guide
#### Step 1
Import SweetAlert from Content Delivery Network (CDN).
```html
<script src="https://unpkg.com/sweetalert/dist/sweetalert.min.js"></script>
```
#### Step 2
After importing the script into your webpage, you can call the swal function in a ```<script>``` tag.
```html
<script>
    swal("Good job!", "You clicked the button!", "success");
</script>
```
If you pass three arguments, the first one will be the modal's title, and the second one its text. The third argument will add an icon to your alert! There are 4 predefined ones: ```warning```, ```error```, ```success``` and ```info```.

#### Step 3
Create an HTML button at the beginning of ```body``` tag to call prettyAlert() function.
```html
<button onclick="prettyAlert()">Click me!</button>
```

## Complete code
```html
<html>
    <head>
        <title>Javascript Sessions | SRMKZILLA</title>
    </head>
    <body>
        <!-- Step 3: Create an HTML button to call prettyAlert() function -->
        <button onclick="prettyAlert()">Click me!</button>
        
        <!-- Step 1: Import library from CDN -->
        <script src="https://unpkg.com/sweetalert/dist/sweetalert.min.js"></script>
        
        <!-- Step 2: Define a function for calling SweetAlert :) -->
        <script>
            function prettyAlert(){
                swal("Good job!", "You clicked the button!", "success");
            }
        </script>
    </body>
</html>
```

## Practice Exercises
1. Change the icon of alert by altering the third parameter of ```swal()``` function.
## Further Reference
[SweetAlert docs](https://sweetalert.js.org/guides/#getting-started)
