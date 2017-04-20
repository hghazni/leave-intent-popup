# Exit Intent Popup (v1.2)

*By Haroon Ghazni (Front End Developer)- www.hghazni.com*

Introduction
-
The 'Exit Intent Popup' module I've created should easily be able to fit within any page as long as you have the following default code included into your html page. You can amend any of the settings below which will be further explained in the documentation.

**Example code with all options (all options are optional):**
```
  <script type="text/javascript">
      muscleModal.init({
      delay: 1,
      width: 600,
      height: 720,
      cookieExp: 30,
      elementName: 'muscleIntent',
      bgElementName: 'muscleIntent_bg',
      closeElementName: 'muscleIntent_close'
  });
```
To use all default values you can simply use:
```
<script type="text/javascript">
    muscleModal.init();
</script>
```

Default Options
-

Default Settings if you don't change anything


| Option Name   | Default Value   | 
| -------------:|:----------|
| delay     | 1       |
| width     | 600      |
| height | 720     |
| cookieExp | 30     |
| elementName | muscleIntent,     |
| bgElementName | muscleIntent_bg,     |
| CloseElementName | muscleIntent_close,     |

Instalation
-
Insert the one javascript file into your relevant JavaScript directory for your website.
```
1. leaveintent.js
```

Your Blank Canvas
-
So this module initially gives you a blank canvas to play with. It has some default html/css to go inside the popup though as soon you add your own styling it will override the default for you.
 
3 Main Elements
-
So these are the 3 main elements you'll be able to rename and style. They can be found in the __.init__ JavaScript code above in the introduction.

You can rename each of the following default names to match the #ID that you've used in your html document.
```
 // Exit Intent Popup Content ID
 elementName: 'muscleIntent',
 
 // Background of the site once triggered
 bgElementName: 'muscleIntent_bg',
 
 // Close button
 closeElementName: 'muscleIntent_close'
```

Ensure your element matches your `elementName`. Default is `muscleIntent`.
```
<div id="musclIntent">
    <!-- Add content here -->
</div>
```

Editing your Intent Popup settings
-
So looking at the code below the following are all the public settings you can change for your exit intent popup.

1. __When the popup will first appear 'seconds'__
```
    delay: 1,
```   
2. __The height and width of the exit intent box in 'pixels'__
```
    width: 600,
    height: 720,
```
3. __How many 'days' before the cookie resets for a visitor__

```    
    cookieExp: 30,
 ```
4. __The name of the three main elements which are used in the module__
 ```
    elementName: 'muscleIntent',
    bgElementName: 'muscleIntent_bg',
    CloseElementName: 'muscleIntent_close'
```
That's all!
-
And that simply put, is it. If you have any issues feel free to contact me on hghazni@gmail.com
