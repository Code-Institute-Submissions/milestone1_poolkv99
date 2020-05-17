# Milestone 1 Pool'KV 99

The website is about my pool team where I play semi-professional pool billards in. You'll get a short introduction about how our team came together as well as who is in our team and which strengths each member has.

Separate the team itself will use it to see what our schedule is and when and where we have to play our matches. Additionally there is a league table to see how our team is doing this season.
<br/><br/>

## DESIGN

### FRAMEWORK
We worked with Bootstrap in the training modules, so used this for the fixtures and league tables to implement and the collapsible menu. For the rest I used CSS and HTML without custom components.

###  COLOR SCHEME
The color scheme is chose is a grey palette.

- `#777777` (light grey)
- `#555555` (dark grey)
- `#cccccc` (lightest grey)
- `#2b2b2b` (darkest grey)
- `#rgba(241, 10, 10, 0.5)` (dotted red line to stand out)
- `#fafafa` (white fonts)

###  WIREFRAMES
I used [Draw IO](https://www.draw.io) to create my wireframes and put them in a separate folder [Wireframes](https://github.com/VolkovBos/milestone1_poolkv99/tree/master/wireframes). I've included `.png` files of each page for visual representation on GitHub.

## UX

This site is for general users who want to know more about the team and team members who want to know more about fixtures and results. The site has divided these sections in different pages, with the information for the general users on the homepage. This because the team members are on the site for specific information and the general users need more generic information.
<br/>

### USER STORIES

#### Site Owner
- As a site owner I want to have the social links open in a new tab/page of the browser so the user is not lost on our website.

#### General User
- As a general user, I want to have links to the social networks of the team, so I can see more of the team.
- As a general user, I want to have a clear and obvious menu, so I can surf on the site without searching to much.
- As a general user, I want to see more information about the team, so I can get a feeling how the atmosphere is in the team.
- As a general user, I want to see what strengths the players have so I know if I can complement the team.
- As a general user, I want to see how the team is doing in the competition, so I know how many games you have to play in a season.
- As a general user, I want to have a possibility to get in contact with the team, so I can join the team.
- As a general user, I want to have a possibility to get in contact with the team, so I can start playing pool billiards.

#### Team Member
- As a team member, I want to see the past results, so I can see how our team has performed. (when I wasn't there)
- As a team member, I want to see the upcoming fixtures, so I can see when and where we have to play again.
- As a team member, I want to see the competition table, so I can see how we are doing this competition.


## Features
- On all pages there is a clear and obvious menu for the three pages.
- A navigation menu, which changes to a hamburger menu on smaller screens
- When you have the hamburger menu on smaller screens, you get a dropdown menu when clicking the hamburger icon
- On all pages there is a seperate footer.
- In the footer there is a newsletter signup possibility.
- In the footer there are social network links.


### [index.html](https://volkovbos.github.io/milestone1_poolkv99/index.html)
- There is an introduction of the team and how it came together.
- Each member is show which it's strengts.
- There is a team photo in the background.

### [league.html](https://volkovbos.github.io/milestone1_poolkv99/league.html)
- There is a schedule of upcoming fixtures, 
- Past results are shown, with a color differentiation on wins and losses.
- There is a league table.


### [contact.html](https://volkovbos.github.io/milestone1_poolkv99/contact.html)
- Contact form.
- Address information about the location.
- Google map for the location details.


## Technologies Used
Brief overview of the languages, frameworks, and other tools I've used on this project:

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
    - Semantic markup language as the shell of the site

- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
    - Cascading Style Sheets as the design of the site

- [Bootstrap](https://en.wikipedia.org/wiki/Bootstrap_(front-end_framework))
    - Components (tables and menu)

- [Font Awesome](https://fontawesome.com)
   - Use of social media icons

- [Google Fonts](https://fonts.google.com/)
    - Use of custom fonts

- [Gitpod](https://www.gitpod.io/)
    - For my development environment

- [Google](https://developers.google.com/web/tools/chrome-devtools/)
    - For my developing
    - For my testing

- [Github](https://github.com/)
    - Version control
    - Share public site

## TESTING
1. Use of the logo in the topleft corner:
    * Mobile
        1. The logo will be smaller and will stay on the same line as the hamburger icon
        2. When you find yourself on any part of the site, you can click on the logo to return to the home section
    * Tablet and desktop
        1. The logo will be normal size and will stay on the same line as the hamburger icon
        2. When you find yourself on any part of the site, you can click on the logo to return to the home section

2. Use of the navigation menu:
    * Mobile and tablet:
        1. Go to the header on the top of the page
        2. Click on the hamburger icon
        3. You will see a dropdown menu
        4. Click on a link in the dropdown menu
        5. The menu closes and the page selected will open
        6. An opened page will be underlined in the menu, whether the menu is collapsed or not 
        7. The bullets that divide the menu items are not shown when the menu is collapsed into the hamburger icon
    * Desktop:
        1. Go to the header on the top of the page
        2. You will see a line under the menu item that belongs to the page you're currently at
        3. When you hover over one of the menu items it will change to the color of that section
        4. Click on one of the menu items
        5. The page will open
        6. When you scroll to a different item then the one you where on, the line under the item will move to the link that you are now on

3. When you want to find basic info about the Pool'KV 99:
    * Mobile, Tablet, Desktop:
        1. At the home page you will find a image that gives you all the team members
        2. You can scroll down and in the section 'Who are we' you can see how the team came togeter
        3. You can scroll down and in the section 'The players' you can see who is in the team and there skills
    * Tablet:
        3. The section 'The players' is shown in smaller fonts and the background 8-ball images have more opacity for a clear view
    * Mobile:
        3. The players in section 'The players' are shown vertically beneath each other and the 8-ball images are not rendered
    

### TEST MATRIX

I used a [testing matrix](https://github.com/VolkovBos/milestone1_poolkv99/blob/master/testing/TestScriptWebsite.xlsx) in Excel from [Tim Nelson](https://github.com/TravelTimN/ci-milestone01-ucfd).

### COMBATIBILITY

I tested it across all major browsers in both desktop(laptop) and mobile configuration. Because of the covid-19 situation during the development I didn't have access to a wider desktop.

- Chrome
- Edge
- Firefox
- Safari
- Opera
- Internet Explorer

### NOTED ISSUES
n/a

## DEPLOYMENT

This project was created using Github. 
From there I used Gitpod.io to write my code.
Then I used commits to git followed by pushes to my GitHub repository.

As my final step I've deployed this project to GitHub Pages from the GitHub repository using the following steps:

1. Login to my GitHub account
2. Go to the [milestone1_poolkv99](https://volkovbos.github.io/milestone1_poolkv99) repository
3. Go to the settings-tab
4. Scroll down to the GitHub Pages section
5. At the GitHub Pages section, choose "master branch" as your source
6. The page will now automatically refresh and the repository deployed
7. You can now scroll down again to the GitHub Pages section to retrieve the link for the website

To run this project locally the following steps should be followed:

1. You can follow [milestone1_poolkv99](https://volkovbos.github.io/milestone1_poolkv99) to my repository
2. Click on the green colored button "Clone or download"
3. Copy the URL that pops up
4. In your local IDE open Git Bash
5. The next step is to change your current working directory to the location you want for your cloned directory
6. Now type in "git clone" and paste the copied URL
7. When you press Enter your local clone will be created


For this project, local deployment was not required.

## CREDITS

### Content
The idea and all the content for this page was written by myself.

### Media
The photo used on the homepage was obtained from my personal library, with permission of all team members to use this for my milestone project.

The other photos I used are from [Pixabay](https://pixabay.com/) and [PxHere](https://pxhere.com/)


### Acknowledgements

I received inspiration for this project from Love Running project in the CSS fundamentals section of the study.

[w3schools](https://www.w3schools.com/) and [StackOverflow](https://stackoverflow.com/) for research.

[embedgooglemap](https://www.embedgooglemap.net/en/) for the Google maps code.

Thanks to [Tim Nelson](https://github.com/TravelTimN/ci-milestone01-ucfd) for the testing matrix.

And a thanks to my mentor Precious Ljege who gave me honest and good feedback on my site/code and helped me te complete this project.

[w3.org](https://www.w3.org/Graphics/SVG/) for the creation of the hamburger (collapsible menu).

I used the code for the menu from [aleesang](https://aleesang.github.io/milestone-project-one).