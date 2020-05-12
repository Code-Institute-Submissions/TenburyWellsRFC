# Tenbury Wells RFC

![Site Preview](assets/images/tenburyrfc-preview.png)
---

## [Project Repository](https://github.com/filleben/TenburyWellsRFC)

## [Deployed Site](https://filleben.github.io/TenburyWellsRFC/)
---

This project is for my local rugby team based in Tenbury Wells, they currently use a generic Pitchero site like many other clubs around them. The goal of this project is to make the club stand out with their site, as well as providing clear information for users, such as upcoming fixtures and results, club news, squad details and include contact details for any interested players, fans or sponsors.

## Table of Contents

- <a href="#ux">UX</a>
- <a href="#features">Features</a>
- <a href="#technologies">Technologies Used</a>
- <a href="#testing">Testing</a>
- <a href="#deployment">Deployment</a>
- <a href="#credits">Credits</a>

<span id="ux"></span>
## UX

### User Goals

I expect that the majority of the users will fall into the following criteria:

- Be a player or coach from either Tenbury Wells RFC or a rival club
- Be a supporter of the team
- A local player looking to join the team

### User Stories

- As a user, I want to view the latest club news, so that I can keep myself updated with the latest club news.
- As a user, I want to see the league table and results, so that I can see how the team is performing.
- As a user, I want to see the season fixtures, so that I can plan on attending the games.
- As a user, I want to be able to contact coaches, so that I can inquire about joining the team.
- As a user, I want the website to both be visually appealing and easy to navigate, so I can easily find information and navigate to different pages.
- As a user, I want to be able to view the current squad, so that I can see what positions the team might need and see who is in the current squad.

### Wireframes

[Here](https://github.com/filleben/TenburyWellsRFC/tree/master/wireframes/initial-designs) are the initial designs I made for the site.

When I was making the site I made a few design changes which I believe improved both the visuals and ease of use. The major changes are:

- Removed the title text and centered the navbar on all pages.
- Moved the results and fixtures to below the league table on the results page.
- Added an image carousel to the squad page.
- Added the 4th page with contact information, map, and a contact form.

The final designs of the site can be found [here](https://github.com/filleben/TenburyWellsRFC/tree/master/wireframes/final-designs)

The wireframes were made using [Balsamiq](https://balsamiq.cloud)

### Design Choices

- **Font**: I wanted to use a single minimal font throughout the site, with this in mind I decided to use [Roboto Condensed](https://fonts.google.com/specimen/Roboto+Condensed?query=robot) from [Google Fonts](https://fonts.google.com/).

- **Colours**: I wanted the site to follow the Tenbury kit colors which are white black and green, I used white as a background color with black text, dark green (Hex:'#005214' RGB:'rgb(0, 82, 20)') for things like the block divider, title text, and buttons, with a lighter green (Hex:'#90ee90' RGB:'rgb(144, 238, 144)') for highlighting text and button hovering. Upon completion of the site I received feedback suggesting to change the background color as it was very bright and therefor difficult on the eyes, so I decided to change the background color from white to light grey (Hex:'#d8d8d8' RGB:'rgb(216, 216, 216)'). With this change, I also edited the sponsor images to better fit with the new background color and uploaded them to the repository.

<span id="features"></span>
## Features

- **Navigation bar**: Allows the user to navigate to all the pages of the site, consistent throughout the site.
- **News Section**: Allows users to view the four latest news articles so they can stay updated.
- **Footer**: Contains links to all the club's social media accounts, consistent throughout the site.
- **League Table**: Allows users to easily visualize the team's performance throughout the season.
- **Results and Fixtures**: Allows users to see the upcoming fixtures and past results so that they could potentially attend upcoming matches.
- **Squad Page**: Allows the user to view the current coaches and players, so that they can see what positions the squad needs and who the coaches are.
- **Image Carousel**: Shows users different squad pictures.
- **Embedded Google Map**: Allows the users to view where the club is based and get directions to it.
- **Contact Form**: Allows users to contact the club directly from the website so that they can ask about anything.

### Features Left to Implement

- Read Me buttons setup to expand the news article on the home page.
- Add a news archive so that more than the latest four articles can be view on the site.
- Add player stats to the squad page could potentially add a page for each player.
- Fixtures, Results, and League Table to automatically pull information from the RFU website.

<span id="technologies"></span>
## Technologies Used

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
  - The project uses **HTML5** to provide the content and structure.

- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
  - The project uses **CSS3** for styling.

- [Bootstrap](https://getbootstrap.com/)
  - The project uses **Bootstrap** for layout, responsiveness and elements.

- [Hover.css](https://ianlunn.github.io/Hover/)
  - The project uses **Hover.css** for hover effects on links.

- [Font Awesome](https://fontawesome.com)
  - The project uses **Font Awesome** for social link icons.

- [Google Fonts](https://fonts.google.com/)
  - The project uses **Google Fonts** to provide the font used on the site.

- [jQuery](https://jquery.com)
  - The project uses **jQuery** for the navbar and the image carousel.

- [JavaScript](https://jquery.com)
  - The project uses **JavaScript** for the navbar scrolling effect.

- [GitPod](https://gitpod.io/)
  - The project devloped in  **GitPod**.

- [Git](https://git-scm.com/)
  - The project uses **Git** for version control.

- [GitHub](https://github.com/)
  - The project uses **GitHub** to host the repository and for the live preview of the site.

<span id="testing"></span>
## Testing

### Testing Tools

#### I used the following tools and devices to test the website in several different scenarios. 

- [Firefox Developer Tools](https://developer.mozilla.org/en-US/docs/Tools)
  - The project used **Firefox Developer Tools** to test responsiveness, styles, and different layouts throughout development. This also allowed the site to be tested on several [mobile devices](https://developer.mozilla.org/en-US/docs/Tools/Responsive_Design_Mode).

- [Samsung Note 10+](https://en.wikipedia.org/wiki/Samsung_Galaxy_Note_10)
  - The project used a **Samsung Note 10+** to test the site on a mobile device.

- [HP Envy x360 13](https://www.amazon.co.uk/HP-13-ar0001na-Touch-Screen-Convertible-Laptop/dp/B07V3J1H3V)
  - The project used an **HP Envy x360 13** to test the site on both a 13-inch laptop and a tablet.

I used the following web browsers on both desktop and mobile where available.

- [Mozilla Firefox](https://www.mozilla.org/en-GB/)

- [Google Chrome](https://www.google.com/chrome/)

- [Opera](https://www.opera.com/)

- [Microsoft Edge](https://www.microsoft.com/en-us/edge)

The project was run through both [HTML Validation](https://validator.w3.org/) and [CSS Validation](https://jigsaw.w3.org/css-validator/validator) with no errors found.

### User Story Tests

1. Latest Club News:
   1. Go to the "Home" page.
   2. Scroll down to the "News" section.
   3. View the four latest news articles.
   4. Do this for both desktop and mobile views.

2. League Table, Results, and Fixtures:
   1. Go to the "Results" page.
   2. Scroll down to the "Midlands Division 4 West Table" section.
   3. View the league table with Tenbury's position highlighted.
   4. Scroll down to the "Results and Fixtures" section.
   5. View the season results with wins and losses highlighted.
   6. View the upcoming fixtures.
   7. Do this for both desktop and mobile views.

3. Contact Coaches:
   1. Go to the "Contact" page.
   2. Scroll down to the "New Players Always Welcome" section.
   3. View the contact information and the google map, zoom in and out as much as you like.
   4. Scroll down to the "Want To Get Involved?" section.
   5. Try to submit the empty form and verify that an error message about the required fields appears.
   6. Try to submit the form with an invalid email address and verify that a relevant error message appears.
   7. Try to submit the form with all inputs valid.
   8. Do this for both desktop and mobile views.

4. View Current Squad:
   1. Go to the "Squad" page.
   2. Scroll down to the "Coaches" section.
   3. View the coaches' pictures and names.
   4. Scroll down to the "Forwards" section.
   5. View the players' pictures, names, and positions.
   6. Scroll down to the "Backs" section.
   7. View the player's pictures, names, and positions. 
   8. Do this for both desktop and mobile views.

### All tests performed with no errors found.

### Issues Found During Testing

- Sponsor images were not centered on smaller displays, fixed by adding "text-align: center;" to the "sponsor-image" class.
- Navbar menu items were cut off when viewing the site horizontally on mobile devices, fixed by adding a horizontal media rule which aligns the menu items horizontally instead of vertically.

<span id="deployment"></span>
## Deployment

To deploy this page to GitHub Pages from its [GitHub repository](https://github.com/filleben/TenburyWellsRFC), the following steps were taken: 

1. From the menu items near the top of the page, select **Settings**.
2. Scroll down to the **GitHub Pages** section.
3. Under **Source** click the drop-down menu labeled **None** and select **Master Branch**
4. On selecting Master Branch the page is automatically refreshed, the website is now deployed. 
5. Scroll back down to the **GitHub Pages** section to retrieve the link to the deployed website.
 
To clone this project from GitHub:

1. Under the repository name, click "Clone or download".
2. In the Clone with HTTPs section, copy the clone URL for the repository. 
3. Open your IDE of choice.
4. Change the current working directory to the location where you want the cloned directory to be made.
5. Type ```git clone```, and then paste the URL you copied in Step 3.
```console
git clone https://github.com/filleben/TenburyWellsRFC
```
6. Press Enter. Your local clone will be created.

Further reading and troubleshooting on cloning a repository from GitHub can be found [here](https://help.github.com/en/articles/cloning-a-repository).

<span id="credits"></span>
## Credits

### Content

- The news articles and contact information where taken from the club's current [Pitchero Site](https://www.pitchero.com/clubs/tenburyrufc).
- The navbar was taken and adapted from [Bootsnipp](https://bootsnipp.com/snippets/kl8Q3).
- The code for the text blocks on the squad page was taken and adapted from [w3schools](https://www.w3schools.com/howto/howto_css_image_text_blocks.asp)

### Media

- The images used in this site were obtained from the club's current [Pitchero Site](https://www.pitchero.com/clubs/tenburyrufc).
- The images used in this site are hosted by the club's current [Pitchero Site](https://www.pitchero.com/clubs/tenburyrufc).

### Acknowledgements

- I received inspiration for this project from the club's current [Pitchero Site](https://www.pitchero.com/clubs/tenburyrufc).
- **Gerard McBride** for helping me through the project with his advice and guidance.
- **[Richard Wells](https://github.com/D0nni387)** for hosting a call all about the readme.
    
