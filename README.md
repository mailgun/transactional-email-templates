# Responsive transactional HTML email templates

Transactional HTML emails often get neglected. **Styling HTML email is painful**. Tables, inline CSS, unsupported CSS, desktop clients, web clients, mobile clients, various devices, various providers.

We’ve tried to remove some of the pain for you and open-sourced a collection of common templates for transactional email.

<p align="center"><img src="https://mailgun.ghost.io/content/images/2014/Aug/icons.png" width="500"></p>

* [Action email](http://mailgun.github.io/transactional-email-templates/action.html)
* [Email alert](http://mailgun.github.io/transactional-email-templates/alert.html)
* [Billing email](http://mailgun.github.io/transactional-email-templates/billing.html)

Each template is **responsive** and each has been **tested** in all the **popular email clients**.

## How to use

* Use these email templates for your transactional emails
* Use them as is or think of them as boilerplates for more detailed emails
* Ensure you [inline the CSS](#inline-the-css) before sending the email out

## What are transactional emails?

Typically any email that is triggered by or sent automatically from your application.

* Welcome emails
* Actionable emails
* Password resets
* Receipts
* Monthly invoices
* Support requests
* App error alerts
* Reminders
* etc.

## Inline the CSS

Before sending HTML emails **you should inline your CSS**.

We recommend using [Premailer](http://premailer.dialect.ca/) to accomplish this.

Our repo contains both the original templates with a separate CSS stylesheet, as well as templates with CSS already inlined for you to preview. See the `/templates/inlined` folder.

## Tested and verified

We’ve tested these email templates across all the major desktop, web and mobile clients, using Litmus. [See the test results.](https://litmus.com/pub/333e2b6/screenshots)

<img src="http://i.imgur.com/eX9fYwL.png">

## Email design workflow with Grunt

You also might be interested in this [Grunt task](https://github.com/leemunroe/grunt-email-design)  for compiling and testing html emails. We used this to help design and test our transactional emails.
