# Band Website - Cotter

Stream One Milestone Project: User Centric Frontend Development - Code Institute

This is a website I have produced for singer/songwriter Tom Cotter. The site allows visitors to listen to some of his music and get information about upcoming gigs. As well as find him on social media and get in touch directly.

The site can be viewed on [GitHub Pages here](https://asquirrelstail.github.io/band-website/).
 
## UX

After a converstaion with Tom I produced a short [brief](https://github.com/ASquirrelsTail/band-website/blob/master/pre-prod/brief.md) featuring a set of goals for the site, a breakdown of Cotters current audience and a few user stories to help guide the UX design.

The site needed to be simple and clean, working well on mobile in particular. Cotter already has a logo and some striking imagery to incorporate and build the site around, and the design needed to be in keeping with those.

Information on Cotter needed to be quick and easy to find, and the site needed to steer users towards his social network profiles for continued enagegment. Users needed to be able to find his songs, gigs and social links with ease.

I was able to put together a couple of [quick sketches](https://asquirrelstail.github.io/band-website/pre-prod/initial-sketches.JPG) followed by a few mockups of the site layout on mobile and desktop.

![alt text](https://asquirrelstail.github.io/band-website/pre-prod/wireframe-1.JPG "Wireframe 1")

![alt text](https://asquirrelstail.github.io/band-website/pre-prod/wireframe-2.JPG "Wireframe 2")

With these as a guide I was able to start coding the main pages of the site.

## Features

 
### Existing Features

- The site has a responsive layout, featuring a nav bar that is collapsed at lower resolutions.
- The site contains embedded audio and video from various streaming services.
- The site has a basic contact form which launches the visitors email client with a pre-filled email on submit.

### Features Left to Implement

The following features fall outside the scope of the milestone project, but will be implemented before the site is made live.

- Alternative music player for browsers that don't support Spotify Web Player.
    -  An alternative music player is required for users of Internet Explorer. Accurately detecting the user's browser and inserting the alternative player will require the use of Javascript.
- EmailJS based email form to replace current mailto: form.

## Technologies Used

- HTML5
- CSS3
- [Bootstrap v4.1.3](https://getbootstrap.com/)
    -  Bootstrap was used for responsive layout, and the collapsing nav component. CSS rules were modified and expanded upon to achieve the desired effects, such as only having the menu appear as a dropdown at certain resolutions.
- [Google Fonts](https://fonts.google.com/)
    -  Google Fonts was used to make sure users could access required fonts, Roboto and Nunito Sans, which was chosen as it is an open source font similar to Avenir which is used in much of Cotter's branding.
- [Fontawesome v5.5.0](https://fontawesome.com/)
    -  The free version of Fontawesome webfonts was used to provide icons for buttons and social media links.
- [Spotify Play Button Widget](https://developer.spotify.com/documentation/widgets/generate/play-button/)
    -  A Spotify widget was used to allow visitors to listen to Cotters songs using Spotify from the site. The style of the iframe was modified using Bootstrap's embed-responsive and custom CSS rules to improve its responsiveness across a variety of resolutions. The embed does not work for users of Internet Explorer but IE is increasingly uncommon, particularly within the target audience.
- [Youtube Video Embed](https://developers.google.com/youtube/player_parameters)
    -  Youtube's embeded video player was used to display a live recording from one of Cotters shows. It was styled using Bootstrap's embed-responsive CSS rules to work well at a variety of resolutions.

## Testing

The site has been tested on a variety of devices, using different browsers and resolutions to ensure compatability and responsiveness. User testing was carried out to make sure all content was easy to find and access on various devices.

Code was validated using the W3C online validators for [HTML](https://validator.w3.org/) and [CSS](http://jigsaw.w3.org/css-validator/). The site was checked for bad links using the W3C [link checker](https://validator.w3.org/checklink).

HTML5 input validation for the contact form was tested manually.

## Deployment

The site has been deployed from the master branch to GitHub Pages [here](https://asquirrelstail.github.io/band-website/), while some associated frameworks are hosted on external CDNs.

## Credits

### Content
Content for the site was kindly provided by Tom Cotter. 

The quote from Ian Paget came from his review on [Indie Midlands](http://www.indiemidlands.com/2018/05/31/live-review-charles-watson-hare-hounds/).

### Media
Photographs used on the site are copyright Tom Cotter, used with permission.

The color pallet was chosen using colors taken from images Tom provided and using [https://coolors.co/](https://coolors.co/) to generate a couple of complementary tones to use in the design.

### Acknowledgements

The shortened vertical rules between columns using psuedo elements to create a shortened border were adapted from [this blog post](https://ivan.reallusiondesign.com/how-to-make-border-smaller-than-div/).

The elegant text-indent snippet used for the logo/h1 was taken from [here](http://www.zeldman.com/2012/03/01/replacing-the-9999px-hack-new-image-replacement/).