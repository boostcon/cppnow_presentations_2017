=====================
Slide Deck Guidelines
=====================

.. role:: raw-html(raw)
   :format: html

- Slide decks should be in the PDF format.
- Slide deck file names should follow this format: :raw-html:`<code><i>TALK_TITLE</i>__<i>SPEAKER_NAME</i>__cppnow_<i>TALK_DATE</i>.pdf``
    - :raw-html:`<code><i>TALK_TITLE</i></code>` should be the title of the talk, restricted to lowercase alphanumeric characters and `_`.
        - ``C++`` should be escaped as ``cpp``.
    - :raw-html:`<code><i>SPEAKER_NAME</i></code>` should be the name of the speaker (first name, middle name(s) and last name in that order), restricted to lowercase alphanumeric characters and `_`.
    - :raw-html:`<code><i>TALK_DATE</i></code>` should be the date the talk was presented, in the format `MM-DD-YYYY`.
- The actual slide deck should be in this repository. No links.
- Slide decks should be context-free.
    - Include the name and year of the conference somewhere in your slide deck.
    - Include links to supplemental presentation materials (example code, referenced documents, etc) in your slide deck.
- Place your copyright somewhere in your slide deck.

FAQ
===

*Why PDFs?*

- A PDF slide deck is a single file, making it easy to download and forward.
- PDFs are fairly portable and have a consistent rendering across bdesktop and mobile OSes.
- PDFs are easy to print.

*Why can't I just link to my HTML5 + javascript slide deck on my website?*

This repository should be complete without any depedencies aside from a PDF viewer, an HTML viewer and a git client.

- People who have downloaded this repository should be able to view all the slides without Internet access.
- We do not have a way of guaranteeing that your website will be accessible 5/10/15 years from now. 

*Why should we include contextual information (conference name, links, etc)? Why should we include a copyright?*

Our audience (both conference attendees and video viewers) may redistribute our slide decks to their colleagues. Our slide decks should contain as much context as possible to inform those who receive the slides second- (or third-, or fourth-) hand.

