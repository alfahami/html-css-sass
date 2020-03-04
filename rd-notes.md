# RESPONSIVE DESIGN NOTES

Using HTML/CSS to make a website or app layout adapt to different screen sizes.

It is a necessisty to build responsive layouts
Layouts should render on any form factor

### Ways to achieve different responsive design:
________________________________________________

* Set te viewport / scale

* Use fluid widths as oppse to fixed (max-width css property)

* Media queries - Different css styling for different screen sizes

* Rem units over px (keeps size intact with the rest of the pages, because it is a multiplier of whatever the root of html font size)

* Mobile first method (design layout for mobile devices)

### Em and Rem units:
_____________________

Pixel is a fixed unit
Em and Rem are similar but they are multiplier of different things.

An em unit is a multiplier or relative to the font size of it parent container or parent element

Where a rem unit is relative to the font-size of the root html element (html tag and it default size is 16px which can be changed within css).

### View port width and viewport height:
________________________________________

viewport is the whole area inside the browser, basically the browsser body
No matter how the browser looks it always got 100 viewport height(vh) and it slice horizontally

A website content can be set to 0 to 100% vh and/or vw