#jQuery Filtr Plugin
A jQuery Plugin to filter content 

#Live Demonstration & Usage Examples
http://hudsonncioletti.github.io/jQuery-Filtr-Plugin/

## Usage

### Search Engine
```html
    <input type="text" id="yourSearchElement" />
```
### Objects to Filter
```html
    <div class="filter-me">
        <p>Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a.</p>
        <span> 00:00 </span>
    </div>
    
    <div class="filter-me">
        <p>Pellentesque in ipsum id orci porta dapibus. Proin eget tortor risus. </p>
        <span> 01:00 </span>
    </div>
    
    <div class="filter-me">
        <p>Praesent sapien massa, convallis a pellentesque nec, egestas non nisi.</p>
        <span> 02:00 </span>
    </div>
    
    <div class="filter-me">
        <p>Vestibulum ac diam sit amet quam vehicula elementum sed sit amet dui.</p>
        <span> 03:00 </span>
    </div>
```
### The Magic
```javascript
$('#yourSearchElement').filtr({
    target : ".filter-me", // Object to be filterd
    targetChild : "span",  // Child of Object to be filterd ( not required )
    caseSensitive : false, // Filter strictly  ( true || false , default is false )
    invert : false,        // Shows non maches ( true || false , default is false )
});
```

##Features

  * Lightweight (~1kb minified, ~2kb Original).
  * Filters on any HTML element!
  * Live Filtering

## Compatibility
jQuery Filtr Plugin has been tested with jQuery 1.7+ on all major browsers:

 * Firefox 2+ (Win, Mac, Linux);
 * IE7+ (Win);
 * Chrome 6+ (Win, Mac, Linux, Android, iPhone);
 * Safari 3.2+ (Win, Mac, iPhone);
 * Opera 8+ (Win, Mac, Linux, Android, iPhone).

## Problems & Bugs?
Make sure that you have a *functional* [jsfiddle](http://jsfiddle.net/) exemplifying your problem and open an [Issue](https://github.com/hudsonnicoletti/jQuery-Filtr-Plugin/issues) for me.



