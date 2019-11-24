# Survey Form

Welcome to the survey form.  The purpose of this project is to construct a survey form similiar to https://codepen.io/freeCodeCamp/full/VPaoNP.

## UX

The Survey Form is about a visit to a Hotel with Experiences, Event Types (e.g. Balls) and Facilities (e.g. Car Park).  If a user is
just making enquiries, the event types and facilities can be left blank.

### User Stories

As a user, I would like to see a form with a name field, an email field, a number field, radio buttons, selection of
options from a dropdown, checkboxes, textarea for additional comments and a submit button to submit all my inputs.

As a user, I am required to enter my name in the name field and my email in the email field.

As a user, if I enter an email that is not formatted correctly, I will see an HTML5 Validation Error.

As a user, if I enter non-numbers in the number input, I will see an HTML5 Validation Error.

As a user, if I enter numbers less than the minimum or greater than the maximum, I will see an HTML5 Validation Error.

As a user, I would expect placeholder text for text based fields.

A screentip is provided when the user hovers over the submit button.

### Information Architecture

Experience - Excellent, Very Good, Good, Poor, Very Poor
Event Types - Balls, City Breaks, Conferences, Exhibitions, Fairs, Parties (e.g. Birthday), Sun Breaks, Weddings and Workshops
Hotel Facilities - Gym, Car Park, Restaurant, Meeting Rooms, Toilets, Taxi Booking

Organising Principle is Interests/Services

[Wireframes](wireframes/survey-form-wireframe.png) are provided.

## Features

The survey form has form validation for name, email and number fields.

## Technologies

* HTML5
* CSS3

Other technologies include fonts.google.com for fonts such as Roboto.

## Testing

Resize the width of the browser window, to ensure that the form is responsive.  A screentip is provided when
the user hovers over the submit button.

If the name and/or email fields are blank an HTML5 Validation Error appears.

If the email is not formatted correctly, an HTML5 Validation Error appears.

If anything other than a number is entered in the number field, an HTML5 Validation Error appears.

If the number is less than the minimum value or the number is greater than the maximum value, an
HTML5 Validation Error appears.

## Deployment

The project is deployed on [GitHub Pages](https://derektypist.github.io/survey-form/) using the Master Branch.

Remote Setup use the command

    git remote add origin https://github.com/derektypist/survey-form
    
Any changes use the git push command in the terminal window.

## Credits

### Content

The contents in this project were written by me.

