![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


# Love Riot 💘 by Cupid&Co

## Intro

In the name of all things ***RoMaNcE*** this Valentine's February, The **Love Riot** web app showcases the **Love Compatibility Calculator**.
Based on zodiac star sign compatibility, users can calculate a potential compatibility score with their partner or crush and send the results on by email.

Compatibility scoring is displayed as a percentage match of the astrological star-signs of each person - adapted from [numerologysign.com](https://numerologysign.com/zodiac-signs-compatibility/)!

------


## Showcase

![Am I Responsive?](documentation/readme/am-i-responsive.webp "Am I Responsive? Website Mockup")

The **Am I Responsive?** link can be found here - [Am I Responsive?](#)

A **deployed link** to the live website can be found here [Love Riot](https://yamesjamess.github.io/feb-24-hackathon-love-riot/#)

---


# Site Goals


## Problem Statement

When it comes to the complexities of love and relationships, many people 'look to the stars' in order to analyse the potential of a budding romance between two people. We decided to build our Valentine's themed application as a Love Compatibility Calculator which is both fun to use and shares some insights into the compatibility of the astrological star-signs.


## Objectives

In the spirit of Valentine's day, our objective was to create a functioning love compatibility calculator game which displays a percentage compatibility score after the user has input two names and two zodiac star-signs.

### Target Audience

The target audience of this game is anyone interested in learning about astrolgical star-sign compatibility in romantic relationships. It can also be played as a light hearted game for all ages, especially around Valentine's Day, where the results can be forwarded to friends (or a crush) by email.

### User Requirements and Expectations

- Simple and intuitive user interface
- Explanation of how the site works is easy to understand
- Calulator game works as expected and is fun to play
- Clear presentation of the content
- Option to learn more about the page / access help with knowing which star-sign to choose
- Design that is visually attractive
- Accessibility
- Features and navigation system works as expected

### User Stories

As a user I would like:
- to understand what the app is about and how to use it.
- to calculate a love compatibility score using the interactive calculator on screen.
- for the animation and scoring to appear smoothly and accurately.
- to have some help with choosing the correct star sign for myself or my crush.
- to navigate through the elements of the game / website easily
- the option to access more information about the app and Cupid&Co.
- to enjoy the experience of using the site with a visually appealing format.


## Trade Offs

Considering the user requirements and expectations, the table below shows the features that should be implemented to make an appealing and functional interactive Love Calculator for users. Due to time constraints and my current skill level, some of these features are not implemented at this stage.

[X] indicates opportunities that were considered at the planning stage but were deemed not viable/feasible for this project sprint.
Y / N indicates a Yes / No as to whether each opportunity was acheived and implemented at this stage.

| Opportunity                                                                | Importance | Viability / Feasibility | Outcome |
| ---------------------------------------------------------------------------- | :--------: | :---------------------: | :------:|
| Love Calculator game grid for interactive compatibility scoring              |     5      |            5            |    Y    |
| About page for more information about the Cupid&Co Team                      |     4      |            5            |    Y    |
| Landing page (before starting the game)                                      |     4      |            5            |    Y    |
| Functioning user input form for game calculation                             |     5      |            5            |    Y    |
| Loading spinner during calculation process                                   |     4      |            5            |    Y    |
| Visual indicator of compatibility result                                     |     3      |            5            |    Y    |
| Info modal to give users guidance on selecting the correct star-sign         |     5      |            5            |    Y    |
| Reset option that clears the calculator form                                 |     5      |            5            |    Y    |
| Option to send results by email to a friend (via an email form)              |     4      |            5            |    Y    |
| Results page with in-depth descriptions of zodiac pair compatibility [X]     |     3      |            2            |    X    |


### Features

- **Feature 1**

    -

    ![screenshot](#)

- **Feature 2**

    -

    ![screenshot](#) 


- **Feature 3**

    - 

    ![screenshot](#)


### Future Features

- Adding a horoscope API for generating detailed compatility / prediction reports along with the compatibility score.
- Adding a pricing page for user to subscribe to our services such as reiki healing, cosmic realignment etc.

## Wireframes

Wireframes for the website were created using the UI wireframe tool, [Balsamiq](https://balsamiq.com/), to plan the layout with a mobile-first approach.

The layout and design was kept consistent across the pages / devices as much as possible.

**Mobile Device Love Calculator with pre-game layout (left) and results page layout (right)**:

![wireframes](/documentation/readme/mobile-wireframes-love-calculator.jpg)

**Note** - The square boxes with X inside was used to illustrate a decorative / animated image. And in the early planning stages we had not yet decided between using 'birthdate' or 'star-sign' user input.


## Compatibility Scoring

The JS logic used to calculate the percentage compatibility scores were based on the Zodiac Signs Compatibility page by [numerologysign.com] (https://numerologysign.com/zodiac-signs-compatibility/).

We initially decided on calculating our own scores based on a compatibility grid such as this one from [astrology-zodiac-signs](https://www.astrology-zodiac-signs.com/images/zodiac-signs-compatibility-chart.png):

![planning stage compatibility grid](/documentation/readme/zodiac-compatibility-chart1.png)

However, we decided it was easier to calculate scores based on numerical data from a similar grid found at [numerologysigns.com](https://numerologysign.com/zodiac-signs-compatibility/):

![compatibility data grid used for final calculations](/documentation/readme/zodiac-compatibility-chart2.png)

The data for zodiac pairs was transcribed into a JS object (compatibilityData) which was then used in the calculation functionality of javascript.

To display different visuals associated with positive / negative scores, 'if/else' statements were run in the JS script depending on % brackets.

## Sending Results by Email




## Brand Identity


**Brand name and Logo options:**

The following details were decided as a Team:

Brand name: **Cupid&Co**

And app name: **Love Riot**

Logo image:

![screenshot of logo](/documentation/readme/logo-image.png)

Logo with brand name (against pink website background):

![screenshot of logo with brand name](/documentation/readme/logo-brand-name.jpg)


**Byline:**


**Colour palette:**

The following colour palette was created using [Coloors](https://coolors.co/) based on the theme of 'love' :

![screenshot of colourscheme](/documentation/readme/coloors-color-scheme.png)

The following set of [Flaticon](https://www.flaticon.com/) stickers were then found which aligned well with the pink theme (see Credits for attribution):

![screenshot of love-themed stickers](/documentation/readme/flaticon-app-images.png)


## Tools and Technologies

1. HTML,
2. CSS,
3. Javascript,
4. Bootstrap,

- [GitHub and Github Pages](https://github.com/) - used to securely store the code and to host and deploy the live project
- [GitPod](https://www.gitpod.io/) - used as a cloud-based IDE for development
- [Chrome Developer Tools](https://developer.chrome.com/docs/devtools/) - used for testing and troublshooting code, along with Lighthouse auditing
- [Balsamiq](https://balsamiq.com/wireframes/) - used to create wireframes during project planning
- [Cloud Convert](https://cloudconvert.com/) - used for resizing and converting image files to webp format
- [Coolors](https://coolors.co/) - used to generate a color palette for the website design
- [Google Fonts](https://fonts.google.com/specimen/Dosis) - used to generate a visually appealing font
- [The Noun Project](https://thenounproject.com) - used for generating the logo icon
- [Flaticon](https://www.flaticon.com) - used to generate love-themed stickers
- [ChatGPT](https://chat.openai.com/) - used to help research javascript logic and for general coding queries

- [beautifytools](https://beautifytools.com/) - used for beautifying code
- [JSHint](https://jshint.com/) - used to validate JS code
- [Esprima](https://esprima.org/demo/validate.html) - used to validate JS syntax
- [W3 HTML validator](https://validator.w3.org/nu/) - used to validate HTML
- [W3 Jigsaw](https://jigsaw.w3.org/css-validator/validator) - used to validate CSS
- [AmIResponsive?](https://ui.dev/amiresponsive?url=https://tarahwaters.github.io/milestone-project2/) - used to create a mockup of the website


You can access our project on GitHub [here](https://yamesjamess.github.io/feb-24-hackathon-love-riot/#)

## Known Issues

## Credits
The following media resources were used:
- [Logo (Cupid icon) generated from The Noun Project](https://thenounproject.com/icon/cupid-5981148/)
- [Flaticon stickers](https://www.flaticon.com/free-stickers/love) created by [MrHamster](https://www.flaticon.com/authors/mrhamster?type=sticker)
- [numerologysign.com](https://numerologysign.com/wp-content/uploads/2020/09/Zodiac-Signs-List-with-Dates-Symbols-1920x1681.png) star-sign inforgraphic:
    ![star-sign infographic](/documentation/readme/numerology-star-sign-info.png)

The Cupid & Co Team:
- [Ilyas Olgun](https://github.com/ilyasolgun11)
- [James Kasetarapanya](https://github.com/yamesjamess)
- [Meghan Roberts](https://github.com/MeganRoberts-dev)
- [Melissa Buckingham](https://github.com/MelissaBuckingham)
- [Russ Smith](https://github.com/rstan-dev)
- [Tarah Waters](https://github.com/tarahwaters)
