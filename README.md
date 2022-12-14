# THE JUJUBE FARM
This is a website for a organic and sustainable community farm. The aim of this website to raise awareness about the farm to potential custumers and the local community at large. To educate them about the sustainable way the farm is cultivated and how this method of farming is good for the soil, the animals and the customer. This website has three pages; a home page, a pruduce page and our story page.
<img src="assets/images/Screenshot-9.png"/>

The deployed website can be viewed here. [THE JUJUBE FARM](https://kaltun-dev.github.io/jujube-farm/index.html).

## UX
### User Stories
+ As a user, I want to…
1.	be able to navigate the website easily.
2.	be able to get the most important information about the farm and what it sells.
3.	be able to understand why organic and sustainable is good for me and the inviroment.
4.	be able to see multible picture about the farm.
5.  be able to know the location of the farm to visit.
+ As a site owner, I want…
1.	the information to be clear and informative.
2.	the information to be sufficiently various for all users.
3.	the website be simple to navigate.
4.  the user (potential customer) to have call of action area. 

### 1. Strategy 
 * Project Purpose
    *    To provide the user (potential customer) with suffcient information about the farm.
    * 	 To educate people about importance of the sustainable and regenrative way of farming .

### 2. Scope
 * I wanted a simple, straightforward UX experience.
 * I wanted a natural and bright color scheme.
 * I wanted my content to be clear for all users. 
 * A site that is visually appealing on most devices.
 * Information about the farm, it's prodcts and it's story.

### 3. Structure
*	A clear layout is in place to ensure users can immediately find all the information.
*	The navbar is clean and simple with distinguished spacing between each of menue links, which allows for easy and simple navigation.	
*	The Home page is containing an introductory bio, a why choose us section, a more in-dept farm bio section, a map section and a footer area with address and openiong times.
*	The produce page provides a look at all the farm's produce that can be bought.
*	The our story page contains the history and bio of the farm.
*	At the bottom of all pages is the footer section with opening times, adddress, social media icons and a trademark.

### 4. Skeleton
Wireframes created with Balsamiq. The project was developed from initial wireframes and more modifications were made during the development. 

Balsamic wireframe links for the website.

[Home](https://github.com/kaltun-dev/jujube-farm/blob/main/assets/images/Screenshot-10.png)


[our story](https://github.com/kaltun-dev/jujube-farm/blob/main/assets/images/Screenshot-11.png)


### 5. Surface
* Colours

we have paid a lot of attention to the color scheme. And used 3 colors throught the website. we've chosen green to emphasise the feeling of nature and calmness. 

<img src="assets/images/Screenshot-12.png" height="500px">

* Font Selection
 
we've used only one font for this website, and that was montserrat. This was done to keep uniformaty throughout the hole page and for simplicity reasons. The font was from [Google Fonts](https://fonts.google.com/).

## Existing Features 

+ Landing page Navigation Bar and the hero image

 The navigation bar and the hero image are featured on all three pages, the full responsive navigation bar includes links to the Home page, the produce page and the our story page. And is identical in each page to allow for easy navigation and consistent user experience. There are 3 diffrent hero images in all three pages to keep things fresh and un-repetative.

<img src="assets/images/Screenshot-2.png">

Home page is consisted of four main sections exculuding the menue and hero image:

1. A little bio section

A brief two line text about the farm.

2. A why choose us sections

A simple 3 row text with fontawsome icons indicating reasons to choose the farm. 

<img src="assets/images/Screenshot-3.png">

3. A three image rows with text under. 

Very imformative section, talks more about the farm with images. The three rows then change to three columns that stack to become responsive.

<img src="assets/images/Screenshot-4.png">

4. A google maps section and a footer section.

This iframe google map shows exacly where the farm is and how to get there.  
The footer section is packed with details about opening times, address, telephone and social media icone.

<img src="assets/images/Screenshot-6.png">

+ Produce page

1. A produce/products area

This page has 6 rows containing products from the farm in the form of images and text. In the small mobile and tablet screen the rows turn into columns. 

<img src="assets/images/Screenshot-7.png">

2. Footer section
 
 A responsive footer that is identical in all three pages.

+ Our story page.

This page has three sections excluding, menue, hero image and the footer sections.

1. A long about-us section talking about the farm and it's story.

<img src="assets/images/Screenshot-13.png">
 
2. A subscribe to our news letter form 

A simple resposive form with name, email and submit button.
<img src="assets/images/Screenshot-8.png">

# Testing

## Automated tests

  + HTML

  This website passed the w3c html validation. There were several errors but they have all been fixed. [W3C validator](https://validator.w3.org/).

  Validation results:
  
  #### The home page

<img src="assets/images/Screenshot-15.png">
  
  #### The produce page

<img src="assets/images/Screenshot-16.png">

  #### The our story page

<img src="assets/images/Screenshot-17.png">

   + CSS

No errors were found when passing through the official [W3C validator](https://jigsaw.w3.org/css-validator/). 

<img src="assets/images/Screenshot-19.png">

No warnings were found.  

## Manual Testing

   + Desktop

 Everything is working good Mozilla Firefox, Google Chrome, labtop and large tablet screen . Page loads and all of the page features are working.

   + Mobile
 
 Tested with Samsung s21, Huawei T3, Samsung tap A7, Samsung s22, Galaxy tab s8 ultra, and iPhone XR. It is responsive as intended.

   +  chrome dev tools lighthouse

<img src="assets/images/Screenshot-14.png">

As it's shown on the image, the performance gategory is rather on the low side. This is due to some out of scope reasons such as javscript, iframe google maps, font awsome icons and large hero images that can't be rezised due to image quality dropping. However all th eother gategories are all good.

+ Mozila dev tools.
I have noticed that on the small screen the dev tools is showing a rather small menue items. This is however not an issue on chrome developer tool and all other large and small screen devices we have tested. 


+ Errors
 
During the CSS validation test, there were quite few errors. there was a one particular error where I used the same #id and same .class and a coma to seprate the two in the same div, and then used the same line of code again in the following section. As you can imagine there were around four errors. I had to make sure there was one unique #id per div, remove the comma and then change the css code.


## Future Features
1. I would like to add a carousal feature on the landing page so that images can be swiped.
2. I would also like to add a video and galery section that says "tour the farm".
3. I would also like to add a shopping page that user can buy the produce boxes from.
4. I would also like to add one more page about the farms cafe. 
5. Finally if I where to do similar project in the future I would code the whole website from head to toes using flex-box. it's just so much easier.

## Project Bugs and Solutions:
No known bugs now. But there were quite few problems at every stage. Whenever i fixed a problem there was an another. Here are some.

1. CSS wasn't beeing applied to html page in the browsser i've linked they style sheets in all the pages but it wasnt linking i've tried stack and google but found nothing. In the end solved problem by git add, git commit and git push.

2. Logo h1 not displaying styling as per css rules.
 So i created new menue class and made display inline block. 

3. Hero image is too large taking the whole page and even more. I've googled and change max-width to 100% and made height- auto but that changed nothing. i tried to look at the love running project for help but that didnt work too. so I found a youtube video about the hero image and made some adjustments to the css again. That method didnt work either. so chose anothero picure and rezised it to 1600 by 500px. That sort of sorted the hero picture. but even after it was still a big mess, image was still rather too large. I moved on to the other sections and on the next day i finally finally after some reasearch changed height to 69vh and width to 100%. and it worked finally, for now. But it was not responsive.

4. Container3 center div icon is not diplaying even though the other icons are displaying fine.
After some research I have replaced it with another icon and that seemed to have worked. 

5. Footer background picture wont fit the whole screen. i then removed the padding 33px by using the inspect element and it worked.

6. Can't seem to change nav background color. After some thinking it really wasnt needed. 

7. Font family is not sticking to elements unless I repeatedly use it on indivitual css ruls. My mentor suggested I set general html styling on top of the CSS folder.

8. Web page wasnt being responive in small 300 to 400px screens. After 2 days with help from my mentor i found out the problem was the why-us h3. which had a padding of 30px, that went beyong page width. making the entire page unresponsive. This same problem come back later on another page but this time i wasnt been fooled again. 

9. There was huge problem with the media queries. there was a error message on the terminal and i coudnt even commit. i googled and there was nothing. thankfully the problem was spotted after some help from the slack code institute community. All along it was just a slash and semi colon before the media queries. 

 10. Some other problems
H4 bio heading is not styling css
Assets folder file paths error due to renaming the folder.
Hero image sizing was not good quality.
Git pushing error due to system problemss.


## Deployment

 The website was deployed to GitHub pages. 
 
 * The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab; 
  - From the source section drop-down menu, select the Master Branch;
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 
The live link can be found [here](https://kaltun-dev.github.io/jujube-farm/index.html).

### Forking the GitHub Repository:

By forking the GitHub Repository you will be able to make a copy of the original repository on your own GitHub account allowing you to view and/or make changes without affecting the original repository by using the following steps:
1. Log in to GitHub and locate the [GitHub Repository](https://github.com/kaltun-dev/jujube-farm)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/kaltun-dev/jujube-farm)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.
```
$ git clone https://github.com/kaltun-dev/jujube-farm
```
7. Press Enter. Your local clone will be created.

## Credits 

### Content

All content was written using sources and background information from: 

- [THE COMBE FARM](https://www.coombefarmorganic.co.uk/)

- [MANOR ORGANIC FARM](https://manororganicfarm.co.uk/)

- [THE HAYE FARM](https://www.hayefarmdevon.co.uk/)

### Media

- All pictures and images used in this project are from [CANVA](https://www.canva.com/) 

### Work based in other code

+ [W3 Schools](https://www.w3schools.com/) - used daily for variety of problems and for deeper understanding of both HTML and CSS concepts.
+ [kevin powels Youtube channel](https://www.youtube.com/watch?v=u044iM9xsWU&list=LL&index=4&t=1157s) - Amazing flex-box tutorial, used it to understand flexbox..
+ [mohamed haroon Youtube channel](https://www.youtube.com/watch?v=qPvekXHaESc&list=LL&index=2) - Used for hero image using flexbox..
+ ["Love Running" footer code](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LR101+2021_T1/courseware/4a07c57382724cfda5834497317f24d5/12ba169db7b34b82b137edd825af6a02/) - Used for the footer and why choose us section. 
+ ["easy toturials youtube channel](https://www.youtube.com/watch?v=oYRda7UtuhA&list=LL&index=6&t=415s) used for our-farm and our- produce section using flexbox.


### Acknowledgements

-	To the Code Institute for the course material, lectures and their grounded guidlines for the project.  

-	To the Slack community for being so helpful despite asking 3 or more questions everyday. Thank you for the dozens of informative groups.  

- To [W3schools](https://www.w3schools.com/)  for general reference regarding sytax, tags, elements and everything in between.

- To my mentor Rahul, for being supportive in many ways, postive and encouraging throughout the project.

-	And finally to my three beautiful children, for being patient & understanding  with me, whilst i was doing this project day and night.



