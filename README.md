# maids-are-more-expensive-on-sundays

Maids Are More Expensive On Sundays is a landing page for every book lover interested to know more and where to purchase the novel written by Alicia I Ciocca "Maids are more expensive on Sundays"

Maids Are More Expensive On Sundays landing page offers an introduction of the book,a link to get the book on Amazon, an author biography as well as a contact form to get in touch with the author or give a comment about the book.

The live link can be found here - https://saamauro92.github.io/maids-are-more-expensive-on-sundays/index.html


![Responsive Mockup](https://github.com/saamauro92/maids-are-more-expensive-on-sundays/raw/main/media/amIResponsive.png)

## Features 

### Existing Features

- __Navigation Bar__

  - Featured on all three pages, the full responsive navigation bar includes links to the Logo/home page, Home, about the author page and contact section and is identical in each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![header](https://github.com/saamauro92/maids-are-more-expensive-on-sundays/raw/main/media/navbar.png)

- __The main hero section__

  - The landing includes an image of the book front in one side and text in the other side with brief introduction and an action button to get the book.
  - This section introduces the user to the image and text with a fade in animation.

![Hero Section](https://github.com/saamauro92/maids-are-more-expensive-on-sundays/raw/main/media/hero.png)

- __About the book section__

  - The about the book section will allow the user to see the book sinopsis 

![About the book](https://github.com/saamauro92/maids-are-more-expensive-on-sundays/raw/main/media/aboutthebook.png)

- __Contact form section__

  - This section will allow the user to send a message/comment to the author. the user will be asked to submit their full name, email addresss and a required message in order to submit the form.
  - After submited, the form will redirect to a success page.

![Contact](https://github.com/saamauro92/maids-are-more-expensive-on-sundays/raw/main/media/contact.png)

- __The Footer__ 

  - The footer section includes links to the relevant social media sites for Maids are more expensive on Sundays. The links will open to a new tab to allow easy navigation for the user. 
  - The footer section includes links to the home page, about the author, contact form section and to get the book on amazon which will open to a new tab.
  - The footer is valuable to the user as it encourages them to keep connected via social media

![Footer](https://github.com/saamauro92/maids-are-more-expensive-on-sundays/raw/main/media/footer.png)

- __About the author Page__

  - The about the author page will provide the user with information about the author, including a profile picture.
  - This section is valuable to the user as they will be able to get the authors background to understand more about the book.

![About the author](https://github.com/saamauro92/maids-are-more-expensive-on-sundays/raw/main/media/theauthor.png)

- __Sucess Page__

  - This page will allow the user to get a feedback after submitting the contact form.


![Success page](https://github.com/saamauro92/maids-are-more-expensive-on-sundays/raw/main/media/sucess.png)

### Features Left to Implement

- __Feedback Section__ 

- This section would show users/readers feedback about the book 

## Testing 

- I tested that this landing page works in different browsers: Chrome, Firefox, Safari.
- I confirmed that the navigation, header, about the book, contact form and about the author sections are all readable and easy to understand.
- I have confirmed that the forms works: requires all the fields to be submitted and the submit button works and will redirect to success page when submitted.

## Validator Testing

 - HTML 
 -No errors were returned when passing through the official [W3C Validator](https://validator.w3.org/#validate_by_input)
 - CSS 
 -No errors were found when passing through the official [Jigsaw Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)
 - Accessibility
 -I confirmed that the colors and fonts chosen are easy to read and accesible by running it through lighthouse devtools
 ![lighthouse](https://github.com/saamauro92/maids-are-more-expensive-on-sundays/raw/main/media/lighthouse.png)



## Manual testing 

| Feature | Expect | Action | Result |
|--|--|--|--|
| Nav bar links | When clicked each page or section will open/show | Clicked each link on the Nav bar | Page/section clicked opened/show |
| Hero Action Button | When clicked will open a new tab with an amazon link | clicked the hero action button | Amazon link opened in a new tab |
| Footer links | When clicked each page or section will open/show | Clicked each link on footers menu | Page/section clicked opened/show |
| Footer Social Links | Social links icons open relevant websites in a new tab when clicked | clicked the social link icon | the link opened a new tab and to the correct site |
| Form submit Button | forms submits when submit button is clicked | clicked the submit button on the form | the form sucessfully submitted on click and redirects to a success page |
| Read more Link in hero | When clicked will smoothly scroll down to about the book sction | clicked the link in hero section | smoothly scrolled down to the about the book section |

## Bugs

**Solved bugs**

 - When passing the html code through validator I found out that some elements on the head had a closure "/" when it was not needed.
liked this: 
`<meta  charset="UTF-8"/>`
`<meta  http-equiv="X-UA-Compatible"  content="IE=edge"/>`
`<meta  name="viewport"  content="width=device-width, initial-scale=1.0"/>`
- Removing the closure slash fixed the problem.



### Unfixed Bugs

- No unfixed bugs

## UI

### Wireframes

 ![wireframe1](https://github.com/saamauro92/maids-are-more-expensive-on-sundays/raw/main/media/Wireframe1.png)
![wireframe2](https://github.com/saamauro92/maids-are-more-expensive-on-sundays/raw/main/media/Wireframe2.png)
![wireframe3](https://github.com/saamauro92/maids-are-more-expensive-on-sundays/raw/main/media/Wireframe3.png)
![wireframe4](https://github.com/saamauro92/maids-are-more-expensive-on-sundays/raw/main/media/Wireframe4.png)


## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 


## Credits
### Content
- All the relevant text was taken from the book Maids are more expensive on Sundays By Alicia I ciocca.
- Geogrotesque font was downloaded from [fontshub.pro](https://fontshub.pro)
- Source Sans Pro font was imported from [Google fonts](https://fonts.google.com/)
 - The contact form submit logic and hidden inputs code was taken from  [Web3Forms](https://web3forms.com/examples)  examples.
 - The animation fade in code was taken from this [tutorial](https://www.tutorialspoint.com/css/css_animation_fade_in.htm)
 - Favicon was downloaded from [favicon.cc](https://www.favicon.cc/?action=icon&file_id=983746)

### Media

 - The image from hero/contact form was taken from the original book Maids Are More Expensive On Sundays
 - The image of Alicia I Ciocca on About the author page was taken from the original book Maids Are More Expensive On Sundays.
 - Used [tinypng](https://tinypng.com/)   to optimized website
 - The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)






