The banner should take up the entire height of the viewport.

• The heading and the tagline should be horizontally and vertically in the center of
the banner.

Layout
Image
• Get the image (medium size) from here: https://unsplash.com/photos/
E0AHdsENmDg

• The medium-sized image has the resolution of 1920x1311 and the file size of 700KB.

Serving this image to smaller screens like mobiles and tablets is far from optimal. 

All
the extra bytes downloaded by the browser will be wasted and the browser has to load
this large image for resizing.

 Use https://www.responsivebreakpoints.com/ to create 4
versions of this image for screens with the resolution of 320 - 1440.

• The width of generated images will be 320px (for small mobiles), 853px (for tablets),
1228px (for tablets) and 1440px (for desktops). Use media queries to set the right
background image depending on the viewport width.

• Remember: the more variations of the image we supply, the better we can optimize for
various screen sizes but 4 is enough for this exercise.

• Use the Device Mode in DevTools to ensure the page looks good on various screen
sizes.

• Open the Network tab and ensure that the right image is downloaded for the right
screen.

Text

• Use the Poppins font (available on Google Fonts) with the weights of 900 (for the
heading) and 300 (for the tagline).