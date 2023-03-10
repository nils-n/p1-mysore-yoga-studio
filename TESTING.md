# TESTING 
The original Excel Testing document can be accessed via [Excel Testing Results](/assets/testing/yoga-studio-test-results.csv).

-----

## Table of Contents 

- [Tests for Functionality ](#tests-of-functionality)
    - [Results W3C HTML Validation](#results-w3c-html-validation)
    - [Results W3C CSS (Jigsaw) Validation ](#results-w3c-css-validation)
    - [Results A11y Color Test](#results-a11y-color-test)
- [Tests of User Stories  ](#tests-of-user-stories)
- [Tests for Usability   ](#tests-for-usability)
- [Tests for Compatibility ](#tests-for-compatibility)
- [Issues Found During Testing ](#issues-found-during-testing)
- [Results Chrome Lighthouse ](#results-chrome-lighthouse)

-----

## Tests of Functionality 

First, the website has been tested that it works functionally correct. All testes have passed.

<p align="center">
<img src="assets/testing/summary-functional.png"
     alt="Image with preview of Excel testing results of the functionality"
     style="max-width:800px" >
</p>

### Results W3C HTML Validation

In the table below the outputs of the W3C HTML Validation results. All tests passed. 

| Page     | Output       | Result |
| -------- |:------------:| ------:|
| Main     | <img src="assets/testing/html-w3c-home.png" alt="image of W3C Html Validation result" >  | Pass   |
| Classes  |  <img src="assets/testing/html-w3c-classes.png" alt="image of W3C Html Validation result" >   | Pass   |
| Schedule |  <img src="assets/testing/html-w3c-schedule.png" alt="image of W3C Html alidation result" >  | Pass   |
| Signup   |  <img src="assets/testing/html-w3c-signup.png" alt="image of W3C Html Validation result" >  | Pass   |
| 404   |  <img src="assets/testing/html-w3c-404.png" alt="image of W3C Html Validation result" >  | Pass   |

### Results W3C CSS Validation

In the table below the outputs of the W3C CSS Validation results. All tests passed. 


| Page     | Output       | Result |
| -------- |:------------:| ------:|
| Main     | <img src="assets/testing/css-1.png" alt="image of W3C CSS Validation result" >  | Pass   |
| Classes  |  <img src="assets/testing/css-2.png" alt="image of W3C CSS Validation result" >   | Pass   |
| Schedule |  <img src="assets/testing/css-3.png" alt="image of W3C CSS Validation result" >  | Pass   |
| Signup   |  <img src="assets/testing/css-4.png" alt="image of W3C CSS Validation result" >  | Pass   |
| 404   |  <img src="assets/testing/css-404.png" alt="image of W3C CSS Validation result" >  | Pass   |

### Results A11y Color Test

In the table below the outputs of the A11y Color Contrast Validation results of the main color contrasts of the website.

| Page     | Output       | Result |
| -------- |:------------:| ------:|
| Colors   | <img src="assets/testing/colors-1.png" alt="image of A11y color contrast validation result" >  | Pass   |
| Colors  |  <img src="assets/testing/colors-2.png" alt="image of A11y color contrast validation result" >   | Pass   |


In the table the output of the A11y Color Contrast Validation results of each page. All tests passed. 

| Page     | Output       | Result |
| -------- |:------------:| ------:|
| Main   | <img src="assets/testing/color-test-home.png" alt="image of A11y color contrast validation result" >  | Pass   |
| Classes  |  <img src="assets/testing/color-test-classes.png" alt="image of A11y color contrast validation result" >   | Pass   |
| Schedule  |  <img src="assets/testing/color-test-schedule.png" alt="image of A11y color contrast validation result" >   | Pass   |
| Signup  |  <img src="assets/testing/color-test-signup.png" alt="image of A11y color contrast validation result" >   | Pass   |
| 404  |  <img src="assets/testing/color-test-404.png" alt="image of A11y color contrast validation result" >   | Pass   |

## Tests of User Stories 

The user stories have been tested case-by-case. All tests passed. 

<p align="center">
<img src="assets/testing/summary-user-stories.png"
     alt="Image with preview of Excel testing results of the user stories"
     style="max-width:800px" >
</p>

-----

## Tests for Usability 

The website has also been tested for usability and consistency across pages, and also that all links have an appropriate aria-label for accessibility. All tests passed. 

<p align="center">
<img src="assets/testing/summary-usability.png"
     alt="Image with preview of Excel testing results of compatibility"
     style="max-width:800px" >
</p>


-----

## Tests for Compatibility 

The website has been tested for compatibility between browsers, and that the website is responsive and displays correctly on all screen sizes as specified during the design stage. 

<p align="center">
<img src="assets/testing/summary-compatibility.png"
     alt="Image with preview of Excel testing results of the usability"
     style="max-width:800px" >
</p>

-----

## Issues Found During Testing 


| Test Case | Issue       | Fix |  Result |
| --------  |:------------:| ------:| ------:|
| TC04      |  Form would be accepted with invalid Email   | Change type of input from `text` to `email` |  Solved    |
| TC05      |  Colour Contrast of Buttons on the Hero Image did not pass A11Y Validation Standard (Ratio 4:1)  | Change Background Colour using color picker, update CSS  |  Solved    |
| TC08      |  W3C CSS Validator error : Typo of padding unit (`2x` instead of `2px`) | Typo corrected    |  Solved   |
| TC11      | More interactivity and personalized would be desirable, i.e. a guest book, Yoga shop or personalized user experience.  |  at this point of the course there are no techniques available to create such content   |  Unresolved - Future Release   |
| TC14     |  2 Colour Contrast Errors found | Changed colors at the requested location of the CSS   |  Solved   |
| TC14     |  3 accessibility errors in the footer, saying "A link contains no text" | correct aria-labels at the mentioned location in the CSS file   |  Solved   |

## Results Chrome Lighthouse 

The Chrome Lighthouse Tool integrated in the Chrome Developer Tools has been applied to test the performance and accessibility of each page. 

- For all pages, it suggest to serve images in next-gen formats and to eliminate render-blocking resources.
- Accessibility scores sufficiently high across all pages 


| Page     | Result       | 
| -------- |:------------:| 
| Main   | <img src="assets/testing/lighthouse-main.png" alt="image of result of chrome lighthouse test" >  | 
|        |  Performance scores a bit low. Lighthouse suggests to eliminate render-blocking resources. | 
| Classes   | <img src="assets/testing/lighthouse-classes.png" alt="image of result of chrome lighthouse test" >  | 
|        |  Performance scores a bit low. Lighthouse suggests to eliminate render-blocking resources.  | 
| Schedule   | <img src="assets/testing/lighthouse-schedule.png" alt="image of result of chrome lighthouse test" >  | 
|        |  Lighthouse suggests to eliminate render-blocking resources.  | 
| Signup   | <img src="assets/testing/lighthouse-signup.png" alt="image of result of chrome lighthouse test" >  | 
|        |  Lighthouse suggests to eliminate render-blocking resources.   | 
| 404   | <img src="assets/testing/lighthouse-404.png" alt="image of result of chrome lighthouse test" >  | 
|        |  Lighthouse suggests to eliminate render-blocking resources.    | 

