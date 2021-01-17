# MS1 - FORPEX webpage

New webpage for existing Czech family firm FORPEX.
 
## UX

FORPEX is a Czech family firm established in 1993. FORPEX specialises in printing. FORPEX was in the past rather succesfull, but nowadays with lower demends for printed materials the family focuses on other businesses has established other rather succesfull firm and FORPEX kind got left behind. The business is running, but needs some face-lifting including new web-page. 

USER STORIES: 

The owners family expects from new web-page:
- mainly display, that the firm exists, business still runs
- because the firm works with prints and design, the web-page must present certain level of design qualities.
- based on their experience, they need to talk to the (potenital) clients or exchange emails, they do not want any web-form, questionaire etc., they want client to call them or write a direct email.
- their clients are usually banks and state officess so the web-page shoud be visualy down-to-earth, representing more stability and realiability than creativity and pioneering.
- it is clear, that at the moment the other businesses of the owners family have priority, so the webpage can not demand any maitnance or activity from the family members.

The user (potentional client) should from this new webpage:
- learn a basic info about FORPEX and field of its expertese
- get a feeling, that the firm has an eye for design and looks stabile and reliable
- get simple and direct way, how to get in touch with the firm - phone, email

Here are wireframes I created at the very beginning of the process (they slightly vary from the final result) http://bit.ly/38PHIfo

## Features

- Scroll-down page: the whole page is one scroll-down page with sereval sections (listed below). The project has also second page - which is just translation in Czech language since FORPEX is a Czech firm and its clients are often Czechs. 
Since FORPEX is print-oriented firm, I used this scroll-down effect with fixed background and several empty bars (holes in the scrolling layer) between each section so they create remotly effect of a printing head scrolling over a paper. The empty bars are reduced in the mobile-size version of the page. 

Sections:

- Header - simple navigation bar with logo and language option
- Home page - simple HL and background 
- About us - simple description of the services FORPEX offers with yellow bar underlining FOPREX's expertese
- Printing solutions - simple description of 3 main printing areas FORPEX provides
- Rerefences - logos of main clients (mainly known Czech banks and state offices)
- Contact - simple contact page with contact info and google-map embaded


### Features Left to Implement
- according to my quick research, Javascript offer smoother nad visually more atractive movement while scrolling - since I am not able to use Javascript yet, I could dont implement it already, but I am ready to make the crolling smoother in the future.

- from javascript I also expect to learn and implement how to give some interesting slight movement to the images while scrolling.

## Technologies Used

The whole page was built with HTML and CSS. Other sources:

- [Bootstrap] (v5.0x) (https://getbootstrap.com/) For some particular details (grid, list-inline etc.)
- [FontAwesome] (https://fontawesome.com/) for using icons
- [GoogleFonts] (https://fonts.google.com/) to use Montserrat font 
- [GoogleMaps] (https://www.google.com/maps) to use embaded map of the firm address


## Testing - to be done

https://validator.w3.org/nu/#textarea - Document checking completed. No errors or warnings to show.

http://jigsaw.w3.org/css-validator/validator$link -  Congratulations! No Error Found.

<!-- In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here. -->

## Deployment - to be done

<!-- This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally. -->


## Credits

### Content

- all the texts were created by me with cooperation with the owners family members

### Media
- The photos used in this site were obtained from https://depositphotos.com/ and the owners family owns full usage rights for all used images

- the Czech and English icons (language switch button) were downloaded from https://www.countryflags.com/

### Acknowledgements

- I was planning to use hamburger-icon manu for small media-size from this tutorial https://medium.com/@lizfaria/create-a-responsive-dropdown-menu-in-html-css-in-ten-steps-fdb4aa906978, but at the end I decided that simple drop-down menu would be more suitable for this kind of webpage, so I did not use any code from the tutorial.