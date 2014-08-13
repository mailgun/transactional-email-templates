# Responsive Transactional HTML email templates

Transactional HTML emails often get neglected. **Styling HTML email is painful**. Tables, inline CSS, unsupported CSS, desktop clients, web clients, mobile clients, various devices, various providers.

<p align="center"><img src="https://mailgun.ghost.io/content/images/2014/Aug/icons.png" width="500"></p>

* [Action email](http://mailgun.github.io/transactional-email-templates/action.html)
* [Email alert](http://mailgun.github.io/transactional-email-templates/alert.html)
* [Billing email](http://mailgun.github.io/transactional-email-templates/billing.html)

We’ve tried to remove some of the pain for you and open-sourced a collection of common templates for transactional email.

Each template is **responsive** and each has been **tested** in all the **popular email clients**.

## Inline the CSS

Before sending HTML emails **you should inline your CSS**. 

We recommend using [Premailer](http://premailer.dialect.ca/) to accomplish this.

Our repo contains both the original templates with a separate CSS stylesheet, as well as templates with CSS already inlined. See the `/inlined` folder.

## Tested and verified

We’ve tested these email templates across all the major desktop, web and mobile clients, using Litmus. [See the test results.](https://litmus.com/pub/3a573b5/screenshots)

## Email design workflow with Grunt

You also might be interested in this [Grunt task for compiling and testing html emails](https://github.com/leemunroe/grunt-email-design). This is what we used to design and test our transactional emails.
