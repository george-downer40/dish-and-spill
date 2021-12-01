# Dish & Spill

[Link to live site](https://george-downer40.github.io/dish-and-spill/)

[Link to my Github](https://github.com/george-downer40)

The purpose of this website is to showcase the restaurant ‘Dish & Spill’. The restaurant is focussed around a community feel with an emphasis on ‘family style’ eating. This sets the restaurant apart from other locations and the website is designed to emphasise that community feel. It is designed to be intuitive and user friendly, allowing visitors to easily learn about the restaurant, its menu, and its community purpose.

![am i responsive](/docs/screenshots/am-i-responsive-image.png "responsiveness example")

## User Stories

* As a visiting user, I want to learn about the restaurant, in particular the food served, the location of the restaurant and its opening times, so that I can decide if this is a somewhere I  would like to eat, and if its opening times align with my upcoming plans.
* As a returning customer (assuming I have dined here before), I want to check if there are any new additions to the seasonal menu, and that the opening times are still viable for my schedule.
* As a visiting user who is looking for something different to a standard restaurant I want to learn more about the community aspect of Dish & Spill.

## Features

* Navigation Bar
    * The navigation icons will underline when hovered over for easy navigation. The navigation icons are available on every page on the site ensuring a user can navigate to the section they wish to view easily.

![picture of navigation bar](/docs/screenshots/nav-bar.png "navigation bar")

* Menu Page
    * As the site is for a restaurant, a dedicated menu page is very important and provides great value to a visiting user.

![picture of menu](/docs/screenshots/menu-page.png "menu page")

* Contact Form
    * The contact form provides a visiting user an easy way to leave feedback for the restaurant.

![picture of contact form](/docs/screenshots/contact-form.png "contact form")

* Form Submission Page
    * The contact form links to a form submission page thanking the user for leaving feedback. This allows the user to return to either the index page or another page rather than being stuck on a thank you page.

![picture of thank you page](/docs/screenshots/form-submission-page.png "submission page")

* Footer
    * The footer contains links to social media channels for the restaurant. These open in a new tab to ensure the user can still access the Dish & Spill site easily.

![picture of footer](/docs/screenshots/footer.png "footer")

## Colours & Typography

The colours chosen are designed to inspire both cleanliness and relaxation. The typography used (Overlock & Caveat) are intended to complement the site's colours and give the restaurant a slightly informal and friendly design.

## Future Features

In the future, the addition of a booking page and an option to sign up to a newsletter would greatly improve the site. The booking page would ensure that users can make a reservation while still on the site, and the newsletter sign up would keep visiting users who like the restaurant updated with menu changes and events, ensuring returning customers.

## Testing
### Validator Testing

All html and css code has been run through the W3C validator (for html) and the Jigsaw validator (for css).

![picture of W3C results](/docs/screenshots/w3-validator-no-errors.png "W3C results")

![picture of Jigsaw results](/docs/screenshots/jigsaw-results.png "Jigsaw results")

### Lighthouse

The site was also tested using the Lighthouse feature on Chrome Developer Tools, scoring 97.

![picture of lighthouse results](/docs/screenshots/lighthouse-score.png "lighthouse score")

### Programs & Devices

* The site was tested on Chrome.
    * The site was also tested on a Windows desktop, Samsung S8 Plus and an iPhone 12

### Responsiveness

The site was tested for responsiveness using Chrome Developer Tools, and has 6 media queries in the css style sheet at various widths to ensure maximum compatibility on as many devices and screen sizes as possible.

### Bugs

When testing the form on the feedback page, the form method POST would bring up an error message and an attempted submission would not lead to the thank you page. This was resolved by removing the POST method from the form element, as for the purpose of this project, it wasn't neccessary.

When the html code was initally run through the W3C validator, a warning message was given recommending a h1, h2, h3 etc. element was added. This was not needed on the site though and was resolved by including an aria-label attribute in the code that caused the warning.

![picture of w3c warning](/docs/screenshots/index.html-w3-validation-error.png "w3c warning")






