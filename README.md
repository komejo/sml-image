sml-image
=========

Mobile-first, retina-friendly CSS starting point for background images, using a Small (1x), Medium (2x), and Large (4x) scaling system. Works with CSS-based background images (including sprites). Example.html also includes jQuery image replacement for inline images.

## Basic Use

Image assets for a site should be created at 200% scale so they look crisp on high-pixel-density screens, such as a retina display.

By saving the assets at full size (img_lg), 50% (img_md), and 25% (img_sm), and then using sm/md/lg class tags, you create a reasonably simple way to set up image handling on a site, even with sprites.

The way it works: the small image is served by default (for mobile), the medium for desktop AND mobile retina, the large for desktop retina.

If you only want to serve background images, you only need the sml.css. If you want to conditionally load inline images, you should also use the appropriate code from example.html

## Example page

http://komejo.com/sml-image/example.html

## License and Credits

© 2013 <a href="https://github.com/komejo">Komejo</a>. Created by <a href="http://twitter.com/komejo">Joe Komenda</a>.

sml-image is released under the <a href="http://opensource.org/licenses/MIT">MIT license</a>.

The person in the photo is me.