# Smart Images

This is a composerable fork of https://github.com/fariasf/smart-images which is a plugin to  smart-load WordPress images (both featured image and in-content images) as the user scrolls. If you want to read the history start there. 

On initial page load, images will be replaced with a blurred version (like Medium does), with a solid color (like Google Image Search does) or with a transparent 1x1 GIF or PNG, either using external requests or embedding the image source encoded in base64. It uses https://github.com/verlok/lazyload to detect the users' scroll and replace the image sources.

This technique will reduce the initial page load time, and the impact will be bigger the more and bigger images the page has. In our test pages, improved PLT by a few seconds (in cases of content with few images) to as much as 30 seconds, in big pieces of content with lot of images.

#### Changes

1.0.0 Initial version immedaitely after the fork once the composer manifest was added.
