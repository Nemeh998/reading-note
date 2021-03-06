## Audio, Video, Images
# Chapter 16: Images
### Contolling sizes of images in CSS
____
Using the width and height properties in CSS.

if the site is designed on a grid, then it might have a selection of image sizes that are commonly used on all pages, such as:
```
Small portrait: 220 x 360 Small landscape: 330 x 210 Feature photo: 620 x 400
```
```
img.one {
  height: auto;
  width: auto;
}
```
```
img.two {
  height: 50%;
  width: 50%;
}
```
## Aligning images Using CSS
There are two ways that this is commonly achieved:

The float property is added to the class that was created to represent the size of the image

New classes are created with names such as align-left or align-right to align the images to the left or right of the page. These class names are used in addition to classes that indicate the size of the image.
```
img.align-left {
float: left;
margin-right: 10px;}
img.align-right {
float: right;
margin-left: 10px;}
img.medium {
width: 250px;
height: 250px;}
```
#### Centering images using CSS
```
img.align-center {
display: block;
margin: 0px auto;}
img.medium {
width: 250px;
height: 250px;}
```
### Keywords:

+ background-image property allows to place an image behind any HTML element.

+ background-repeat property can have four values:

1. repeat
2. repeat-x
3. repeat-y
4. no-repeat
+ background-attachment property specifies whether a background image should stay in one position or move as the user scrolls up and down the page.
It can have one of two values:

1. fixed
2. scroll
+ background-position property to specify where in the browser window the background image should be placed.

bg-pos

background property acts like a shorthand for all of the other background properties. The properties must be specified in the following order:

1. background-color
2. background-image
3. background-repeat
4. background-attachment
5. background-position
+ rollover to create a link or button that changes to a second style when a user moves their mouse over it.

+ gradient for the background of a box. The gradient is created using the background-image property and different browsers required a different syntax.

**Key point** To reduce the number of images the browser has to load, create image sprites.

## Chapter 19: Practical Information
### Search Engine Optimization (SEO)
Search engine optimization (or SEO) is the practice of trying to help the site appear nearer the top of search engine results when people look for the topics that this website covers.

## On-Page Techniques
The main component of this is looking at keywords that people are likely to enter into a search engine if they wanted to find your site, and then including these in the text and HTML code for your site in order to help the search engines know that your site covers these topics.

## Off-Page Techniques
Getting other sites to link to you is just as important as on-page techniques. Search engines help determine how to rank your site by looking at the number of other sites that link to yours.

## On-Page SEO
In every page of the website there are seven key places where keywords (the words people might search on to find this site) can appear in order to improve its findability:

## Page Title
URL / Web Address
Headings
Text
Link Text
Image Alt Text
Page Descriptions
## Identifying Keywords and Phrases
Through:

Brainstorm
Organize
Research
Compare
Refine
Map
## Analytics: Learning about the site visitors
One of the best tools for doing this is a free service offered by Google called Google Analytics.

The overview page gives a snapshot of the key information the owner of site is likely to want to know. In particular, it tells how many people are coming to this site. Also it tells more about what the visitors are looking at when they come to your site, and where the visitors are coming from.

## Domain Names & Hosting
In order to put the site on the web the developer will need a domain name and web hosting.

+ Domain Names Your domain name is your web address (e.g. google.com or bbc. co.uk). There are many websites that allow you to register domain names. Usually you will have to pay an annual fee to keep that domain name.

+ Web Hosting So that other people can see your site, you will need to upload it to a web server. Web servers are special computers that are constantly connected to the Internet. They are specially set up to serve web pages when they are requested.

+ Hosted Services There are a number of online services that allow you to point your domain name to their servers.

## FTP & Third Party Tools
To transfer your code and images from your computer to your hosting company, you use something known as File Transfer Protocol.

## Article: Video and Audio APIs
The <video> and <audio> elements allow us to embed video and audio into web pages.

<video controls>
  <source src="rabbit320.mp4" type="video/mp4">
  <source src="rabbit320.webm" type="video/webm">
  <p>Your browser doesn't support HTML5 video. Here is a <a href="rabbit320.mp4">link to the video</a> instead.</p>
</video>
the controls attribut enables the default set of playback controls. If it's not specified there will be no playback controls.

Part of the HTML5 spec, the HTMLMediaElement API provides features to allow to control video and audio players programmatically ??? for example HTMLMediaElement.play(), HTMLMediaElement.pause(), etc. This interface is available to both <audio> and <video> elements as well.

Playing and pausing the video
```
playPauseMedia()
```
```

play.addEventListener('click', playPauseMedia);
```
```
playPauseMedia()
```
```
function playPauseMedia() {
  if(media.paused) {
    play.setAttribute('data-icon','u');
    media.play();
  } else {
    play.setAttribute('data-icon','P');
    media.pause();
  }
}
stopMedia()

function stopMedia() {
  media.pause();
  media.currentTime = 0;
  play.setAttribute('data-icon','P');
}
mediaBackward()
mediaForward()
```
