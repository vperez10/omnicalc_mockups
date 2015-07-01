# Omnicalc Mockups

The goal of this project is to practice using Bootstrap to layout and style our pages.

## Introduction

There are eight files in this repository:

- word_count/new.html
- word_count/results.html
- loan_payment/new.html
- loan_payment/results.html
- time_between/new.html
- time_between/results.html
- descriptive_statistics/new.html
- descriptive_statistics/results.html

These are blank HTML documents except that they are already linked to Bootstrap and Font Awesome.

Your job is to make static mockups of the following targets:

 - https://omnicalc-target.herokuapp.com/word_count/new
 - https://omnicalc-target.herokuapp.com/word_count/results
 - https://omnicalc-target.herokuapp.com/loan_payment/new
 - https://omnicalc-target.herokuapp.com/loan_payment/results
 - https://omnicalc-target.herokuapp.com/time_between/new
 - https://omnicalc-target.herokuapp.com/time_between/results
 - https://omnicalc-target.herokuapp.com/descriptive_statistics/new
 - https://omnicalc-target.herokuapp.com/descriptive_statistics/results

Your mockups won't actually perform the calculations, of course, but try to make them *look* as close to the targets as possible. Also, don't attempt the calendar-datepicker-popup on `time_between/new.html` yet.

If you need to write any custom CSS beyond vanilla Bootstrap, you can do so in `custom_styles.css`, which is already linked to all eight documents.

We'll bring our static mockups to life soon.

## Setup

 - Fork and clone this repository.
 - Open the entire folder in Sublime.
 - In Chrome, open the file you are working on in one tab and your target in another tab.

## Steps

 - Add the [navbar](http://getbootstrap.com/components/#navbar) to the top. The example code includes every possible use-case, but try to go through and figure out which bits to eliminate and which bits to modify to match our target.
 - Create the basic grid skeleton. [Shoelace.io](http://shoelace.io/) may come in handy.
 - Add the [list of links](http://getbootstrap.com/components/#list-group-linked) to the left side. Since the documents are located in different folders, you need to use [relative file paths](https://css-tricks.com/quick-reminder-about-file-paths/) to make the links work.
 - Add a [panel](http://getbootstrap.com/components/#panels-heading) to the right side.
 - Add content to the panel body; either a [form](http://getbootstrap.com/css/#forms-horizontal) or a [description list](http://getbootstrap.com/css/#horizontal-description), depending on which page you are working on.
 - Include [Font Awesome icons](http://fortawesome.github.io/Font-Awesome/icons/) where appropriate.
 - Make it [Responsive](http://getbootstrap.com/css/#responsive-utilities):
  - On extra-small and small screens, hide the left nav.
  - On medium and large screens, hide the navbar links (since the left nav is visible).
 - When a form submit button is clicked, make it so that you end up at the corresponding results page.
 - Experiment with different [Bootswatches](https://bootswatch.com/).

