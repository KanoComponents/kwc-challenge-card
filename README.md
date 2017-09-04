# \<kwc-challenge-card\>

## Purpose:
To display a building challenge, and indicate whether it is completed not.

## Variants:
* complete

## Properties
* challengeid (String): Unique challenge identifier. Currently the challenge slug. 
* imgurl (String): Url to image for challenge cover.
* title (String): Title for this challenge
* completed (Boolean): Should the card show the complete icon and styles?
* creator (String): of the challenge
* label (String): Not sure why we have this.
* 

This component exposes the following custom css names to set the height and width of the element
* --kwc-cc-width
* --kwc-cc-cover-height


## Installation
* Clone this repository.
* Run `bower i`
* Make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Running Tests

```
$ polymer test --skip-plugin junit-reporter
```
## TODO
Component behaviour with broken image link.