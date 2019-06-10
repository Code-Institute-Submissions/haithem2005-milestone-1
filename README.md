# THE MONKEES
###### Milestone project-1 User-Centric Frontend Development - Code Institute
This is a (front-end only) responsive website for a band.The band is a 1960’s rock band and have around 50 years experience of performing live at numerous events around the world. 
#   UX
This project targets audiences who are the band fans and potential fans who wish to use the site to:
 
1. see and hear clips from the band back catalog.
2. keep updated with any new material as it becomes available.
3. read about the band news.
4. see pictures for the band, their tours, and their events.
5. the band can use the site to showcase their music and publicize their availability to perform at events such as weddings and Christmas parties.

To achieve this i made the project as simple as i could, ease to learn and use.
The project contain 4 pages(home, media, photo, event) also there is a links in the footer for there social media accounts.

# Technologies

1. HTML5
2. CSS
3. BOOTSRTAP (4.3)
4. FANCYBOX 3
5. jQuery
6. Google-fonts

# Features

* The navbar in this site stays collapsed regardless of the screen size to promote a minimalist design also some transitions such as translate and color used with it to add some style to the menu items.</br>
* Allow users to view band photos as a gallery in the photo page Using fancybox to display images with CSS zoom in transition when hover.
* A favicon have been added to each HTML page.

# Testing
 
 The user story achieved the intended outcome by providing them with four pages:
###### The home page
which introduce the band to their fans through about us section, tell them the band news through the news section, also it
has the tours dates in the tour section. On desktop about us section and news section contain an image 
of the band while on mobile its only one image for both of them, some extra margins added to the desktop view to make the logo looks better.
###### The media page
which contain some videos in the videos section and sound clips in the audio section so users can listen and watch the band.
the audio section contains 3 audios in a row in the desktop view, while in the mobile view each row has one audio clip.
###### The photo page
contain some band photos and covers in addition to the band logo. In the mobile view each photo is in a row, while in the desktop view 3 photos per row. in the desktop view when any photo hovered its zoom in, each row has 3 photos, while in the mob view each row has only one photo and no zoom in
###### The event page
which allow users to contact the band for any kind of events using a form with 4 fields (name, email, mobile, and event description).In desktop view, the form is 60% of the screen size while on mobile it's 75%.
                             

* If you try to submit the contact form with an invalid email address, there will be an error noting the invalid email address. Furthermore, the 'required' attribute is added to the 'name,' 'email,' and 'mobile' fields, so if those fields are not filled in, the form will not submit. If all field is valid, the page will reload. 

* All social links will open in a new tab using 'target="_blank"'. All links have been manually tested to ensure that they are pointing to the correct destination.

* This site was tested across multiple browsers and on multiple mobile devices to ensure compatibility and responsiveness.
* The HTML code validated using w3c HTML validator.
* The CSS code validated using w3c CSS validator.
* During the testing phase, I realized that in the photo page at medium screen size, each row contains 3 photos as in desktop view which is not working good, I fix it using col-md-2 to make each row have 2 photos. Also, the red color which used in all the heading was not easy to read so I use a text-shadow property to add some white shadow around the text so it can be read easily.


# Deployment
This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages,
you should create a new repository on the working environment then add the files to it after that commit the added files finally send it to the GitHub repository which you have been created, also the landing page must be named index.html.

To run locally, you can clone this repository directly into the editor of your choice by pasting to your terminal 
git clone https://github.com/haithem2005/milestone-1. To cut ties with this GitHub repository, type git remote rm origin into the terminal.

# Credits

### Content

* The text for section about us was copied from the Wikipedia article https://en.wikipedia.org/wiki/The_Monkees.
* the text for section news was copied from www.monkees.com 

### Media

* The photos used in this site were obtained from code institute and google.
* The video and sound clips in this site were obtained from youtube.


# Acknowledgements

The collapsed navbar regardless of viewport width was taken from [bootstrap examples](https://getbootstrap.com/docs/4.3/examples/navbars/).

I received inspiration for this project from my friends, family, and colleagues.




