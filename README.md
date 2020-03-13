<img src="https://i.imgur.com/ICXCZqT.png" style="margin: 15px;">

`python3 -m http.server`

[create an anchor](#footer)

# **Contents**
**1 - Introduction**
- [1.1 - What is the Site About?](#what-is-the-site-about?)
- [1.2 - What is the Purpose of the Site?](#what-is-the-purpose-of-the-site?)
- [1.3 - Who Built the Site and Why?](#who-built-the-site-and-why?)

**2 - Site Structure**
- [2.1 - Global Elements]()
    - 2.1.1 - 
    - 2.1.2 - 
    - 2.1.3 - 
    - 2.1.4 - 
    - 2.1.5 - 
    - 2.1.6 - 
- 2.2 -
    - 2.2.1 - 

**3 - Technologies used**
- 3.1 - More Stuff
    - 3.1.1 - 
    - 3.1.2 - 
- 3.2 - 

**4 - Testing**
- 4.1 - Testing Stuff

# **1 Introduction**

## **1.1 What is the Site About?**
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


## **1.2 What is the Purpose of the Site?**
The purpose of the site is two fold:
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

## **1.3 Who Built the Site and Why?**
The site was conceived, designed and built by Cathal Dolan as his first "User Centric 
Frontend Development Milestone Project",  part of his Full-Stack Developer Diploma 
course from [Code Institute](https://codeinstitute.net/), Ireland. He has been a musician on the train since 2014, 
and felt that due to the absence of good online information about the "Santa Special", 
a beneficial exercise to produce one.

......................


# **2 - Site Structure & Content**

## **2.1 - Global Elements**
For the purposes of consistency, several elements are repeated across the site:

### **2.1.1 - Colours**
There are fours colours used throughout the site. Primary and second are employed to 
reflect and maintain consistency with the RPSI crest colour scheme. The Font Primary colour
is used to colour
- **Primary Colour**: Burgundy: rgb(142, 29, 35), Hex #8E1D23
    - Headings
    - Address titles on Contact Us page
    - Page rules
    - Image borders
    - Buttons
    - Timelines
    - Inline links
    - Footer trim line

- **Secondary Colour**: Blue: rgb(51, 101, 160), Hex #3365A0
    - Footer main colour 
    - Form fields

- **Secondary Colour @ 50% Opacity**: Blue: rgba(51, 101, 160, 0.5), Hex #3365A0aa
    - Footer main colour 
    - Hamburger Menu background

- **Font Primary**: Grey: rgb(91, 91, 91), Hex #5B5B5B
    - Paragraphs
    - Timeline text
    - "Ticket" Background

- **Font Secondary**: Off White: rgb(248, 248, 248), Hex #F8F8F8
    - Navbar
    - Hero Images text    
    - Form fields
    - Hamburger Menu Backgrounds
    - Footer text and icons

### **2.1.2 - Fonts**
The site uses two fonts, both members of the Google Fonts family. For flexibility 
purposes all weights are available for use. 
- **Font 1**:
    - Hero images
    - All headings
    - Primary text on "Ticket" Backgrounds

- **Font 2**:
    - All paragraphs
    - Buttons
    - Form placeholders
    - Secondary text on "Ticket" Backgrounds
    - Footer

### **2.1.3 - Images**
- **"Ticket" Background**: A background image in the style of a vintage train ticket 
is employed on several pages as a background and or frame. 

<img src="https://i.imgur.com/dmyZZQj.png" style="margin-left: 30%; width: 200px;">

### **2.1.4 - Page Layout**
All pages follow the same basic layout. That is (click link to jump to more specific
requirements for each):
- **[Page Header](#page-header)**
- **[Main Section](#main-section---elements)**:
    - Introduction
    - Main Body:
        - Info Cards
        - Timelines
        - Clickable Media
        - Contact Form
        - Paragraph Text
- **[Page Footer](#page-footer)**

<img src="https://i.imgur.com/yP4jFC6.png" style="margin-left: 30%; width: 300px;">

### **2.1.5 - Page Header**

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

    2. **Text**: Each hero contains text that is relavant to the page being viewed
    to give the viewer an indication as to what the page content will be.

### **2.1.6 - Main Section - Elements**

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
specific topic. Although alhough all cards follow the same basic structure, differences
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
There are two styles of timeline:
    1. **Linear**
    2. **Curved**

- **Clickable Media**:
Several pages include clickable media links. These take three formats:
    1. **Quotes**: Takes the User to the QUote source
    2. **Photos**: Opens a larger version of the photo in a new window
    3. **Videos**: Opens a larger version of the video in a new window

- **Contact Form**:
The contact form allows Users to contact us directly via the site.

- **Paragraph Text**:
This exists outside of the Introduction or cards and is required to highlight certain

### **2.1.7 - Page Footer**
The footer is is displayed on all pages, maintaining an identical format in all cases.
It consists of a two-colour background with the secondary site colour taking up the
majority of the real estate, with the site primnary colour occupying a strip along
the top of the footer. It comprises four components or sections:

1. **RPSI Logo**: Links to https://www.steamtrainsirerland.com
2. **Contact Us**: Links to the "Contact Us" page
3. **Newsletter Sign-up**: Allows for the collection of "opt-in" email addresses.
Addresses are collected.......
4. **Social Links**: Individual icons (provided by Font Awesome) linking to the relevant social media platform page
for the RPSI
    - **Instagram**: https://www.instagram.com/steamtrainsireland/
    - **Facebook**: https://www.facebook.com/steamtrainsireland/
    - **Twitter**: https://twitter.com/RPSITrains
    
......................

## **2.2 - Pages Overview**
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

......................

## **2.3 - Individual Pages**

This section outlines the specifics for each page and wireframe links for reach.

### **2.3.1 - Page Responsiveness**

The site is responsive in order to take into account different screen sizes. 
This results in different page layouts being required for different devices. 
Where this occurs on a page it is denoted below by the inclusion of different
device names and the differences between what will be displayed on each. 

For ease of understanding in this doc, the following apply:
- PC = Large and XL screens
- Tablet = Medium screens
- Mobile = Small and XS screens

An individual wireframe is provided for each layout of each page.

### **2.3.2 - Home Page**
The Home Page is the landing page at which visitors arrive on the site. It is
also accessed via the logo in the header and the "Home" button on the navbar.

#### **Home Page - Sections & Components**
- Header
- Introduction
- Info cards with a button link to other Pages
    - **PC**: 3 Cards
    - **Tablet**: 2 Cards
    - **Mobile**: 2 Cards
- Review "Ticket"
    - **PC**: 2
    - **Tablet**: 1
    - **Mobile**: 1 position moved from bottom of the main section to beneath the
    introduction paragraph. This is done in order to maximise space available.
- Footer

#### **Home Page - Wireframes**
- **PC**: 
- **Tablet**: 
- **Mobile**: 

### **2.3.2 - Schedule & Tickets**:  
Accessed by clicing the "Schedule & Tickets" button in the navbar. It can also be
reached by clicking the approrpriate links on the ......page and ....page.

#### **Schedule & Tickets - Sections & Components**
- Header
- Introduction
- Linear Timeline containing six "ticket" background images, one for each day that 
the service runs with text overlay stating the day, date, and time of each service. 
- Footnote paragraph text regarding the use of a Diesel locomotive on certain
services
    - **PC**: Horizontal
    - **Tablet**: Horizontal
    - **Mobile**: Vertical
- Footer

#### **Schedule & Tickets - Wireframes**
- **PC**: 
- **Tablet**: 
- **Mobile**:

### **2.3.3 - Your Journey**
Accessed by clicing the "Your Journey" button in the navbar. It can also be
reached by clicking the appropriate links on the ......page and ....page.

#### **Your Journey - Sections & Components**
- Header
- Introduction
- Curved Timeline containing six point of interest names and corresponding images.
    - **PC**: Horizontal
    - **Tablet**: Horizontal
    - **Mobile**: Vertical
- Footer

#### **Your Journey - Wireframes**
- **PC**: 
- **Tablet**: 
- **Mobile**:

### **2.3.4 - The Train**
Accessed by clicing the "The Train" button in the navbar. It can also be
reached by clicking the appropriate links on the ......page and ....page.

##### **The Train - Sections & Components**
- Header
- Introduction
- Up to three Info Cards about the trains' rolling stock. Two contain a table 
listing details about each engine.
    - **PC**: 3 Cards
    - **Tablet**: 2 Cards
    - **Mobile**: 2 Cards
- Footer

#### **The Train - Wireframes**
- **PC**: 
- **Tablet**: 
- **Mobile**:

### **2.3.5 - The Crew**
Accessed by clicing the "Crew" button in the navbar. It can also be
reached by clicking the appropriate links on the ......page and ....page.

#### **The Crew - Sections & Components**
- Header
- Introduction
- Up to 6 Info Cards 
    - **PC**: 6 Cards
    - **Tablet**: 4 Cards
    - **Mobile**: 6 Cards
- Footer

#### **The Crew - Wireframes**
- **PC**: 
- **Tablet**: 
- **Mobile**:

### **2.3.6 - Gallery**
Accessed by clicing the "Crew" button in the navbar. It can also be
reached by clicking the appropriate links on the ......page and ....page..

#### **Gallery - Sections & Components**
- Header
- Introduction
- Up to 12 Info Cards using the "Ticket" background for each. They contain 
video links or images and are laid out in column format.
    - Videos are displayed in the first position of each column
    - Images are displayed in all other positions
    - **PC**: 3 columns (3 videos, 9 images)
    - **Tablet**: 2 Columns (2 videos, 6 images)
    - **Mobile**: 1 Column (1 video, 9 images)
- Footer

#### **Gallery - Wireframes**
- **PC**: 
- **Tablet**: 
- **Mobile**:

### **2.3.7 Contact Us**
Accessed by clicing the "Crew" button in the navbar. It can also be
reached by clicking the appropriate links on the ......page and ....page..

#### **Contact Us - Sections & Components**
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

#### **Contact Us - Wireframes**
- **PC**: 
- **Tablet**: 
- **Mobile**:

......................

# **3 - Technologies Used**
## **3.1 - Bootstrap** 
v4.3.1 https://getbootstrap.com/docs/4.3/getting-started/introduction/
Bootstrap is used in this project for the following:
- navbar
- etc.

## **3.2 - Imgur**
All images used on this site and in this readme are stored and hosted on Cloudinary.
https://www.imgur.com

## **3.3 - Font Awesome**
v5.11.2
https://fontawesome.com/icons?d=gallery


## **3.4 - Google Fonts**
https://fonts.google.com
Google fonts is used for the following font purposes:


## **3.5 - Favicon Generator**
https://www.favicon.cc

## **3.6 - Gitpod**
This website has been constructed using Gitpod IDE

## **3.7 - GitHub Repository**
This website is hosted on GitHub
- Project Name: 
- GitHub Repository: 
- Demo Link: 

......................

# **4 - Testing**

Testing has been carried out using the following devices/browsers

- Desktop
- Chrome
- Edge
- Mozilla
- Desktop Chrome emulator
- Huawei P30 lite

## **4.1 - Page Layouts**

Rendered pages should match test screen shots for each page and each device:

- **Home Page** 
    - **PC**:
    - **Tablet**: 
    - **Mobile**: 

- **Schedule & Tickets** 
    - **PC**:
    - **Tablet**: 
    - **Mobile**: 

- **Your Journey** 
    - **PC**:
    - **Tablet**: 
    - **Mobile**: 

- **The Train** 
    - **PC**:
    - **Tablet**: 
    - **Mobile**: 

- **The Crew** 
    - **PC**:
    - **Tablet**: 
    - **Mobile**: 

- **The Gallery** 
    - **PC**:
    - **Tablet**: 
    - **Mobile**: 

- **Contact Us** 
    - **PC**:
    - **Tablet**: 
    - **Mobile**: 

- **Home Page** 
    - **PC**:
    - **Tablet**: 
    - **Mobile**: 

## **4.2 - Test: Header**

### **4.2.1 - Site Logo**
- **Test**: Click on logo on each page
    - **Result**: User is returned to the Home Page

### **4.2.2 - Navbar Navigation**
- **Test**: Click on "Home" link in navbar
    - **Result**: Verify page navigates to "Home" page
- **Test**: Click on "Schedule & Tickets" link in navbar
    - **Result**: Verify page navigates to "Schedule & Tickets" page
- **Test**: Click on "Your Journey" link in navbar
    - **Result**: Verify page navigates to "Your Journey" page
- **Test**: Click on "Crew" link in navbar
    - **Result**: Verify page navigates to "Crew" page
- **Test**: Click on "The Train" link in navbar
    - **Result**: Verify page navigates to "The Train" page
- **Test**: Click on "Gallery" link in navbar
    - **Result**: Verify page navigates to "Gallery" page
- **Test**: Click on "Contact Us" link in navbar
    - **Result**: Verify page navigates to "Contact Us" page

## **4.3 - Test: Footer**
- **Test**: Click on 'RPSI" crest=
    - **Result**: Verify https://www.instagram.com/steamtrainsireland/ opens in a new tab
- **Test**: Click on 'Facebook' icon
    - **Result**: Verify https://www.facebook.com/steamtrainsireland/ opens in a new tab
- **Test**: Click on 'Twitter' icon
    - **Result**: - **Result**: Verify https://twitter.com/RPSITrains opens in a new tab
- **Test**: Click on 'Instagram' icon
    - **Result**: Verify https://www.instagram.com/steamtrainsireland/ opens in a new tab
- **Test**: Add an email address to the "Newsletter" sign-up field and "Submit"
    - **Result**: 
        - Field authenticates email address
        - Email sent notification Displays
        - Email address is received by website admin

## **4.4 - Test: Videos Functionality**

- **Test**: Click on each video
    - **Result**: Video opens and plays in a new window with audio

## **4.5 - Test: Images Functionality**

- **Test**: Click on each image
    - **Result**: Image opens in a new window

## **4.5 - Test: Contact Us Form**

### **4.5.1 - Test 1: Test that fields are set as Required Fields**
- **Test**: Navigate to 'Contact Us' section and click the 'Submit' button without completing
any fields.
    - **Result**: Verify 'Field required' message is displayed for empty fields 
        - Name
        - Email
        - Say what you want
- **Test**:  Enter text into Name field and click 'Submit' button
    - **Result**: Verify 'Field required' message is displayed for empty field (Email)
- **Test**:  Enter text into Email field and click 'Submit' button
    - **Result**: Verify 'Field required' message is displayed for empty field (Name)

### **4.5.2 - Test 2 - Test that Email field is set for email format**
- **Test**: Navigate to 'Contact Us' section, enter text to Name field. Enter text without 
@ symbol to Email field.
    - **Result**: Verify error message is displayed
- **Test**: Enter text with @ symbol to Email field
    - **Result**: Verify Form submission accepted (for test purposes the page page refreshes)

......................

# **5 - Deployment**

This website is deployed on Github pages. Deployment to my GitHub pages is done via the AWS Cloud9 IDE using git in the terminal window.

## **5.1 - Deployment steps**
Using the terminal window add the files to the temporary git directory using the [git .] command.
These files can then be committed to the git repository using the [git commit -m""] command.
Deployment is then made to GitHub pages using the [git push] command.

All versions are held on the master branch.

......................

# **6 - Credits**

## **6.1 - Content**

The text for the Home section was sourced courtesy of the Irish Rock n Roll Museum website home page https://irishrocknrollmuseum.com/museum/thin-lizzy/

## **6.2 - Media**

The discography images used in this site were obtained from:

## **6.3 - Acknowledgements**

Acknowledgements to the following in constructing this project