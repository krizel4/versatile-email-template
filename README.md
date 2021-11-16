# Versatile Email Template
This table contains mobile responsive alternating tables. Because e-mail clients haven't found a way to agree with each other, this is as "versatile" as it gets. A lot of the bells and whistles that modern web offers, like accordians, carousels, and video embeds, can be done in some e-mail clients. Unfortunately, not every e-mail client displays these features properly. So this "versatile" layout is also friendly with Outlook, Gmail, Yahoo, Apple Mail, and more.

## About the Code:
* Responsive
* Embeds Roboto and has a backup font for Outlook
* Conditional MSO logic to display rounded buttons
* Alternating tables that stack properly in mobile

## Email HTML
If you're a web developer not familiar with email HTML, prepare for heartbreak and traveling back in "coding" time. E-mail clients have different preprocessing engines, and you unfortunately have to surrender to coding practices that go against the typical clean code you see in modern web development. To ensure your e-mail is as faithful as possible to the designer's layout, there's inline styling, CSS selectors, an excessive use of !important, conditional MSO statements and some legacy code. Outlook is perhaps one of the most challenging e-mail clients to code for, because it still processes the code through Word.

## Future Development
Dark mode design.