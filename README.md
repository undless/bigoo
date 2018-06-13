![GitHub Logo](/images/bigoo-logo.png)

Bicolor Font Icon by [undless](http://undless.fr)

Demo: [https://undless.github.io/bigoo/](https://undless.github.io/bigoo/)

Bigoo is a bicolor font icon. CSS & font-face only, as regular font icon.
I'll update the project with new icons, stay tuned!

## It's so FLUFFY

Because it's a font, you can change colors and size the way you want / need / love

Check the demo: [https://undless.github.io/bigoo/](https://undless.github.io/bigoo/)

## I Need it

Well, to use it in your project : 

1. Download the file
1. Unzip where you want in your project
1. Link the css to your project :
    ```
    <link rel="stylesheet" type="text/css" href="yourPathToTheFile/bigoo/bigoo.min.css">
    ```
1. Chose the two colors you want and add them in your own CSS using CSS Variables (CSS Variables Support table )
    ```css
    :root {
     --bigoo-main-color: #03a9f4;
     --bigoo-second-color: #607d8b;
    }
    ```
    Make sure that this declaration is made BEFORE the bigoo.min.css import.

    If you prefer to use SASS Variables:
    Download the SASS version and set the two colors you want in your SCSS vars definitions
    $bigoo-main-color: #03a9f4;
    $bigoo-second-color: #607d8b;
    Make sure that the var initialization is made BEFORE the bigoo.min.scss import and to preprocess it with all your other stylesheets.

    If you dont want to use variables at all:
    Just edit the bigoo.min.css file with your 2 colors:
    ```CSS
    .bigoo:before{color:#03a9f4}
    .bigoo:after{color:#607d8b}
    ```
1. Use it in your project. You need the general class "bigoo" and the specific icon class. Exemple:
    ```
    <i class="bigoo bigoo-arrow-circle-left"></i>
    ```
    You can use it directly on existing tags with text inside.
    ```
    <h1 class="bigoo bigoo-arrow-circle-left">Big Title Here</h1>
    ```
    But be aware that the line-height property is set to 0.
    I would recommand to use a specific ```<i>```, ```<span>``` or ```<div>``` tag.

## Hooks

The Bigoo CSS is !important free and single class only so you can easily overide any style from your own CSS.

Check some exemples: [https://undless.github.io/bigoo/](https://undless.github.io/bigoo/)

## Anything else ?

Feel free to [open an issue](https://github.com/undless/bigoo/issues) on Github i'll answer as fast as i can.



Enjoy!
