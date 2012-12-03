# CSS-Reset
This project aims to strike a balance between the use of a reset stylesheet and the alternative idea of normalizing browser styles by first providing a reset to alleviate the tedium of manually removing styles from individual elements and secondly by offering a flexible way of re-adding *normalized* base styles to chosen elements or document fragments when those styles are in fact desired.

## Reset.css
Mash up of [Eric Meyers' reset](http://meyerweb.com/eric/tools/css/reset/) and some useful cross browser reset rules from [normalize.css](http://necolas.github.com/normalize.css/)

## Base.css
Encapsualted adaptation of [normalize.css](http://necolas.github.com/normalize.css/) designed to be used in conjunction with a reset stylesheet and edited on a project by project basis.

Usage:
    
    [include a reset stylesheet]
    <div>
        <h1>This element is unformatted</h1>
        <div class="-base">
            <h2>This element is formatted</h2>
            <p>Adding `-base` to any element will turn it's html content into a formatted document without the need for classes or IDs.</p>
		</div>
    </div>

## Supported browsers
- Firefox
- Chrome
- Safari
- Mobile Safari
- Opera
- IE