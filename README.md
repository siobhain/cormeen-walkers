# Cormeen Walkers


describe what the project hopes to accomplish, who it is intended to target and how it will be useful to the target audience. 

SOB This is a WIP of my README, Anything preceeded by SOB is a placeholder for future edits

SOB 👩🏻‍💻 View an example of this section [here](https://github.com/kera-cudmore/Bully-Book-Club#bully-book-club-website)

# Overview
Cormeen Walkers is a website about walking groups that meet for their walk at Cormeen Sports Complex in rural Co Meath.  There are 3 diverse walking groups that meet weekly although one group, the Power Walkers meet twice a week.  Each group has their own pace and distance but all walks are completed in an hour. The website gives information about when each group meet, where they meet & how far they walk. Each quarter there is a longer 3 hour walk walk in the nearby mountain and details about this excursion can be received by signing up for the newsletter.  There is a gallery with photos taken by Cormeen Walkers. 

## Goal
I created this website as I was continually contacted for information about these walking groups, when and where they meetup etc & I want to be able to direct them to the website whihc will give them all of the information they seek. I specifically do not want to include a contact phone number as I am trying to avoid receiving calls. 

## Target Audience
This website is a landing page for 
- Anyone living in the locality looking for information about walking groups.
- Those who know vaguely of the groups' existence but need specific information about meetup day/time & distance covered.
- Those who have lapsed in attending weekly walks and want to start walking again.
- New people who have moved into the area.

SOBAdd an image of the finished site here - use [amiresponsive](https://ui.dev/amiresponsive) 


The GitHub link to the live site is https://siobhain.github.io/cormeen-walkers/

---
In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

## CONTENTS

* [User Experience](#user-experience-ux)
  * [User Stories](#user-stories)

* [Design](#design)
  * [Colour Scheme](#colour-scheme)
  * [Typography](#typography)
  * [Imagery](#imagery)
  * [Wireframes](#wireframes)

* [Features](#features)
  * [General Features on Each Page](#general-features-on-each-page)
  * [Future Implementations](#future-implementations)
  * [Accessibility](#accessibility)

* [Technologies Used](#technologies-used)
  * [Languages Used](#languages-used)
  * [Frameworks, Libraries & Programs Used](#frameworks-libraries--programs-used)

* [Deployment & Local Development](#deployment--local-development)
  * [Deployment](#deployment)
  * [Local Development](#local-development)
    * [How to Fork](#how-to-fork)
    * [How to Clone](#how-to-clone)

* [Testing](#testing)

* [Credits](#credits)
  * [Code Used](#code-used)
  * [Content](#content)
  * [Media](#media)
  * [Acknowledgments](#acknowledgments)

---

## User Experience (UX)

👩🏻‍💻 View an example of a completed user experience section [here](https://github.com/kera-cudmore/Bully-Book-Club#user-experience-ux)

### User Stories

#### Client Goals

- To minimise amount of time explaining when/where the walking groups meet, the pace, the routes taken & distance covered.
- Site to be responsive -  viewable on all device sizes & all commonly used  browsers
- Users to receive a newsletter by providing a name & email address
- Users can easily find eircode of the meeting place and/or pin meeting place on google maps.
- Purposely do NOT include a contact phone number on this website as a main goal is to reduce number of phone calls.
- Users can view gallery with photos of whats to be seen on the walks & invited to let walk leader know if they have photos to add.

Users may arrive at this page via web search or direct link

First time user can be
- Interesting in finding out more about Cormeen Walkers.
- Looking for general information about the walking groups and where they meet.
- Looking for meet up times & location of a particular group.
- Looking for duration & distance of each groups' walks.

Returning Visitors
 - looking for day and time of a particular walking group
 - looking for directions or eircode for the meetup location
 - interested in singing up for newsletter

## Design

👩🏻‍💻 View an example of a completed design section [here](https://github.com/kera-cudmore/earth-day-hackathon-2022#Design)



### Colour Scheme

The colors chosen reflect the countryside lanes and the building at the meetup location.
SOB


### Typography

The fonts used for this website are Bitter & Nunito, Bitter is a serif type font & used for logo "Cormeen Walkers" in the header. Nunito is a san serif type font and used for all other text. Both fonts are imported from [Google Fonts](https://fonts.google.com/).  

With these font choices I have made the conscious decision to mix a serif with a san serif. The serif Bitter is used only in the header of the web page & although it is a traditional style it has a modern twist. The font is specifically designed for comfortably reading on any computer or device and is refeered to as a 'contemporary' serif typeface for text.  I did want to use a traditional type font for the logo but not one designed over 100 years ago and so Bitter became my choice. For the main text I wanted a clean looking text without extras so as not to distract from the information presented, but one that also blended well with the Bitter logo. Hence I chose Nunito which is a well balanced san serif type font & I think they work well together in this case.

### Imagery

#### Photos

1. The hero image is a country lane typical of the locality in which the walks take place, it is used to attract users that are interested in walking in quiet rural country lanes.
2. The reason for the building image shown in "About Cormeen Sports Complex" is two fold, 1st for people who are familiar with the building it is used to jog their memory as to where the meetup place is & 2nd for new walkers and/or new people to the area it is to help them realise that they have arrived at the location & not drive past it.
3. There are 2 further images at the end of home page in whats referred to as the 'benefits-section' in html. The 1st image is taken in Jan 2022 outside Cormeen Sports Complex before the Family Walkers start, it is used to show users a typical walking groups from Cormeen.  The 2nd, a close up of walking in leaves, is used to encourage the user to come out walking, It is beside the 'Benefits to Walkers' text so meant as a motivitational picture for the user.
4. The Signup page (Newsletter in navigation menu) has a background image from Loughan Lae our local mountain. This is a teaser for users as the signup panel covers most of this picture, they are prompted to signup so that the panel goes away and they get to see the beautiful Loughan Lae.
5. In the gallery page there are 12 photos taken by Cormeen Walkers, at time of writing some of these images are repeated on this page & i will endeavor to have 12 unique images by submission time but please forgive if this does not occur.

#### Icons 
- The are 9 icons used in this website and they are are freely available from [Font Awesome](https://fontawesome.com/), The 9 icons are outlined [here](docs/fa-icon.PNG). Each icon element is given aria-label for accessibility purposes.

### Wireframes

![3 Page Website](docs/images/cormeenwalkers-pages.bmpr)

The site consistes of 3 pages Home, Newsletter & Gallery. Each page can be reached from the menu in the header.  The currect active page is highlighted with a box border*** clearly visible to the user.

The home page (named index.html) has the most important information such as the "When and Where" of the walking groups, the days of the week each group meet & details about the distance and pace of the walk.

For consistency of user experience the header and footer is same on each of the 3 pages.

The header contains the logo & navigation links to get around the website.
The footer contains the tag line "All walks start at 10am from Cormeen Sports Complex" *** along with social media ison links to home page of facebook, twitter youtibe & instagram.  As the site is for educational purposes only there are no social media channels to link to. This informaiton is also outlined in the footer.

The newsletter page (named signup.html) outlines details of the quarterly daytrip and invites the user to submit their name and email address (verified) so that they can be send details of upcominthe next trip etc in a newsletter.  Once they hit "Send me Newsletter" button, the user will get a confirmation notice advising them to check their inbox for the newsletter and how to unsubscribe from receiving it. The confirmation notice is held on a seperate html page named confirm.html but user is oblivious as same backdrop is used for both signup and confirm pages. 


The Gallery page reinforces the sense of countryside, farmland & fresh air by displaying images of sights to be seen while on one of these walks. 

** RESPONSIVE
This ws is responsive, it maintains its layout when viewed on difference screen widths.  The site elements rearrange themesevles according to the current browser screeen width in order to maintain consistency of design and presentation.

![Mockup](docs/images/cormeenwalkers.jpg)

## Features

👩🏻‍💻 View an example of a completed user experience section [here](https://github.com/kera-cudmore/TheQuizArms#Features)

Header & Footer common to all 3 pages

- Home Page : Hero Image, About, Groups, Information & Benefits
- Signup Page : firstname, email form & submit button
- Gallery Page : 12 framed photos in masonary style

### General features on each page

Common to all 3 pages are the header, navigation bar & footer.

If there is a feature that appears on all pages of your site, include it here. Examples of what to include would the the navigation, a footer a nd a favicon.

I then like to add a screenshot of each page of the site here, i use [amiresponsive](https://ui.dev/amiresponsive) which allows me to grab an image of the site as it would be displayed on mobile, tablet and desktop, this helps to show the responsiveness of the site.


### Times
- There are 3 groups & 4 meetups per week

- Walkers : Meet twice a week Mon & Fri, 8k circuit
- Buggys : Meet Wed 10am 5K route
- Family : Meet Sat 10am 4k route

### Guidelines
- No dogs
- High Visibility Jacket
- Weather appropriate Clothing & footwear
- map to find us
Cormeen Sports Complex eircode a82 ft62 is in North County Meath close to the Cavan border, It is equidistant to the towns
				of Kells, Kingscourt & Bailieborough. It is a rural location with views of windmills on rolling farmland
				hills, walking routea from here will have you crossing old stone bridges and walking past farmland
				through the seasons, roads so quite that some have the grassy center!

### Future Implementations

The following features and improvements are for consideration when planning the next version of the website :

- The current newsletter and archives of past newsletter be available for viewing.
- A "Route" section with drawing on google map screenchots of the various road routes used  by the walking groups.  There are 8 different looped routes that can be taken form this crossroads location and each has its own uniqueness.  
- There are 4 offroad crosscountry routes to local townlands/villages which were used by our ancestors in days gone by & the right of way is still upheld, These crosscountry routes be outlined and documented on the website, they are called Mass Paths.
- Links on the web site to join the various Whatsapp groups maintained by Walking Group Leaders.
- Consideration should be given if a contact phone number is required, this can largely be determined by feedback from current users.
- Add any new walking groups that have started up since.
- In index.html, consider rename the final section (benefits-section) to a more suitable name like information-section & add more valuable content.



### Accessibility

Each icon element is given aria-label for accessibility purposes.  

Aria-label v alt

Unfortunately I was unable to physically test the site with a screen reader so I am undecided which attribute - aria-label or alt -  is approprite for accessibility. This stems from the fact that devtools inspect element on browser dropdown seems to use the alt value in the 'accessibility' Name property (ex Gallery photos ) did note that the value on my alt attribute for mages was visible on the dropdown inspect visual in devtools  it depends alos on the 


Be an amazing developer and get used to thinking about accessibility in all of your projects!

This is the place to make a note of anything you have done with accessibility in mind. Some examples include:

Have you used icons and added aria-labels to enable screen readers to understand these?
Have you ensured your site meets the minimum contrast requirements?
Have you chosen fonts that are dyslexia/accessible friendly?

Code Institute have an amazing channel for all things accessibility (a11y-accessibility) I would highly recommend joining this channel as it contains a wealth of information about accessibility and what we can do as developers to be more inclusive.

## Technologies Used

👩🏻‍💻 View an example of a completed Technologies Used section [here](https://github.com/kera-cudmore/Bully-Book-Club#Technologies-Used)

### Languages Used

HTML & CSS.

### Frameworks, Libraries & Programs Used

Make sure to include things like 
git, GitHub,
wireframe handwritten the program used to make your wireframes, any programs used to compress your images, did you use a CSS framework like Bootstrap? If so add it here (add the version used).

A great tip for this section is to include them as you use them, that way you won't forget what you ended up using when you get to the end of your project.

## Deployment & Local Development

👩🏻‍💻 View an example of a completed Deployment & Local Development section [here](https://github.com/kera-cudmore/TheQuizArms#Deployment)

### Deployment

Include instructions here on how to deploy your project. For your first project you will most likely be using GitHub Pages.

### Local Development

The local development section gives instructions on how someone else could make a copy of your project to play with on their local machine. This section will get more complex in the later projects, and can be a great reference to yourself if you forget how to do this.

#### How to Fork

Place instructions on how to fork your project here.

#### How to Clone

Place instructions on how to clone your project here.

## Testing

 Each icon element is given aria-label for accessibility purposes. In devtools I was unable to see the aria-label value on inpection of the icon element via dropdown visual on the browser, however I did note that in some cases the parent element (such as a h2 or h3) acquires the aria-label value for the icon but not in all cases & unfortunatley time did not allow me to investigate further. The aria-label value cab be clearly seen on the accessibility tab of devtools but not on the inpect dropdown, Without time to investigate further I assume this is a limitation on devtools and that had I been actually able to test these aria-labels with a screen reader it would work as intended.



SOB bug - family icon does not render
Start as you mean to go on - and get used to writing a TESTING.md file from the very first project!

Testing requirements aren't massive for your first project, however if you start using a TESTING.md file from your first project you will thank yourself later when completing your later projects, which will contain much more information.
  
Use this part of the README to link to your TESTING.md file - you can view the example TESTING.md file [here](milestone1-testing.md)

background colors

## Credits
SOB Irish Heart Foundation
👩🏻‍💻 View an example of a completed Credits section [here](https://github.com/kera-cudmore/BookWorm#Credits)

The Credits section is where you can credit all the people and sources you used throughout your project.

### Code Used

If you have used some code in your project that you didn't write, this is the place to make note of it. Credit the author of the code and if possible a link to where you found the code. You could also add in a brief description of what the code does, or what you are using it for here.

### Content

Who wrote the content for the website? Was it yourself - or have you made the site for someone and they specified what the site was to say? This is the best place to put this information.

###  Media

If you have used any media on your site (images, audio, video etc) you can credit them here. I like to link back to the source where I found the media, and include where on the site the image is used.
  
###  Acknowledgments

If someone helped you out during your project, you can acknowledge them here! For example someone may have taken the time to help you on slack with a problem. Pop a little thank you here with a note of what they helped you with (I like to try and link back to their GitHub or Linked In account too). This is also a great place to thank your mentor and tutor support if you used them.