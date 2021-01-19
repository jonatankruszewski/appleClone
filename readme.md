Create the structure folder.
Save the images from the website. You can use some extension to download all of them at once.
Create the basic templating, add a link to the css file.
If the css file doesn't exist, if you CTRl + Click (or command in MAC) it will create it for you.
Make sure the HTML and the body take 100% of the window without overflow when given borders.
Add fontAwesome
Beware to use a CDN that supports font awesome 5+
beacuse this one doesn't, and doesn't take the new icons starting with fas.

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

Add the SVG mac logo. Search for one in the internet. Download it.
To include it, you can add it as an object in your HTML file.
To change its properties, you can open it and modify them.

regarding the sections.
we can split🥁


fonts
you can download them from the developer tools from appole.

https://www.cufonfonts.com/font/sf-ui-display


@font-face {
  font-family: "San Francisco Pro Display";
  src: url("fonts/awesome-font-light.woff") format("woff");
  font-weight:lighter;
}


