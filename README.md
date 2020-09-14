# Band Website (DJ Shadow)

## 1st Milestone Project

## User Centric Front-End Development

## Code Institute 2020

---

The brief for this project was to build a website to represent a band, which would
appeal to both new and existing fans. The music artist DJ Shadow was chosen as the
subject for this purpose. The design was based on user experience priciples and a
responsive mobile first method was employed. The purpose of this wesite is to provide
users with:

- useful and appealing information about the artist
- links to samples of his music (videos/spotify)
- links to his social media
- upcoming touring dates & ability to contact his management
- photos
- merchandising
- newsletter sign-up

---

### See the image below for an example of the responsiveness of the site.

Click the image to be taken to a live demo of the site:

[![homepage][1]][2]

[1]: ./documentation/images-for-readme/am-i-responsive.JPG
[2]: https://robot5000-design.github.io/project_one/index.html "Live Site"

---

### **UX Design**

#### Strategy

_User Stories:_

There are 3 types of users of the site: the artist(site owner), the fans or the organiser of an event.

As the site owner:

- I want to present myself and my music in a positive way and in a style that fits with my image and my music.
- I want fans to be drawn in by the landing page.
- I want fans to know when and where I am playing live.
- I want fans to be able to listen to samples of my music and be directed to spotify where I make money from their repeat listens.
- I want my new album to be promoted but to use my famous material to promote the site.
- I want fans to be able to purchase merchandise.
- I want fans to be able to keep up to date with what is going on in my world through links to my social media and either a news feed or newsletter sign-up.
- I want a contact form for event organisers to be able to get in touch with my management for potential gigs.

As a fan:

- I want to be able to get links to new and old music and videos.
- I want to be able to purchase merchandise.
- I want to be able to stay up to date with news and link to social media sites.
- I want to be able to see where the artist is touring next or if they might be playing local to me soon.
- I want to be able to quickly find bio information about the artist.
- I want to see photos of the artist.

As an event organiser:

- I want to see what the artists upcoming touring schedule looks like and to have the means to contact the artists management.

The main goals of this site, arising from the user stories and research of other musician sites are:

- to have useful and appealing information about the artist.
- to have links to samples of his music (videos/spotify).
- to have links to his social media.
- to have upcoming touring dates & ability to contact his management
- to have a selection of photos.
- to have merchandising.
- to have a news page or a newsletter subscriber sign-up.

#### Scope

Based on the results of the Strategy research the features to be included are:

- Landing page with iconic endtroducing image.
- Gallery with photos from official Instagram.
- Music page with links to all albums on spotify.
- Embedded youtube videos of some well known music pieces.
- A newsletter subscription form.
- A bio page.
- An upcoming gigs page with the ability to contact management.
- All features are viable except an online shop at this moment and a newsletter sub is more suitable to
  this project rather than a news feed page. A link to an official artist online shop can be provided.

#### Structure

- A simple tree and branch layout with few pages all accessible from the navigation bar at
  the top of the page where the user expects.
- Custom 404 page, so in the case of a broken external link a button is provided
  for the user to return to safety.
- Tree structure implemented with navbar for mobile users and linear path on gallery page
  if necessary to reduce the number of photos on screen all at once.

#### Skeleton

Wireframes made in Balsamiq Wireframes were used for basic layout. These can be viewed here:

[Landing Page All Sizes](./documentation/wireframes/landing_page.png)

[Music Page All Sizes](./documentation/wireframes/music_page.png)

[Tour Page All Sizes](./documentation/wireframes/live_page.png)

[Gallery Page All Sizes](./documentation/wireframes/gallery_page.png)

[About Page All Sizes](./documentation/wireframes/about_page.png)

[Merch Page All Sizes](./documentation/wireframes/merch_page.png)

#### Surface

Colours were chosen based on the 20th aniversary edition of DJ Shadow's seminal album, Endtroducing.
This also provided the main logo/icon for the nav element.

The main background colour #9F8A38 was darkened slightly to provide more contrast with the text.
This allowed the site to score 100 in the Accessibility category on Chrome Development Tools Lighthouse.

The fonts chosen were Bebas Neue for headings (bold eye-catching font) and Roboto Mono for everything else.
Text colour is an off-white #FAFAFA contrasted with #3F3F3F for icons and footer.

[Figma](https://www.figma.com/) was used to check colours
and basic theme. The Figma mock-up can be viewed [here](./documentation/images-for-readme/figma-mock-up.jpg).

![ColourChoices][3]

[3]: ./documentation/images-for-readme/color-choices.jpg "Colour Choices"

---

### **Features**

Common to all pages, a nav element with navigation links at the top of the page. This is fixed
on mobile where the smaller screen results in more scrolling. A navbar is also utilised 
on smaller screen sizes. Icons have been used to completment all headings.

In addition all pages have a constant footer which contains links to social media, terms(doesn't exist)
and privacy(doesn't exist). These links provide interactive feedback when hovered over,
they change colour.

Customised Bootstrap was used to help with the responsiveness and layout of the site.
In addition targeted media queries were used to assist with this.

More detailed information on features of each page:

*1. Home:*

 Landing page with large hi-res eye-catching widescreen version of the famous photo
 used on the original Endtroducing album cover. An opaque overlay gradually lights
 up from dark when you arrive on the page. This gives the impression of the lights being
 switched on in the music store as you look through a window.

 Embedded classic video from Endtroducing in addition to an image of the new album
 with an opaque overlay on hover which has a link to the album on Spotify.

 A form to sign-up for a subscriber newsletter.


*2. Music:*
 
 Selection of all album covers that when hovered over the opaque overlay contains 
 information on the album and a link to the album on Spotify. Selection of embedded 
 youtube videos to draw in new listeners.

*3. Tour:*

 List of upcoming touring dates and contact form modal to contact management.

*3. Gallery:*

 Page of photos from the official Instagram, laid out in an ad-hoc poster board 
 format. Linear pagination used to spread photos over two pages as necessary.

*4. About:*

 Some bio info about the artist with appropriate photos.

*5. Merch:*

 Link to the official DJ Shadow online Shop.

*Other potential features which could be implemented in future:*
* Have an online shop built into the site.
* A news page rather than subscriber news.
* Embedded Instagram rather than current Gallery page.

These would allow the website to be constantly updating which would keep users 
coming back.

---

### **Technologies Used:**
*Languages:*
* HTML - Base structural language.
* CSS - For styling.

*Libraries:*
* Bootstrap 4.5.2 - Used to help with grid layout and screen size responsiveness.
* Javascript, Popper.js, and jQuery as part of Bootstrap.
* Font Awesome for icons.
* Google Fonts for Bebas Neue and Roboto Mono fonts.

*Hosting and Version Control:*
* Github - Holding repository and hosting site.
* Git - Version control.

*Others:*
* Balsamiq - For wireframes.
* Figma - For partial colour mock-up of home page.

---
### **Testing:**



---
### **Deployment:**



---
### **Credits:**




---
