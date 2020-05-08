# Tenbury Wells RFC - Milestone 1 Project

![Site Preview](assets/images/TenburyRFC-preview.png)
---

This project is for my local rugby team based in Tenbury Wells, they currently use a generic Pitchero site like many other clubs around them. The goal of this project is to make the club standout with their own site, aswell as providing clear information for users, such as upcoming fixtures and results, club news, squad detials and include contact detials for any interested players, fans or sponsors.

## UX

### User Goals

I expect that the majority of the users will fall into the following criteria:

- Be a player or coach from either Tenbury Wells RFC or a rival club
- Be a supporter of the team
- A local player looking to join the team

### User Stories

- As a user I want to view the latest club news, so that I can keep myself updated with the latest club news.
- As a user I want to see the league table and results, so that I can see how the team is performing.
- As a user I want to see the season fixtures, so that I can plan on attending the games.
- As a user I want to be able to contact coaches, so that I can inquire about joining the team.
- As a user I want the wesbite to both be visually appealing and easy to navigate, so I can easily find information and navigate to different pages.
- As a user I want to be able to view the current squad, so that I can see what positions the team might need and see who is in the current squad.

### Wireframes

[Here](https://github.com/filleben/TenburyWellsRFC/tree/master/assets/wireframes/initial-designs) are initial designs I made for the site.

When I was making the site I made a few design changes which I believe improved both the visuals and ease of use. The major changes are:

- Removed the title text and centered the navabar on all pages.
- Moved the results and fixtures to below the league table on the results page.
- Added a image carousel to the squad page.
- Added a 4th page with contact information, map and contact form.

The final designs of the site can be found [here](https://github.com/filleben/TenburyWellsRFC/tree/master/assets/wireframes/final-designs)

The wireframes were made using [Balsamiq](https://balsamiq.cloud)

### Design Choices

- **Font**: I wanted to use a single minimal font throughout the site, with this in mind I decided to use [Roboto Condensed](https://fonts.google.com/specimen/Roboto+Condensed?query=robot) from [Google Fonts](https://fonts.google.com/).

- **Colours**: I wanted the the site to follow the Tenbury kit colours which are white black and green, I used white as a background colour with black text, dark green (#005214) for things like the block divider, title text and buttons, with a lighter green (#90ee90) for highlight text.

## Features

- **Navigation bar**: Allows user to navigate to all the pages of the site, consistent thoughout the site.
- **News Section**: Allows users to view the four latest news articles so they can stay updated.
- **Footer**: Contains links to all the clubs social media accounts, consistent thoughout the site.
- **League Table**: Allows users to easily visualise the teams performance thoughout the season.
- **Results and Fixtures**: Allows users to see the upcoming fixtures and past results, so that they could potenially attend upcoming matches.
- **Squad Page**: Allows user to view the current coaches and players, so that they can see what positions the squad needs and who the coaches are.
- **Image Carousel**: Shows users different squad pictures.
- **Embedded Google Map**: Allows the users to view where the club is based and get directions to it.
- **Contact Form**: Allows users to contact the club directly from the website, so that they can ask about anything.

### Features Left to Implement

- Read Me buttons setup to expand the news article on the home page.
- Add a news archive so that more than the lasest four articles can be view on the site.
- Add player stats to the squad page could potenially add a page for each player.
- Fixtures, Results and League Table to automatically pull information from the RFU website.

## Technologies Used

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
  - The project uses **HTML5** to provide the content and structure.

- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
  - The project uses **CSS3** for styling.

- [Bootstrap](https://getbootstrap.com/)
  - The project uses **Bootstrap** for layout and responsiveness.

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

## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
   1. Go to the "Contact Us" page
   2. Try to submit the empty form and verify that an error message about the required fields appears
   3. Try to submit the form with an invalid email address and verify that a relevant error message appears
   4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.

## Credits

### Content

- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media

- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X
