# Third Party WebApp integration by Iframe with an Enate Advanced Custom Card

## Create an Advanced Custom Card

Go to Enate Builder and in the Custom Card page, click to create a new Custom Card. Add a name to the card and a description if you want and then click the ‘Advanced’ toggle [(see here for more information about creating Advanced Custom Cards in Enate)](https://docs.enate.net/enate-help/builder/builder-2021.1/custom-data-and-custom-card-configuration/super-flexible-cards).

## Add Sample Card Code

Copy and add the sample card code from "iframe-sample-card.en8Card" into the relevant sections. You can also just import "iframe-sample-card.en8Card" in Builder/Card section and play with sample.  

Note: You might need to modify the frame content in your CSP (Content Security Policy) in order to load this sample card in your instance *(For this card you modify "frame-src" part and add "https://*.github.io").

## Work Manager Default Card View

At runtime in Work Manager, the Custom Card will look like this: 

![currently loaded work item information picture](https://enateltd.github.io/Custom-Card-Integration/iframe/docs/default.jpg)

## Get Work item information

This provides information about the currently loaded work item.

![currently loaded work item information picture](https://enateltd.github.io/Custom-Card-Integration/iframe/docs/pkt-info.jpg)

## Update Work item Title 

This changes the title property of currently loaded work item.

*Before*
![before currently loaded work item title picture](https://enateltd.github.io/Custom-Card-Integration/iframe/docs/pkt-title0.jpg)

*After*
![after currently loaded work item title picture](https://enateltd.github.io/Custom-Card-Integration/iframe/docs/pkt-title1.jpg)

## Add Validation

This adds validation to prevent the currently loaded work item from being submitted.

![currently loaded work item validation message picture](https://enateltd.github.io/Custom-Card-Integration/iframe/docs/vld-added.jpg)

## Remove Validation

This removes the validation that was preventing the currently loaded work item from being submitted.

![currently loaded work item validation message picture](https://enateltd.github.io/Custom-Card-Integration/iframe/docs/vld-removed.jpg)


## Get Logged-In User information by Calling Enate API

This provides information about the currently logged-in user.

![currently logged-in user information picture](https://enateltd.github.io/Custom-Card-Integration/iframe/docs/user-info.jpg)


### 1. Note

An example of this iframe can be found here: [https://enateltd.github.io/Custom-Card-Integration/iframe/index.html](https://enateltd.github.io/Custom-Card-Integration/iframe/index.html).
