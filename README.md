# The Monkees

### This is the project of the website of The Monkees band by Tomasz Kosmider.
### It is the part of Full Stack Software Developer course @ Code Institute


## UX

### Abstract

This website is created for The Monkees band. They are an American rock and pop band originally active between 1966 and 1971.
The main purpose of the website was to stay in touch with their fans. The Monkees want to present their creations such as music,
videos and photos. Also, the band would like to publicise their availability to perform on fans requested events (weedings, 
christmas parties, etc.). The last purpose pointed by the Monkees was to share social media links of Youtube, Twitter and Facebook.

For the user stories and wireframes please go [HERE](https://app.moqups.com/t.kosmider1309@gmail.com/mpVfMLTPtw/view).

### Proposal

I had to use technologies I learnt so far, which are HTML, CSS and Bootstrap.   
I have used The Resume Project (The Mini Project) by Code Institute as the example of the methodology of work.  

I decided to create a website with the minimalistic design, as it is the easiest way to achieve proper result, with limited skills.  

I have pointed out all main requirments and decided to create a navbar cointaining 4 buttons using Bootstrap Grid System to
provide desired responsive design. So for the medium and large devices we will get 4 buttons in the row and for the smaller displays
there will be 2 rows of 2 buttons. The buttons are News, Media, Photos and Book Us - so all main requirments will be provided in 
the form of responsive Navigation Bar.  
The logo should always stay on the top of the page and lead us back to the homepage.  
Footer also uses Bootstrap to display content in 1 or 3 rows.  

#### News

I also choose Bootstrap Grid System to present the section content in a responsive way. This time with sorting content in 1 or 2
columns, depending on the screen size.


To bring some life and to attract user's attention I have used Hover.css and Font Awesome that were introtuced to me in The Resume Project.

## Features

### Existing Features

##### Media
Allows users to play. stop and navigate mp3 songs and mp4 videos by using HTML5 <audio> and <video> widgets.
 
##### Photos
Allows users to scroll through ga;;ery and to open images in a new window by simply clicking on them

##### Book Us 
Allows users to book an event, by having them fill out the contact form. 

### Features Left to Implement

##### Admin panel for posting and adding new content
JavaScript panel for website administrators. It would make posting new things much easier, with no need to change the website code manually.

##### Karaoke style lyrics while playing songs
Implementation of the lyrics which activly scroll themselves while listening to songs on Media page.

##### Calendar on Book Us Page
JavaScript calendar with availability of the band on particular days would make a contact easier.

## Technologies Used

#### HTML5
#### CSS3
#### [Bootstrap 3.3.7](https://getbootstrap.com/docs/3.3/getting-started/)
#### [Font awesome 4.7.0](https://fontawesome.com/v4.7.0/)
#### [Hover.css 2.1.1](https://designlink.work/en-US/hover-css/)
#### [Cloud9](https://www.c9.io)

## Testing

The website was tested with:  
Chrome Version 70.0.3538.110 (Official Build) (64-bit)  
Opera Version:57.0.3098.76  
Firefox Version:63.0.3 (64-bit)  
Microsoft Edge 42.17134.1.0  

[W3C validator](https://validator.w3.org/)

During the test 2 problems have been found.

Problem 1: Grid was not acting properly, when pushing divs to the new line. Some divs got stuck on the right side, because of the div height.  
Implemented solution: display:flex and flex-wrap: wrap applied to section area.

Problem 2: some elements was sticking out of the divs, when the browser window was too small.  
Implemented solution: width: 100% aplied to all elements within section's divs.

## Deployment

[GitHub](https://lesmoke.github.io/TheMonkees/)

## Credits

### Content

Content of News page was copied from the Wikipedia.  

### Media

All graphics, music, video and pictures were provided by Code Institute  

### Acknowledgements

I would like to thank to Code Institute team and Victor Miclovich, my mentor.



