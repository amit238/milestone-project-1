# Ed Sheeran

Milestone Project 1 - User Frontend Centric

This is a page about everything Ed Sheeran, the website consists of a general info section, Events, Merchandise and Subscribe page. You can find a demo to the website here.

# UX

##### Strategy

The main focus I had when creating this website, was that I wanted it to be as convenient and accessible to everyone on any screen size. I also want users to be able to view anything on Ed Sheeran whether thats his latest song or his latest merch, it will all be on this website.

##### Scope 

On the 'Subscribe' page as a user you are able to sign up for a newsletter to be notified when something new on him comes up.

##### Structure 

In my 'Merchandise' page, I want my users to quickly be able to purchase what merchandise they want by clicking on the 'Purchase Now' button which redirects them.

##### Skeleton

Index Wireframes:

[Desktop](../wireframes/desktop-index.png)

[Mobile](../wireframes/mobile-index.png)

Events Wireframes:

[Desktop](../wireframes/desktop-events.png)

[Mobile](../wireframes/mobile-events.png)

Merchandise Wireframes:

[Desktop](../wireframes/desktop-merchandise.png)

[Mobile](../wireframes/mobile-merchandise.png)

Subscribe Wireframes:

[Desktop](../wireframes/desktop-subscribe.png)

[Mobile](../wireframes/mobile-subscribe.png)

##### Surface

I had picked the colours blue and dark grey to give the pages a quirky look.

#### User Stories

Users should be able to see a navigation bar, which is in a fixed position. This where you are able to access other pages on the website. On **mobile** you can see a fixed button on the right-hand side of the navigation bar. Which can also expand if you click it and will have all the pages.

As a user type, on my 'Events' page if I want to book tickets for the event. I am able to click anywhere on the selected event, and it will take me straight to the POS.

If I want to view his latest music video or read more about him, there are buttons which will redirect me.

# Features

##### Existing Features

* Home - Allows users to see his latest album, song and information about him.
* Events - Users are able to view all his upcoming events.
* Merchandise - Users can view his latest and best merchandise on this page.
* Subscribe - Allows users to subscribe to a newsletter to get anything new about him straight to your email and phone

On the Home, Events and Merchandise page. There are buttons which redirect you. For example, there is a 'Purchase now' button on all clothes in the 'Merchandise' page.

There is a form on the 'Subscribe' page that allows users to fill in a form and sign up for the newsletter. When they're finished they can conclude by clicking the 'Subscribe' button.

##### Features left to Implement
* Adding data error to my forms when trying to submit on the 'Subscribe' Page

# Technologies Used

##### 1. HTML
* Used to create the website.

##### 2. CSS
* This was used to style the website.

##### 3. Font Awesome
* Used to put icons throughout the website.

##### 4. Google Fonts
* Used to give a more wider range of fonts for the website.

##### 5. Bootstrap v. 4.2.1
* Bootstrap Grid that I have deployed throughout the website, for it to be responsive on all platforms. 
* Bootstrap Cards that I have also deployed throughout the website, to give it a more aesthetic look.
* Bootstrap Carousel, Navigation Bar, Form

##### 6. JQuery
* To embed a map from [Google Maps](https://www.google.com/maps/place/West+Way,+Hounslow+TW5+0JE/@51.4787225,-0.3792974,18z/data=!3m1!4b1!4m5!3m4!1s0x487672d314a1f8fb:0xa3a28ac1fe2c6e26!8m2!3d51.4787657!4d-0.3776329)

# Testing

For creating the website i'm using AWS Cloud9 on Google Chrome

I have used [https://validator.w3.org](https://validator.w3.org/) to validate my HTML and [https://jigsaw.w3.org/css-validator](https://jigsaw.w3.org/css-validator/) to validate my CSS. The only errors are the embedded map and Google Fonts that i have used but i cannot change as it's not my code.

##### View

* I have also tested the website on Google Chrome developer tools. Seeing how it is viewed on all IPhone and IPad sizes along with the Google Pixel 2.

* During the developement of the page I've also viewed the page on Firefox and Microsoft Edge.

##### Links

* I have also tested my links and to see if they all go onto a new tab, using `target=_blank"` in the HTML.

##### Form

* When trying to submit an empty form, a message will pop out saying "Please fill in this field." 

* The 'required' attribute is added to the 'Name' 'Phone Number' and 'Email' fields, so if those fields are not filled in, the form will not submit.

# Deployment

Im using GitHub to deploy my website, directly from the master branch. Since the start of my project, i have created a GitHub Repository which i have commited my changes of my website to it. Any changes will update automatically upon any new commits to the master branch. For the website to work on GitHub page, my landing page must be named index.html.

You can view the website [here](https://amit238.github.io/user-frontend-project/)

If you want to run locally, you can clone this repo, by pasting `git clone https://github.com/amit238/user-frontend-project` into your terminal.

# Credits

##### Content

All the content on the website has been written by me. 

##### Media

The images i have gathered for this website, are from Google Images and [Ed Sheerans Website](http://edsheeran.com/)

##### Acknowledgements

For some inspiration i used [Ed Sheerans Website](http://edsheeran.com/) to see how certain pages were layed out.

For the 'About' section in the `index.html` page i had copied and reworded it from his [Wikipedia](https://en.wikipedia.org/wiki/Ed_Sheeran)