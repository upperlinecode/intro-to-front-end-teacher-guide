# Intro to CSS Student Guide

## Motivation (i.e. What is this, and why should you care? )

CSS is ***the*** fundmental way of adding style to your websites, and without it, your sites are just a bunch of text in a chunks. All the color, style, and generally cool things you see on the web require tons of CSS. Today will be a nice starting point for you to get your feet wet and see some cool results.



# Part-1: Basic styling and the box-model.

### Step 1: Link to your stylesheet.

+ Open up the 'div-style-challenge.html' file. You'll see a very basic page with some text about animals wrapped in four `<div>` tags.

To start adding CSS, we need to link to the css file in our project folder. There's already one created, called "div-styles.css", so we'll link to that file with a `<link>` tag. The `href` attribute will just be "div-styles.css", but we will also need to tell the web browser that this is a css document with a `rel` attribute and a `type` attribute.

+ In your the `<head>` section of your HTML document add a `<link href="div-styles.css"  rel="stylesheet" type="text/css"  />` tag.

The top of your HTML code should look something like this:
```
<!DOCTYPE html>
<html>
  <head>
    <title> Cool Animals </title>
    <link href="div-styles.css"   rel="stylesheet" type="text/css"    />
  </head>
  ....
```

If you've added the link correctly , when you reload your page you should see that the background turns to a bright magenta! Cool! If you'd like, change the color to a softer, more pleasing `gray` or `dodgerblue`.
There are 140 differnt color names which your web brower can make sense of--basically every crayon color you could want from "cornslik" to "rebeccapurple." You can find a [complete list of colors here](http://www.w3schools.com/colors/colors_names.asp). To change the color, all you need to do is delete the `magenta` from your CSS and replace it with the color of your choice (e.g. `background-color: magenta;`) ***don't forget the semicolon!***

Can't find the exact color you want? Try using a hex color like `#b300b3` or `#0040ff` or find your own with a [hex color picker](http://www.w3schools.com/colors/colors_picker.asp). Or just google "color picker" for a cool tool. CSS also accepts colors in the red-green-blue values like `rgb(66, 134, 244)`. It's a wild, colorful, world out there.


### Step two: Add a border to the divs.

Let's style these divs. For starters, it's hard to tell where one div starts and where the others begin. Let's select all the DIV elements and give them a border and a background-color so that we can see the outline of where they are.

+ Add the following to your CSS document.

```
div {
    border: 5px solid red;
    background-color: dodgerblue;
}
```

Take a moment to look at how the code above is written. Start with the **selector**, in this case `div`, write the curly brackets `{   }`, and write the properties on lines inbetween the curly braces.

The `border` property takes **three** values:
1. The first is how thick the border is, measured in pixels. Try changing this value a bit with values like `1px` or `17px`.
2. The second is the border-style. It accepts values like `solid` and `dashed`.
3. The third is the color, and it takes all the color names and values that the background-color takes.

Some of these CSS properties can get complicated, but the good news it that nobody is expected to remember them all--as a developer you can cheat! Try googling "CSS border property" or going to a good resource like [w3schools to see a bunch of examples](http://www.w3schools.com/css/css_border.asp)


### Step three: change the width.

Now that you have borders for all the divs, let's restrict the width a bit so they don't take up the entire page. A

+ Add a `width: 600px;` to your div styles. Your code should look the the code below--note how each property is on its own line:

```
div {
    border: 5px solid red;
    width: 600px;
}
```


What did changing the width do? Let's try changing the `width` value a bit. Is **800px** better? **400px**? For a cool twist, try a percent value like `width: 80%`. Size properties also accept a percent value, but what do you think the value referes to--i.e. 80% of what?


### Step four: change the margin and padding.

+ First, add a padding value: `padding: 10px;`

What did this do?

+ Next, add a margin value: `margin: 20px;`

What did adding a margin do? How is it different from padding?


### Step five: style a class of elements.

So far, you've been styling **all** the `div` elements with the `div {}` selector. What if you only want to style **some** divs, for example the sea creatures?? To do this, we will need a different type of selector that references a **class** of elements.

In your HTML file, you should notice that some of the divs have a `class` attribute:

```
  ......
  ......

  <div id="whale-shark" class="sea-creatures">
    The whale shark is found in open waters of the tropical .....
  </div>

  <div id="narwhal" class="sea-creatures">
    Narwhals can live up to 50 years. They are often...
  </div>

```

Here, the both the "narwhal" div and the "whale-shark" div have the same class: "sea-creatures". We can select just these two elements with a special class selector, which is just a period followed by the class name, which in this case is `.sea-creatures` . Class names can't have spaces, so in this case the class name was given a dash.

+ Add a different background-color to the sea-creatures class with a class selector:

```
.sea-creatures {
  background-color: blue;
}

.land-creatures {
  background-color: brown;
}

```

Notice how at this point, there are TWO different CSS code lines determining the background-color of the sea-creatures divs: one from the `div {}` selector, and the second from the `.sea-creatures {}` selector. Whenever there is a conflict like this, the browser will use the selector that is ***most*** specific. In this case, because the class selector is more specific than the element selctor, the background-color will change according to the class selector's CSS.

But wait, what about our honey badger! It didn't get any style, but it too is a land creature...

+ To fix this, add the "land-creatures" class to the honey badger div.

### Step five: Select one particular element with an id selector.

What if there's **one** particular element we want to select? For special unique elements, we can use the **id selector** which is a hashtag followed by the id of the element.

+ Change the pangolin element using a hashtag selector:

```
#pangolin {
  font-family: helvetica;
  font-weight: bold;
  font-size: 15px;
  border: 2px dashed red;
}

```

The code above probably won't look pretty, but notices how it only targets one element. Note the the ID selector is intended for special cases, and in any page, there should never be two elements with the same id. If you want to select multiple elements, use a class selector.

### Step six: Google and experiment with some basic CSS elements!

Let's return to our very first site--the hobby page you made for the first HTML lesson.

+ Create a new CSS file in your project folder for your styles--make sure it ends in `.css`. For example `hobby-styles.css` Go ahead and link the CSS file to your HTML page with the `<link>` tag that we learned above.

Now it's time to experiment with a variety of CSS properties. For each, you might need to google the name of the property followed by "CSS" to see an example on a site like W3Schools. The best way to learn css is to copy an example and experiment with changing the values.

Below is the list of properties to try. Try to use as many as you can in the remaining time.

+ border
+ width
+ height
+ color
+ font-size
+ font-weight
+ font-family
+ text-align
+ border-radius
+ background-color
+ text-decoration
+ box-shadow  [this link](http://www.cssmatic.com/box-shadow) can help.
+ margin
+ padding
+ float
+ **challenge** display
+ **challenge** position
+ Check out this handy [cheat sheet!](https://www.smashingmagazine.com/wp-content/uploads/images/css3-cheat-sheet/css3-cheat-sheet.pdf)
