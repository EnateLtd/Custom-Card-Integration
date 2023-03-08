# Third Party WebApp integration by Iframe with Custom Card

## How to create a Advance Custom Card

Create work manager advance custom card ([see the documentation here](https://docs.enate.net/enate-help/builder/builder-2021.1/custom-data-and-custom-card-configuration/super-flexible-cards))

## Import Sample Card

You can just import "iframe-sample-card.en8Card" in Builder/Card section and play with sample.

Note: You might need to modify CSP (Content Security Policy) related to frame to load this sample card in your instance.

## Get Work item information

It will give you Information of currently loaded work item.
[currently loaded work item information picture]()

## Update Work item Title

It will change title property of currently loaded work item.

*Before*
[before currently loaded work item title picture]()

*After*
[after currently loaded work item title picture]()

## Add Validation

It will add a validation which will stop currently loaded work item to be submitted.
[currently loaded work item validation message picture]()

## Remove Validation

It will remove a validation which was stopping currently loaded work item to be submitted.
[currently loaded work item validation message picture]()


## Get Logged-In User information by Calling Enate API

It will give you information of currently logged-in user.
[currently logged-in user information picture]()


### Note

This iframe example hosted at [https://enateltd.github.io/Custom-Card-Integration/iframe/index.html](https://enateltd.github.io/Custom-Card-Integration/iframe/index.html)