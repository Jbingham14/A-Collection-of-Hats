---
title: Technical Documentation
layout: about
permalink: /technical.html
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---
# Technical Documentation
{% include feature/nav-menu.html sections="Items Chosen;Imaging Standards;Metadata Standards;" %}
## Items Chosen
These items are all hats that I own and thus there should not be any copyright concerns. 
I chose hats for this project because I wanted to work with a collection of my own and do something that did not require me to visit another repository.
## Imaging Standards
These photos were taken with a Nikon D5300 with a 18-55mm lens. The photos are 300 dpi both in horizontal and vertical resolution. They were taken with 1/80 second exposure and an f-stop of f/8. The ISO was set to 200 without flash.
These photos were taken using this Nikon and a Neewer Photo Studio Light Box both rented from the IU Wells Makerspace. T
hese photos were then uploaded and save on my home pc. I then uploaded and renamed the photos and then uploaded to GitHub. 
I took photos from various angles but with my difficulty using GitHub I figured it was better to just feature the frontal images of the hats. 

{% include feature/image.html objectid="PICK AN IMAGE" width="50" caption="INSERT A CAPTION" %}

INSERT

## Metadata Standards
The metadata for this project uses the metadata scheme of Dublin Core and one custom value I called “brand”.
The values of individual elements are subject to both custom and established controlled vocabularies such as the Library of Congress Name Authority and the Getty Art and Architecture Thesaurus.
Below is an explanation of what Dublin Core and text item type elements are used and what standards have been applied to their input.
 
### Dublin Core elements  
#### Title - required, 1 value allowed
The title element contains the title I gave to the hat. The Title is way to differentiate the hats from each other. Some are based on what brand they represent or the hat type in the case of some hats having the same brand.  
Examples: Achievement Hunter Dad, Red Bull Racing
#### Subject - required, 1 values required
The subject field is the topic of a resource. For hats I used the subject field as similar to a genre term. While the Library of Congress has a set of genre/form terms, I used my own custom terms to better describe the collection.
Examples: Golf, Formula 1
#### Date - optional, 1 value allowed
Date element contains the value of the date of publication which is important to include in any sort of bibliographic item. The dates are formatted according to the W3C date format which allows for dates to be inputted in this way:
•	YYYY-MM-DD
•	YYYY-MM
•	YYYY
Since, I am unsure on the exact dates of many of the hats I decided to use the second date YYYY-MM. There are some fields left blank. 
Example: 2015-12, 2014-08
#### Location - required, 1 value allowed
This field represents where I purchased the hat. For those bought online, I used whatever my current location at that time was which was either Indianapolis, IN or Bloomington, IN. For those I bought or received elsewhere, I included that city. 
Examples: Indianapolis, Indiana, Austin, Texas
#### Format - required, 1 value allowed
These are all photos of hats; thus they are all images using jpeg filetype. 
Examples: image/jpeg
#### Description - required, 1 value allowed
The description element contains a short description of the hat, where it came from, and whether it was received as gift or purchased. 
#### Type - required, 1 value allowed
For this field I used the Getty Art and Architecture Thesaurus to differentiate the different types of hats. This field is usually used to a way to characterize different format types, however, since these are different hat types/ styles I thought this Dublin Core field would match best. 
Examples: beanie, baseball cap
#### Latitude and Longitude- required, 1 value allowed each
I included these fields as they were part of the Collection Builder template. I used approximate locations in a gps search to determine what the latitude and longitude of each hat, corresponding with the location field. 
Example: 39.156929, -86.523655
#### Creator - required, 1 value allowed
The creator element is used to denote the manufacturer. I was unsure which field this fit best in. However, after giving it some thought the creator is who made the fabric and that would be the manufacturer. 
Examples: Quality Internet Good, Under Armour
#### Brand - required, 1 value allowed
The Brand is my own custom field. This is not who made the actual product, but what the hat is representative of. While Achievement Hunter is the name of some of the hats, their parent company is Rooster Teeth and is thus the brand. 
Example: Rooster Teeth, Nintendo
#### Identifier - required, 1 value allowed
For this field I wanted to use color schemes as a way to differentiate or identify the hats. Since colors are an identigying feature I used identifier for the color scheme. I used https://www.w3schools.com/colors/colors_groups.asp as my reference for the colors described. 
Examples: white; grey; blue; red, saddlebrown; goldenrod
#### Rights - required, 1 value allowed
The rights element describes the copyright status. I own these hats therefore, there should not be any lingering copyright issues. 
#### Source - required, 1 value allowed
These hats are my own and via this digital project they are considered my own private collection that I am putting on display digitally. 
