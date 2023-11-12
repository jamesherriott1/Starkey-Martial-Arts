# Starkey Martial Arts - Milestone Project 1

 This is my first webpage and also my first project for ther course. Unfortunately the project wasn't given the time needed so it's not as complete as I would have liked.

## Technologies Used For This Site

For this project I used HTML5 and CSS3.

The code was written using [Code Anywhere](<https://app.codeanywhere.com>) and [Git Hub](<https://github.com/>).

For the wire frames in this file I used Balsamiq.

## Description

This site was built for the martial arts club where I train. They relied on social media to share information so I sugeested a website where people can have an interactive experience while gathering all the information needed about the club.

All of the information you need for classes and times in 1 place.

In future I would like to add a coaches section, a logo to the header and anchors to the classes and coaches in the timetable element.

I've tried to make it as simple as possible and keep it within the colour schemes of the club.

There are bits missing which i would like to add at a later date. For example, the club logo on the header was something that was left out because of the poor design of it on Canva.

This was the original idea which I'd put together in Balsamiq.

<!--add screenshot of wireframe-->

## index.html

Tested code and got no errors. i did get an info message saying Trailing slash on void elements has no effect and interacts badly with unquoted attribute values.

To resolve the issue I removed the trailing slash where appropriate.

Copied the newly tested code to contact and timetable pages now there are no errors or info messages.

Checked nav element works on all pages correctly.

Added sections from line 33 to 77 and tested code. No errors to report.

Adeded line 78 to 115 and tested code. No errors to report.

Added footer section. Line 116 to 131. Tested code. No errors to report.

### pop up modal

Ive added a pop up modal to lines 33 to 51 which i took from [bootstrap] (https://getbootstrap.com/docs/4.0/components/modal/). I've tested the code and found no errors so I changed the text to suit my requirements.

## timetable.html

Added the h2 section to the timetable page. lines 49 to 57. Tested code and found no errors.

Added class timetable h2 section to lines 58 to 60. Tested code. No errors found.

Deleted the id's and classes from all timetable.html sections.

Added timetable section to timetable.html from line 62 to 294. I used some HTML and CSS from [101 Computing](<https://www.101computing.net/my-timetable-in-html-css/>) for the basic structure of my timetable and added or removed code as neccessary.I tested the code and found 1 error 'Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections, or else use a div element instead for any cases where no heading is needed'. I will add a h2 and see what happens.

Added a h2 element inside the timetable section on line 63. Tested code. No errors found.

Deleted h2 from line 58 to 60 in timetable.html as it was meant to be inside the section.

## contact.html

Ive added the 'contact us' h2 to the contact.html page on line 32. I tested the code and got the same message about the trailing slash as I didnt copy and paste the edited version of the code over after correcting it on the index.html page. Ive corrected and retested and have no errors.

Added the form section back into contact.html on lines 33 to 44. Tested the code and got the trailing slash message again but this time it was on the form. I also got the same message as before on the timetable secton advising me there was no h2 - h6 element inside the section. I'll change that and see what happens.

I've moved the h2 inside the form section and removed the trailing slashes and retested the code and there are no errors found.

I added the code for the submit button on line 45 to 47 and again got the message about th h2 - h6. this time I changed the section to a div instead of adding a h element and retested the code. No errors to report.

<!--There were some styling issues with the submit button being inside my form element so I Googled how to put it outside and styled it.
I got the code from [Dev Diaries](https://www.dev-diaries.com/social-posts/html-submit-button-outside-form/#:~:text=For%20a%20HTML%20form%20element,with%20the%20button's%20form%20property.)
-->

## CSS

I've added some style to the main page. I've added a font family and background image and some style to the header id and h1. Tested css and found no errors
<!--add screenshot of page with style-->
Added menu and logo id's to the style.ccs file. I also added the menu id to the unordered list inside the nav.

Added id and class to h2 divs and an id to the classes section. Tested the code and got an error. I left some whitespace in the myclass id. Corrected and retested, no errors found. 

added the cover text id to the css file and tested it. No errors found, but i do keep seeing the same warning and I'm not quite sure what it means. The page is starting to come together in the browser too.
<!--add screen shots of css warning and web page-->