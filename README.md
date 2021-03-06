# The Monkees

![alt text](https://github.com/mattjboland/ci-milestoneone/blob/master/images/monkees12.jpg)

This website is going to be used as advertisment and promotion of a band call The Monkees. It gives the user a basic
history of the band and provide audio clips and a video clip for them to enjoy. It informs the user of the services 
they provide and will have testimonials from previous customers. It has an enquiry form where the user will input their
email with a view to getting some feedback on the services they provide or even book. I have built and structured a 
website thats easily navigated by the user and easy on the eyes retaining the attention of the user while being 
informative and explaining the purpose and goals of the band.

## UX

The purpose of this website project is to create a site for the 1960's band The Monkees who have 50 years experience and 
have sold approximately 75 million albums worldwide. The target audience for this website will be the fans who wish to 
use the website for video and audio clips and to get informed about the services they provide. Also potential fans who use 
this site will be attracted by the pictures and descriptions of the band, also the audio and video clips.

**I used the following features on the website for the user to achieve these goals**

* A brief description of the Band
* Audio clips for the user to experience
* Serices, what the band can be booked for
* Video clip for the user to experience
* A brief description on each band members
* Testimonials, what others have said
* Enquiry form where users can enter and email and be contacted
* Social links to Facebook, Twitter and YouTube

## Wireframe Mockups

* [Home Page MU](https://github.com/mattjboland/ci-milestoneone/blob/master/wirefame-mockup/IMG_0486.jpg)
* [Band Page MU](https://github.com/mattjboland/ci-milestoneone/blob/master/wirefame-mockup/IMG_0487.jpg)
* [Testimonial Page MU](https://github.com/mattjboland/ci-milestoneone/blob/master/wirefame-mockup/IMG_0488.jpg)
* [Enquiry Page MU](https://github.com/mattjboland/ci-milestoneone/blob/master/wirefame-mockup/IMG_0489.jpg)

This was the original idea with various pages linked, when the website was created and reviewed by Guido and myself
we both agreed that the carousel on each of the pages was too much too look at. It wasnt easy on the eyes. We agreed
that the best solution was to create a single page website and include all these element on one home page.

## Features

[Home Page][https://mattjboland.github.io/ci-milestoneone/]

* NavBar - I used this feature for ease of navigating the website and to the different pages 
* Carousel - I used this to display some images on each page of the website to keep the users attention
* Audio Clips - I have some audio clips for the user to experience some of their hits
* Video Clip - I have a video clip for the user to enjoy
* Form - I used this so the user can enquire about services etc
* Social Links - I have access links to Facebook, Twitter and YouTube

## Technologies Used

* HTML - This is used as the layout to build the website
* CSS - This is used to style the website
* [Bootstrap](https://getbootstrap.com/) - This is used for the layout and also used grids/rows for the responsive design
* [Font Awesome](https://fontawesome.com/) - This is used for some icons in the website
* [JQuery](https://jquery.com/) - This is used in the carousel and in the enquiry form

## Testing

I have thoroughly tested the website and was unable to find any bad links. Everything is working as is supposed to. I 
have also submitted an incorrect email into the form and it gave me an error message to show that the required attribute 
within my form is working as it should.

## Issues and Bugs

I came across several issues with code, whether it was code taken from Bootstrap or my own code. the first was a problem 
with the Bootstrap Carousel. The carousel wasnt working correctly, so I sent a message to Tutor support and it was 
realised that I linked the Bootstrap CDN before the FontAwesome link and this caused the issue. When the links were 
swapped the problem was resolved. There were many simple issues some that were easily solved by visiting the 
[W3schools](https://www.w3schools.com/) page.

The other big problem I came across was when I was using a video file and linking it to the website. When I inspected 
the file it wasnt responsive. It was working well on large viewports but when viewed on a mobile, it pushed the NavBar 
out and the centering was all wrong. I tried many ways to resolve this problem and couldn't figure it out. So I put it 
out to [Slack](https://slack.com/intl/en-ie/) Community and was able to resolve the problem very quickly and effectively.

I had problems with the audio clips and centering of the pictures. I originally wanted the four clips to be in a row across
the page. This proved to have many problems. Especially when viewed on a smaller screen. When I thought I have solved the 
problem I would check again and it would not render down correctly. This was a persisent problem I had on other sections
too. I got help again online and was able to come up with and effective solution. I then determined it looked better by
splitting the rows to make two and two. The block of four worked much better especially when it came to viewing on a 
smaller screen.

Again I had lots of problems with the layout of the band-details section. I wanted to have the picture along with a brief
description of each band member. Again this proved to be very difficult when viewing on a smaller screen. It was throwing
out the pictures and they werent lining up with their corresponding description, so again I resolved the problem by going 
online and searching for a solution and ended up with a solution from [StackOverFlow](https://stackoverflow.com/).

## Validation

I have checked the code on [https://validator.w3.org/nu/#textarea] and no major errors were reported.

There are a couple of minor errors, but nothing that majorly affects the sites functionality. 

## Deployment

I deployed my website via GitHub pages and is currently published at [https://mattjboland.github.io/ci-milestoneone/]

## Credits

**Content**

For my NavBar I based it on the NavBar seen in the Code Institute module and project work on the Whiskey Landing
Page. I did however take this portion of code from Bootstrap and styled it to suit my page but the basis was from
the coursework.

The Carousel was taken from the Bootstrap website and I used the media content images from Code Institute and used 
them within the carousel.

Home section was taken from Bootstrap with columns and rows used. Guido gave me tips to tidy this section and make it
more visually appealing the to user.

The Audio-Clips section again was taken from Bootstrap with the columns and rows used. I used the images supplied by 
Code Institute and organised them using card components also from Bootstrap. With the help and guidance from my Mentor
Guido I was get this part of the site working correctly and rendering down to smaller screens effectively.

All text used for development of this website was extracted from the Wikipedia article 
[The Monkees](https://en.wikipedia.org/wiki/The_Monkees)

For my Services section I used a portion of code from the Code Institute module and project work on the Whiskey
Landing Page. I modified this slightly to suit my page and changed the Font Awesome icons and used columns and rows
from Bootstrap.

The Video was also supplied by Code Institute and I used that within my website. I used Bootstrap to embed the video into
my website. 

Band details was extracted from The Monkees Wikipedia.  I used a portion of code from the Code Institute module and 
project work on the Whiskey Landing Page. The images again were supplied by Code Institute and used a grid with columns 
and rows from Bootstrap.

For my Testimonials section again I used a small portion of code from the Code Institute module and project work on the 
Whiskey Landing Page. I modified it to suit my website.

The Enquiry Form I used for this website was taken from Bootstrap. I tried several different ones but with the help of my 
Mentor Guido, we decided that this option was the best one to suit the needs of this website.

Finally my Social section I used for my project was a part of the Code Institute module and project work on the Resume 
Project. This really helped my site become interactive and supplied the links where users could explore and research more
about the band. Again columns and Font Awesome were used.

**Media Content**

All media content was supplied by [Code Institute](https://github.com/Code-Institute-Org/project-assets)

## Acknowledgements

* [Code Institute](https://codeinstitute.net/) I used parts of code from the modules, coursework and projects. All
    the media, pictures, audio clips and video were supplied by Code Institute
* [Bootstrap](https://getbootstrap.com/) I used Bootstraps Navbar, Carousel and Form examples in my website
* [W3schools](https://www.w3schools.com/) I used this website when I encountered some problems with my code
* [Slack](https://slack.com/intl/en-ie/) I also used this website for help on code and errors
* [StackOverflow](https://stackoverflow.com/) This website was used as a reference for help and tips
* Guido Cecilio, Guido is my mentor and his help and patience on this project was incredible. I learned so much from 
our meetings and without his knowledge and information it would have been an impossible task. I am so grateful for his 
help.


