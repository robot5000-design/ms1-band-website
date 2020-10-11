# Functional Tests

## Testing links and responsiveness of each html page:
Using Chrome and Chrome Dev Tools. Check all links open in new tab.

## 1. Common to all pages:

- Nav Element Links:

Links | index.html | music.html | tour.html | gallery.html | gallery_2.html | about.html | merch.html
--- | --- | --- | --- | --- | --- | --- | ---
Logo | y | y | y | y | y | y | y
Home | y | y | y | y | y | y | y
Music | y | y | y | y | y | y | y
Tour | y | y | y | y | y | y | y
Gallery | y | y | y | y | y | y | y
About | y | y | y | y | y | y | y
Merch | y | y | y | y | y | y | y

- Footer Element Links:
  
Links | index.html | music.html | tour.html | gallery.html | gallery_2.html | about.html | merch.html
--- | --- | --- | --- | --- | --- | --- | ---
Spotify | y | y | y | y | y | y | y
iTunes | y | y | y | y | y | y | y
Instagram | y | y | y | y | y | y | y
YouTube | y | y | y | y | y | y | y
Facebook | y | y | y | y | y | y | y
Twitter | y | y | y | y | y | y | y
Terms | y | y | y | y | y | y | y
Privacy | y | y | y | y | y | y | y

## 2. Individual pages:

Links | index.html | music.html | tour.html | gallery.html | gallery_2.html | about.html | merch.html | 404.html
--- | --- | --- | --- | --- | --- | --- | --- | ---
Midnight Embedded | y 
New Album | y 
Pathetic |  | y 
Endtroducing |  | y 
Mountain |  | y 
Re-Emagined |  | y
Private |  | y 
Better |  | y
Outsider |  | y 
Pre-Emptive |  | y
High Noon |  | y 
Six Days |  | y
You can't |  | y 
Firestorm |  | y
Arrow Forward | | | | y
Page 2 | | | | y
Arrow Back | | | | | y
Page 1 | | | | | y
Shop Link | | | | | | | y
Back Link | | | | | | | | y


## 3. Forms:

- Check Subscribe Form: Input required. Not active. No error. Working as expected.
- Check Contact Form: All inputs required. Not active. No error. Working as expected.


## 4. Page Responsiveness:

Breakpoints | index.html | music.html | tour.html | gallery.html | gallery_2.html | about.html | merch.html
--- | --- | --- | --- | --- | --- | --- | ---
W270px | y | y | y | y | y | y | y
W576px | y | y | y | y | y | y | y
W768px | y | y | y | y | y | y | y
W992px | y | y | y | y | y | y | y
H450px | y | y | y | y | y | y | y


- In addition each page is checked for responsiveness using Chrome Dev Tools infinitely
	adjustable sliding re-sizer tool. From 280px (Samsung Galaxy Fold) up to full width
	1536px on a 4k laptop. The 404 page was checked this way.
- Any problems are mentioned in the Summary below.

---
## __Summary:__

- No problems found with Links.
- Adjusted Top and bottom margin of images on About page when checking responsiveness.
- Below 297px width album names on album page are overflowing. This may only affect the
  Galaxy Fold. Insert appropriate media query.
- Corrected small overflow on Galery pagination due to margin. Fixed.
- Corrected small overflow due to margin on 404 page at 270px. Fixed.

## __Addendum:__

 - Tested responsivity again after modifying media queries for min-width.

### Bugs List from Github Issues section:
- Opaque Album overlays not displaying on Internet Explorer bug #15.
	Due to time constraints and low IE use this issue is deemed non-critical
	and is not being fixed.

- nav menu list items not correctly spaced in internet explorer bug #14.
  Fixed.

- Merch image not appearing on Internet Explorer bug #11. 
  Fixed.

- Anchor wrapped in button element #10.
	Fixed.

- Large overflow on music and index pages bug #7.
	Fixed.

- Pagination current page visible on top of the navbar on android mobile bug #4.
	Fixed.

- hero image resizing jump on mobile bug #1.
	Fixed.
