imagelightbox
=============

Image Lightbox, Responsive and Touch‑friendly.

This is a fork of the lightbox plugin created by Osvaldas Valutis at http://osvaldas.info/image-lightbox-responsive-touch-friendly.

## Requirements and Browser support

* jQuery 1.11 (earlier version not tested), feel free to use jQuery v2 if you dont need to support older browsers
* All mayor desktop browsers and versions as well as mobile browsers on Android, iOS and Windows Phone

## How to use

````javascript
<script src="jquery.js"></script>
<script src="imagelightbox.js"></script>
<script>
    $( function()
    {
        $( selector ).imagelightbox();
    });
</script>
````

## Options

The list of options and their default values is:

````javascript
$( selector ).imagelightbox(
{
    selector:       'id="imagelightbox"',   // string;
    allowedTypes:   'png|jpg|jpeg|gif',     // string;
    animationSpeed: 250,                    // integer;
    preloadNext:    true,                   // bool;            silently preload the next image
    enableKeyboard: true,                   // bool;            enable keyboard shortcuts (arrows Left/Right and Esc)
    quitOnEnd:      false,                  // bool;            quit after viewing the last image
    quitOnImgClick: false,                  // bool;            quit when the viewed image is clicked
    quitOnDocClick: true,                   // bool;            quit when anything but the viewed image is clicked
    onStart:        false,                  // function/bool;   calls function when the lightbox starts
    onEnd:          false,                  // function/bool;   calls function when the lightbox quits
    onLoadStart:    false,                  // function/bool;   calls function when the image load begins
    onLoadEnd:      false                   // function/bool;   calls function when the image finishes loading
});
````
