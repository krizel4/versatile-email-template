# Versatile Email Template
This table contains mobile responsive alternating tables and optional rounded buttons. Because e-mail clients haven't found a way to agree with each other, this is as "versatile" as I've gotten with design. A lot of the bells and whistles that modern web offers, like accordians, carousels, and video embeds, can only be done in *some* e-mail clients. Unfortunately, not every e-mail client displays these features properly. Thus, this "versatile" layout is created to viewer-friendly in Outlook, Gmail, Yahoo, Apple Mail, and more.

## About the Code:
* Responsive
* Embeds Roboto and has a backup font for Outlook
* Conditional MSO logic to display rounded buttons
* Alternating tables that stack properly in mobile

## Email HTML
If you're a web developer not familiar with email HTML, prepare for heartbreak and traveling back in "coding" time. E-mail clients have different preprocessing engines, and you unfortunately have to surrender to coding practices that go against the typical clean code you see in modern web development. To ensure your e-mail is as faithful as possible to the designer's layout, there's inline styling, CSS selectors, an excessive use of !important, conditional MSO statements and some legacy code. Outlook is perhaps one of the most challenging e-mail clients to code for, because it still processes the code through Word.

## Resources
Here are a few resources I've referred to over the years to build this template.
* *Divs and Ghosts Tables*: <https://webdesign.tutsplus.com/tutorials/html-email-using-ghost-tables--cms-32551>
* *Mobile Responsive Email Stacking*: <https://www.litmus.com/blog/mobile-responsive-email-stacking>
* *Bullet Proof Email Buttons*: <https://www.litmus.com/blog/a-guide-to-bulletproof-buttons-in-email-design>

## Future Development
* Dark mode design.
* Code clean-up. This is a working design, so some tables/rows/cells have some desperate looking inline styling added to it to force visuals. Some of the code may not be necessary, so this will need to be cleaned in the future to reduce the file size.

