<img src="https://i.imgur.com/ICXCZqT.png" style="margin: 15px;">

`python3 -m http.server`


# **Contents**
**1 - Introduction**
- [1.1 What is the Site About?](#1.1-what-is-the-site-about)
- [1.2 What is the Purpose of the Site?](#1.2-what-is-the-purpose-of-the-site)
- [1.3 Who Built the Site and Why?](#1.3-who-built-the-site-and-why)

**2 - Site Content & Structure**
- [2.1 Pages Overview](#2.1-pages-overview)
- [2.2 Global Elements](#2.2-global-elements)
    - [2.2.1 Page Responsiveness](#2.2.1-page-responsiveness)
    - [2.2.2 Colours](#2.2.2-colours)
    - [2.2.3 Fonts](#2.2.3-fonts)
    - [2.2.4 Images](#2.2.4-images)
    - [2.2.5 Page Layout](#2.2.5-page-layout)
    - [2.2.6 Page Header](#2.2.6-page-header)
    - [2.2.7 Main Section Elements](#2.2.7-main-section-elements)
    - [2.2.8 Page Footer](#2.2.8-page-footer)
- [2.3 - Individual Pages](#2.3-individual-pages)
    - [2.3.1 Home Page](#2.3.1---home-page)
    - [2.3.2 Schedule & Tickets](#2.3.2-schedule-&-tickets)
    - [2.3.3 Your Journey](#2.3.3-your-journey)
    - [2.3.4 The Crew](#2.3.4-the-crew)
    - [2.3.5 The Train](#2.3.5-the-train)
    - [2.3.6 Gallery](#2.3.6-gallery)
    - [2.3.7 Contact Us](#2.3.7-contact-us)

**3 - Technologies Used**
- [3.1 Bootstrap](#3.1-bootstrap)
- [3.2 Imgur](#3.2-imgur)
- [3.3 Font Awesome](#3.3-font-awesome)
- [3.4 Google Fonts](#3.4-google-fonts)
- [3.5 Gitpod](#3.5-gitpod)
- [3.6 GitHub Repository](#3.6-github-repository)

**4 - Testing**
- [4.1 Page Layouts](#4.1-page-layouts)
- [4.2 Test: Header](#4.2-test-header)
    - [4.2.1 Site Logo](#4.2.1-site-logo)
    - [4.2.2 Navbar Navigation](#4.2.2-navbar-navigation)
- [4.3 Test: Footer](#4.3-test:-footer)
- [4.4 Home Page](#4.4-home-page)
- [4.5 Schedule and Tickets Page](#4.5-schedule-and-tickets-page)
- [4.6 Your Journey Page](#4.6-your-journey-page)
- [4.7 The Crew Page](#4.7-the-crew-page)
- [4.8 The Train Page](#4.8-the-train-page)
- [4.9 Gallery](#4.9-gallery)
- [4.10 Contact Us Page](#4.10-contact-us-page)

[**5 Source Code Legend**](#5-source-code-legend)

[**6 Deployment**](#6-deployment)

[**7 Credits and Acknowledgements**](#7-credits-and-acknowledgements)

-------------------------------

# **1 Introduction**

## **1.1 What is the Site About**
The "Santa Special" is a Christmas themed train operated by the 
[Railway Preservation Society of Ireland (RPSI)](https://steamtrainsireland.com). It 
runs annually on each of the Saturdays and Sundays of the three weekends prior to 
Christmas, operating from Connolly Station in Dublin. A steam engine is used to pull 
vintage carriages, each of which has been appropriately decorated for the season. 

Tickets are open to members of the public and it is most popular with parents/grandparents
and their younger children. It is a round-trip of about two and a half hours, that
includes onboard musicians walking through the carriages singing sing-along Christmas
songs, followed by Santa and his Elves, who stop at each set of seats to speak with the
children and give them a gift. The service also offers a limited range of snacks
and a full bar. Tickets are available directly from the RPSI, its members, and online
at [eventbrite](ghjk), a link to which is included on the "Schedule & Tickets" page.

<img src="https://i.imgur.com/1lOIJKq.jpg" style="margin-left: 20%; margin-bottom: 25px; width: 400px;">


## **1.2 What is the Purpose of the Site**
The site has practical and theoretical purposes:

### **Practical**
The principal purpose of the site is to demonstrate my abilities as a developer and put into 
place what I have learned so far, particularly recreating what I learned in previous
modules and projects. While aesthetics and US are important, the prupose of taking this course
is to learn how to write and implement high quality code, with this project focusing onhtml and
css. With this in mind, several elements of the site have been built with coding rather than
design in mind. Examples of this are:
- Hero images display as full screen on all page and devices
- Different hero image on each page
- Different layouts on different views
- Different layouts on same devices depending on view 
    - Gallery
- Employing virgin code as opposed to Bootstrap

### **Theoretical**
1. **New Guests**: The site acts as a shop window for the "Santa Special", providing
information highlighting the positives of the service. The expected outcome is to
engage those who have an interest in family days out with young kids, and preferably
have an interest in steam trains. Because demand constantly outstrips supply, it is 
not necessary to use the site to do a "hard sell" thus eliminating the need for 
pushy messages and notifications.

2. **Existing Guests**: Many guests make the Santa Special an annual family event. 
Inspite of this, many guests know very little about the train because it can be
difficult to find out information as there are limited online resources for it. In
addition to providing core information such as departure times and locations, it also
contains more general points of interest about the service that will be of interest
to existing customers.

## **1.3 Who Built the Site and Why**
The site was conceived, designed and built by Cathal Dolan as his first "User Centric 
Frontend Development Milestone Project",  part of his Full-Stack Developer Diploma 
course from [Code Institute](https://codeinstitute.net/), Ireland. He has been a musician 
on the train since 2014.

[**Back to top of Introduction**](#introduction)

[**Back to Contents Section**](#contents)

......................


# **2 Site Content and Structure**

## **2.1 Pages Overview**
The website consists of seven pages, each accessed via a navigation bar on each page.
1. **[Home Page](#2.3.1-home-page)**: A brief introduction to the "Santa Special" train service.
2. **[Schedule & Tickets](#2.3.2-schedule-&-tickets)**: Information about when the service operates, from where, 
ticket costs, and how to obtain tickets. 
3. **[Your Journey](#2.3.3-your-journey)**: An overview of what passengers can expect their journey to 
consist of, the route taken and points of interest along it.
4. **[The Train](#2.3.4-the-train)**: Factual information about the train such as the size and max speed
of the steam engines.
5. **[The Crew](#2.3.5-the-crew)**: An introduction to the different teams that 
volunteer on the train and what their roles are with regards to making the service 
a success.
6. **[Photo & Video Gallery](#2.3.6-gallery)**: A selection of photographs and 
videos taken of and on the "Santa Special".
7. **[Contact Us](#2.3.7-contact-us)**: Page containing a "contact form", society 
addresses, phone numbers, email addresses and website.

## **2.2 Global Elements**
For the purposes of consistency, several elements are repeated across the site:

### **2.2.1 Page Responsiveness**

The site responds to different screen sizes and devices, done through a mix of
Bootstrap elements and media queries. For the purposes of aesthetics and UK, 
individual pages are laid out differently on different devices. 

For ease of understanding in this doc, the following apply:
- PC = Large and XL screens
- Tablet = Medium screens
- Mobile = Small and XS screens

### **2.2.2 Colours**
There are fours colours used throughout the site. Primary and second are employed to 
reflect and maintain consistency with the RPSI crest colour scheme. The Font Primary colour
is used to colour

- 

- **Primary Colour**: Burgundy: rgb(142, 29, 35), Hex #8E1D23 ![#8E1D23](https://placehold.it/15/8E1D23/000000?text=+)
    - Headings
    - Address titles on Contact Us page
    - Page rules
    - Image borders
    - Buttons
    - Timelines
    - Inline links
    - Footer trim line

- **Primary Colour @ 50% Opacity**: Burgundy: rgba(142, 29, 35, 0.5), Hex #8E1D23aa ![#8E1D23aa](https://placehold.it/15/8E1D23aa/000000?text=+)
    - Headings

- **Secondary Colour**: Blue: rgb(51, 101, 160), Hex #3365A0 ![#3365A0](https://placehold.it/15/3365A0/000000?text=+)
    - Footer main colour 
    - Form fields

- **Secondary Colour @ 50% Opacity**: Blue: rgba(51, 101, 160, 0.5), Hex #3365A0aa ![#3365A0aa](https://placehold.it/15/3365A0aa/000000?text=+)
    - Footer main colour 
    - Hamburger Menu background

- **Font Primary**: Grey: rgb(91, 91, 91), Hex #5B5B5B ![#5B5B5B](https://placehold.it/15/5B5B5B/000000?text=+)
    - Paragraphs
    - Timeline text
    - "Ticket" Background

- **Font Secondary**: Off White: rgb(248, 248, 248), Hex #F8F8F8 ![#F8F8F8](https://placehold.it/15/f8f8f8/000000?text=+)
    - Navbar
    - Hero Images text    
    - Form fields
    - Hamburger Menu Backgrounds
    - Footer text and icons

### **2.2.3 Fonts**
The fonts chosen are based on the fonts that were used by British Rail for over half 
a century, *Gill Sans* and *Railway Alphabet*. These were chosen for their familiarity 
and association with trains. However, as the site uses Google Fonts and neither are
on that platform, the closest alternatives are employed: 

- **Font 1**: [Lato](https://fonts.google.com/specimen/Lato?query=lato) (in place of Gill Sans)
    - Hero images cover text
    - All headings
    - Primary text on "Ticket" Backgrounds
    - Footer links

- **Font 2**: [Raleway](https://fonts.google.com/specimen/Raleway?query=raleway) (in place of Railway Alphabet)
    - Navbar links
    - All paragraphs
    - Buttons
    - Form placeholders
    - Secondary text on "Ticket" Backgrounds

### **2.2.4 Images**
- **"Ticket" Background**: A background image in the style of a vintage train ticket 
is employed on several pages as a background and/or frame. 
    - Home
    - Gallery

<img src="https://i.imgur.com/dmyZZQj.png" style="margin-left: 30%; width: 200px;">

### **2.2.5 Page Layout**
All pages follow the same basic layout with the header, page intro and footer being
consistent across all pages. Many of the Main Body elements are common to 
several pages too. 
- **[Page Header](#page-header)**
    - Logo
    - Navbar
    - Hero Image (Changes for each page)
    - Hero Image cover text
- **[Main Section](#main-section---elements)**:
    - **[Introduction:](#Introduction)**
        - H1 Headline
        - Paragraph
    - **Main Body:**
        - **Info Cards**
            - Home
            - The Crew
            - The Train
        - **Timelines**
            - Schedule & Tickets
            - Your Journey
        - **Contact Form**
            - Contact Us
- **[Page Footer](#page-footer)**

<img src="https://i.imgur.com/yP4jFC6.png" style="margin-left: 30%; width: 300px;">

### **2.2.6 Page Header**

The header is displayed on all pages, maintaining the same format in all cases. It is
composed of three parts:

1. **Logo**: The "Santa Special" boiler plate (and actual boiler plate :-)) is used as
the site logo. It is positioned on the top right of the header. It is an active link 
that returns the User to the homepage when clicked.

<img src="https://i.imgur.com/ICXCZqT.png" style="margin-left: 50px; width: 150px">

2. **Navbar**: The navigation bar consists of seven clickable buttons, one for each 
page as listed in the "Site Structure & Content - Content" section of this file.
Clicking a link brings the user to that specific page. On large and XL devices the
navbar is displayed as a row positioned at the top right of the page. On medium
devices and smaller, a responsive hamburger menu is employed. Stuff about JS?

3. **Hero Image**: Each page contains a unique Hero image made up of two elements:
    1. **Transition**: To give the image the appearance of movement, it will enlarge
    by 10% within its container when a page is first accessed.

    2. **Cover Text**: Each hero contains text that is relavant to the page being viewed
    to give the viewer an indication as to what the page content will be.

### **2.2.7 Main Section Elements**

Each page includes at least two of the following components:

- **Introduction**:
The introduction on each page consists of two elements:

    1. **Headline**: This H1 heading is positioned top centre on the main section
    of all pages and is a the title of the page, indicating what the content beneath 
    relates to.
    2. **Paragraph**: The text is centrally positioned beneath the H1, justified
    left.

- **Info Cards**:
Informational cards are displayed on several pages to provide information about a 
specific topic. Although all cards follow the same basic structure, differences
do exist between pages. Cards consist of five of the following six elements:

    1. **Image ^**: Circular and bordered 
    2. **H2 ^** 
    3. **Rule ^** 
    4. **Paragraph ^** 
    5. **"More" Button ~** 
    6. **Table "**

    **^** Displays on all cards    
    **~** Displays on Home page cards only   
    **"** Displays on "The Train" page

- **Timelines**:
A graphical timeline appears on several pages. It displays horizontally on larger
devices and vertically on smaller ones. It appears on two pages:
    1. Schedule & Journey
    2. Your Journey

- **Clickable Media**:
The Gallery pages includes multiple clickable media links. These take two formats:
    1. **Photos**: Opens a larger version of the photo in a new window
    2. **Videos**: Opens a larger version of the video in a new window

- **Contact Form**:
The contact form allows Users to contact us directly via the site.

- **Paragraph Text**:
This exists outside of the Introduction or cards and is required to highlight certain

### **2.2.8 Page Footer**
The footer is is displayed on all pages, maintaining an identical format in all cases.
It consists of a two-colour background with the secondary site colour taking up the
majority of the real estate, with the site primnary colour occupying a strip along
the top of the footer. It comprises four components or sections:

1. **RPSI Logo**: Links to https://www.steamtrainsirerland.com
2. **Tickets**: Links to the ["Schedule & Tickets"](https://cathaldolan.github.io/The-Santa-Special/schedule_tickets.html) page
2. **Contact Us**: Links to the ["Contact Us"](https://cathaldolan.github.io/The-Santa-Special/contact_us.html)page
3. **Newsletter Sign-up**: Allows for the collection of "opt-in" email addresses.
Addresses are collected.......
4. **Social Links**: Individual icons (provided by Font Awesome) linking to the relevant social media platform page
for the RPSI
    - **Instagram**: https://www.instagram.com/steamtrainsireland/
    - **Facebook**: https://www.facebook.com/steamtrainsireland/
    - **Twitter**: https://twitter.com/RPSITrains
    

## **2.3 Individual Pages**

This section outlines the specifics for each page and includes a wireframe for
each device as well as a link to the actual page. Content differences between
sections are highlighted.

### **2.3.1 Home Page**
The Home Page is the landing page at which visitors arrive on the site. It in
designed to give users an overview of what the site is about, encouraging
them to explore further. It is also accessed via the logo in the header and 
the "Home" button on the navbar.

#### **Home Page Sections & Components**
- **Header**
- **Introduction**
- **Main Body**
    - Info cards with a button link to other Pages:
    - The Crew
        - *On all devices*
    - The Train
        - *On all devices*
    - Your Journey
        - *Shown on PC only*
- **Review "Tickets"**
    - **PC**: 2 tickets
    - **Tablet**: 1 ticket
    - **Mobile**: 1 ticket
- **Footer**

#### **Visuals**

- [Mobile](https://i.imgur.com/sHNEBaE.jpg)
- [Tablet](https://i.imgur.com/RRXfe6l.jpg)
- [PC](https://i.imgur.com/sW90KcA.jpg)
- [Weblink - Home Page ](https://cathaldolan.github.io/The-Santa-Special/)


### **2.3.2 Schedule & Tickets**:  
This page provides information on the schedule for the tarin and how users can
find tickets. It's accessed by clicing the "Schedule & Tickets" button in the 
navbar. It can also be reached by clicking the approrpriate links on the home 
page, contact us page and via the "Tickets" link in the footer.

#### **Schedule & Tickets Sections & Components**
- **Header**
- **Introduction**
- **Main Body**
    - Linear Timeline containing six "ticket" background images, one for each day that 
the service runs with text overlay stating the day, date, and time of each service.
The timeline is horizontal on larger screens and vertical on smaller ones. 
    - Footnote paragraph text regarding the use of a Diesel locomotive on certain
services
- **Footer**

#### **Visuals**

- [Mobile](https://i.imgur.com/I0QGSe2.jpg)
- [Tablet](https://i.imgur.com/LRrHD3j.jpg)
- [PC](https://i.imgur.com/mHlNEm8.jpg)
- [Weblink - Schedule & Tickets](https://cathaldolan.github.io/The-Santa-Special/schedule_tickets.html)

### **2.3.3 Your Journey**
Your Journey provides information about where the train goes, what it passes
along the way, and what guests can expect during the journey. It is accessed 
by clicing the "Your Journey" button in the navbar. 

#### **Your Journey Sections & Components**
- **Header**
- **Introduction**
- **Main Body**
    - Linear Timeline containing six points of interest including names and images.
The timeline is horizontal on larger screens and vertical on smaller ones. 
- **Footer**

#### **Visuals**

- [Mobile](https://i.imgur.com/MnS5iE7.jpg)
- [Tablet](https://i.imgur.com/PcI2tJG.jpg)
- [PC](https://i.imgur.com/nsgji10.jpg)
- [Weblink - Your Journey](https://cathaldolan.github.io/The-Santa-Special/your_journey.html)

### **2.3.4 The Crew**
It takes a crew of more than 50 individuals to operate each train. This
pages give a small insight into the various groups of people and what
they do. It's accessed by clicing the "Crew" button in the navbar. It can also be
reached by clicking the appropriate link on the home page.

#### **The Crew Sections & Components**
- **Header**
- **Introduction**
- **Main Body**
    - Info cards about each team:
        - Santa & His Elves
            - *On PC only*
        - The Engineers
            - *On all devices*
        - The Bar & Kitchen
            - *On all devices*
        - The Safety Officers
            - *On PC only*
        - Management
            - *On PC only*
        - The Musicians
            - *On all devices*
- **Footer**

#### **Visuals**

- [Mobile](https://i.imgur.com/mATW38P.jpg)
- [Tablet](https://i.imgur.com/K2fXoxB.jpg)
- [PC](https://i.imgur.com/mR4vh8y.jpg)
- [Weblink - The Crew](https://cathaldolan.github.io/The-Santa-Special/the_crew.html)

### **2.3.5 The Train**
Part of the attraction with the Santa Special is its vintaghe credentials.
The Train page gives some insight into the engines and cariages used. It
is accessed by clicing the "The Train" button in the navbar. It can also be
reached by clicking the appropriate link on the Home page.

##### **The Train Sections & Components**
- **Header**
- **Introduction**
- **Main Body**
    - Info cards about each locomotive and the carriages:
    - No. 85 - Merlin
        - *On all devices*
    - No. 4 - The Beast
        - *On all devices*
    - Craven Carriages
        - *On PC and Mobile only*
- **Footer**

#### **Visuals**

- [Mobile](https://i.imgur.com/rSOVUiL.jpg)
- [Tablet](https://i.imgur.com/lYDCiHx.jpg)
- [PC](https://i.imgur.com/sXSK8uv.jpg)
- [Weblink - The Train](https://cathaldolan.github.io/The-Santa-Special/the_train.html)

### **2.3.6 Gallery**
The Gallery page gives a visual glimpse at certain aspects of the train and
some of those that work with it. It containsd a mix of images and video. 
Accessed by clicing the "Crew" button in the navbar.

#### **Gallery Sections & Components**
- **Header**
- **Introduction**
- **Main Body**
    - Up to 12 Info Cards using the "Ticket" background to frame each photo/video. 
    - aid out in column format with one video and three images per column.
    - Videos are displayed in the first position of each column. They 
    are YouTube links that open in a new window.
    - Images are displayed in all other positions. They enlarge when clicked
    in a new window.
    - **PC**: 3 columns (3 videos, 9 images)
    - **Tablet**: 2 Columns (2 videos, 6 images)
    - **Mobile**: 1 Column (3 video, 9 images)
- **Footer**

#### **Visuals**

- [Mobile](https://i.imgur.com/7ntAvlD.jpg)
- [Tablet](https://i.imgur.com/Nscl0PW.jpg)
- [PC](https://i.imgur.com/hclciuD.jpg)
- [Weblink - Gallery](https://cathaldolan.github.io/The-Santa-Special/gallery.html)

### **2.3.7 Contact Us**
Accessed by clicing the "Crew" button in the navbar, the page provides information
on how to contact the RPSI and includes a contact form. The page can also be
reached by clicking the Contact Us link in the footer.

#### **Contact Us Sections & Components**
- **Header**
- **Introduction**
- **Contact Form** contained inside a bordered coloured background and including three 
input fields, each with a place holder:
    1. **Full Name**: Text input field
    2. **Email**: Text input field with default email authentication
    3. **"Say what you want"**: Freetype text box that can take up to 500 characters
- **RPSI Contact Details**: Separate justified centre paragraphs with address, phone
number and email addresses for the RPSI head office in Northern Ireland and its 
sub-office in the Republic of Ireland. 
- **Web Address**
- **Footer**

#### **Visuals**

- [Mobile](https://i.imgur.com/lUO76Mb.jpg)
- [Tablet](https://i.imgur.com/9YI78I8.jpg)
- [PC](https://i.imgur.com/a3FcCkC.jpg)
- [Weblink - Contact Us](https://cathaldolan.github.io/The-Santa-Special/contact_us.html)


[**Back to top of this Section**](#2-site-content-and-structure)

[**Back to Contents**](#contents)

......................


# **3 Technologies Used**
## **3.1 Bootstrap** 
For ease of development, Bootstrap [v4.4.1](https://getbootstrap.com/docs/4.4/getting-started/introduction/) 
is employed in several areas of the site including:
- [Navbar](https://getbootstrap.com/docs/4.4/components/navbar/)
- [Columns](https://getbootstrap.com/docs/4.0/layout/grid/)
    - Footer
    - Home Page
    - The Crew
    - The TrainGallery
- [Contact Us Form](https://getbootstrap.com/docs/4.0/components/forms/)

## **3.2 Imgur**
All images used on this site and in this readme are stored and hosted on [Imgur](https://www.imgur.com)

## **3.3 Font Awesome**
Social media icons in footer are provided by [Font Awesome](https://fontawesome.com/icons?d=gallery) v5.11.2 

## **3.4 Google Fonts**
Fonts are provided by [Google Fonts](https://fonts.google.com)

## **3.6 Gitpod**
This website has been constructed using [Gitpod](https://gitpod.io) IDE

## **3.7 GitHub Repository**
This website is hosted on [GitHub](https://github.io)
- **Project Name**: The-Santa-Special
- **GitHub Repository**: https://github.com/CathalDolan/The-Santa-Special
- **Demo Link**: https://cathaldolan.github.io/The-Santa-Special/index.html

[**Back to top of this Section**](#3-technologies-used)

[⬆ back to Contents](#contents)

......................

# **4 Testing**

Testing has been carried out using the following devices/browsers:

- Desktop
- Chrome
- Desktop Chrome emulator
- Huawei P30 lite

## **4.1 Page Layouts**

Rendered pages should match test screen shots for each page and each device:

- **Home Page** 
    - [Mobile](https://i.imgur.com/sHNEBaE.jpg)
    - [Tablet](https://i.imgur.com/RRXfe6l.jpg)
    - [PC](https://i.imgur.com/sW90KcA.jpg)
    - [Weblink - Home Page ](https://cathaldolan.github.io/The-Santa-Special/) 

- **Schedule & Tickets** 
    - [Mobile](https://i.imgur.com/I0QGSe2.jpg)
    - [Tablet](https://i.imgur.com/LRrHD3j.jpg)
    - [PC](https://i.imgur.com/mHlNEm8.jpg)
    - [Weblink - Schedule & Tickets](https://cathaldolan.github.io/The-Santa-Special/schedule_tickets.html) 

- **Your Journey** 
    - [Mobile](https://i.imgur.com/MnS5iE7.jpg)
    - [Tablet](https://i.imgur.com/PcI2tJG.jpg)
    - [PC](https://i.imgur.com/nsgji10.jpg)
    - [Weblink - Your Journey](https://cathaldolan.github.io/The-Santa-Special/your_journey.html)

- **The Crew** 
    - [Mobile](https://i.imgur.com/mATW38P.jpg)
    - [Tablet](https://i.imgur.com/K2fXoxB.jpg)
    - [PC](https://i.imgur.com/mR4vh8y.jpg)
    - [Weblink - The Crew](https://cathaldolan.github.io/The-Santa-Special/the_crew.html) 

- **The Train** 
    - [Mobile](https://i.imgur.com/rSOVUiL.jpg)
    - [Tablet](https://i.imgur.com/lYDCiHx.jpg)
    - [PC](https://i.imgur.com/sXSK8uv.jpg)
    - [Weblink - The Train](https://cathaldolan.github.io/The-Santa-Special/the_train.html)

- **The Gallery** 
    - [Mobile](https://i.imgur.com/7ntAvlD.jpg)
    - [Tablet](https://i.imgur.com/Nscl0PW.jpg)
    - [PC](https://i.imgur.com/hclciuD.jpg)
    - [Weblink - Gallery](https://cathaldolan.github.io/The-Santa-Special/gallery.html)

- **Contact Us** 
    - [Mobile](https://i.imgur.com/lUO76Mb.jpg)
    - [Tablet](https://i.imgur.com/9YI78I8.jpg)
    - [PC](https://i.imgur.com/a3FcCkC.jpg)
    - [Weblink - Contact Us](https://cathaldolan.github.io/The-Santa-Special/contact_us.html)

## **4.2 Test Header**

### **4.2.1 Site Logo**
- **Test 1**: Click on logo on each page
    - **Result**: User is returned to the Home Page

### **4.2.2 Navbar Navigation**
- **Test 1**: Click on "Home" link in navbar
    - **Result**: Verify page navigates to "Home" page
- **Test 2**: Click on "Schedule & Tickets" link in navbar
    - **Result**: Verify page navigates to "Schedule & Tickets" page
- **Test 3**: Click on "Your Journey" link in navbar
    - **Result**: Verify page navigates to "Your Journey" page
- **Test 4**: Click on "Crew" link in navbar
    - **Result**: Verify page navigates to "Crew" page
- **Test 5**: Click on "The Train" link in navbar
    - **Result**: Verify page navigates to "The Train" page
- **Test 6**: Click on "Gallery" link in navbar
    - **Result**: Verify page navigates to "Gallery" page
- **Test 7**: Click on "Contact Us" link in navbar
    - **Result**: Verify page navigates to "Contact Us" page

### **4.3 Test Footer**
- **Test 1**: Click on 'RPSI" crest=
    - **Result**: Verify https://www.instagram.com/steamtrainsireland/ opens in a new tab
- **Test 2**: Click on 'Facebook' icon
    - **Result**: Verify https://www.facebook.com/steamtrainsireland/ opens in a new tab
- **Test 3**: Click on 'Twitter' icon
    - **Result**: Verify https://twitter.com/RPSITrains opens in a new tab
- **Test 4**: Click on 'Instagram' icon
    - **Result**: Verify https://www.instagram.com/steamtrainsireland/ opens in a new tab
- **Test 5**: Add an email address to the "Newsletter" sign-up field and "Submit"
    - **Result**: 
        - Field authenticates email address
        - Email sent notification Displays
        - Email address is received by website admin

### **4.4 Home Page**

- **Test 1**: Click "More" button beneath "Meet Santa & His Elves" card
    - **Result**: User is brought to The Crew page
- **Test 2**: Click "More" button beneath "Take a Trip Back in Time" card
    - **Result**: User is brought to The Train page
- **Test 3**: Click "More" button beneath "Sit Back & Enjoy" card
    - **Result**: User is brought to Your Journey page
- **Test 4**: "Sit Back & Enjoy" section is visible on PC only
    - **Result**: Section is not visible on Tablet or mobile

### **4.5 Schedule and Tickets Page**

- **Test 1**: Click Eventbrite button
    - **Result**: User is brought to RPSI Eventbrite page https://www.eventbrite.ie/o/railway-preservation-society-of-ireland-10929797747
- **Test 2**: View timeline on small, medium and large screen.
    - **Result**: Timeline changes from horizontal to vertical and vice versa

### **4.6 Your Journey Page**

 - **Test 1**: View timeline on small, medium and large screen.
    - **Result**: Timeline changes from horizontal to vertical and vice versa

### **4.7 The Crew Page**

 - **Test 1**: "Santa & His Elves" section only displays on PC
    - **Result**: Section is not visible on Tablet or mobile
 - **Test 2**: "Management" section only displays on PC
    - **Result**: Section is not visible on Tablet or mobile

### **4.8 The Train Page**

 - **Test 1**: "Craven Carriages" section only displays on PC and mobile
    - **Result**: Section is not visible on Tablet

### **4.9 Gallery**
- **Test 1**: Click on each video
    - **Result**: Video opens and plays in a new window with audio
- **Test 2**: Click on each image
    - **Result**: Image opens in a new window

### **4.10 Contact Us Page**

- **Test**: Test that fields are set as Required Fields
    - **Test 1**: Navigate to 'Contact Us' section and click the 'Submit' button without completing
    any fields.
        - **Result**: Verify 'Field required' message is displayed for empty fields 
            - Name
            - Email
            - Say what you want
    - **Test 2**:  Enter text into Name field and click 'Submit' button
        - **Result**: Verify 'Field required' message is displayed for empty field (Email)
    - **Test 3**:  Enter text into Email field and click 'Submit' button
        - **Result**: Verify 'Field required' message is displayed for empty field (Name)

- **Test** - Test that Email field is set for email format
    - **Test 1**: Navigate to 'Contact Us' section, enter text to Name field. Enter text without 
    @ symbol to Email field.
        - **Result**: Verify error message is displayed
    - **Test 2**: Enter text with @ symbol to Email field
        - **Result**: Verify Form submission accepted (for test purposes the page page refreshes)

[**Back to top of this Section**](#4-testing)

[**Back to Contents**](#contents)

......................

# **5 Source Code Legend**

So as to make both the CSS and HTML code easier to navigate, a series of headings are
included for each:

### **HTML**
- < !--======================================== Section - Start -->
- < !--~~~~~~~~~~~~~~~~~~~~ Sub-Section - Start -->
- < !-- Code Comment -->
- < !--? Code Query? -->

### **CSS**
- /*======================================== Section Start */
- /*~~~~~~~~~~~~~~~~~~~~ Sub-Section Start */
- /* Code Comment */
- /*? Code Query? */

[**Back to top of this Section**](#5-source-code-legend)

[**Back to Contents**](#contents)

......................

# **6 Deployment**

Although constructed on Gitpod, the site and all of it's code and assets areas are
hosted on GitHub. So as to prevent the potential loss of data and to allow access to 
all development work carried out on the site, even that not used, the two platforms
are regularly "sync'd". This is a three part process carried out using the Terminal
Window:

1. All code is added to the temporary git directory using the [git add .] command. 
This adds all files that have been changed.

2. "Added" files can then be committed to the git repository using the [git commit -m""] 
command. The reason for each commit is included by way of a comment.
3. Deployment is the final step and publishes the most up to date version to the 
publicly available front end on GitHub pages. It's done using the [git push] command.

All versions are held on the master branch.

[**Back to top of this Section**](#6-deployment)

[**Back to Contents**](#contents)

......................

# **7 Credits and Acknowledgements**

#### Text & Images
The majority of text and images used on the site are sourced from RPSI resources:
- https://www.facebook.com/RPSIDublin
- https://www.facebook.com/steamtrainsireland
- https://www.steamtrainsireland.com/

#### Videos
- DJ Ken Dot, a transport enthusiast https://www.youtube.com/channel/UC3hFt_sJjEoeXkxWVreowDw

#### Hamburger Menu
- This code came from https://stackoverflow.com/questions/42586729/bootstrap-4-change-hamburger-toggler-color 
with an explanation from https://www.youtube.com/watch?v=U7mjfv9gATs&feature=youtu.be

#### Timeline
- Timeline as seen on the "Schedule & Tickets" and "Your Journey" was created using
existing code from "Nickoafan" https://codepen.io/nickoafan/pen/eJMaBx

#### General Assistance
Minor issues and solutions, such as centering elements came from a mix of sources:
- https://stackoverflow.com/
- https://www.w3schools.com/

[**Back to top of this Section**](#7-credits-and-acknowledgements)

[**Back to Contents**](#contents)

......................