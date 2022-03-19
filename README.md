# UFOs
## Overview of Project

### Purpose
I have been working with Dana to create a visually appealing display of UFO sightings, that allows users to filter for multiple criteria (shape, city, date, country, state) at the same time. The goal was to create a webpage that is dynamic and attractive. 

### Resources
- Data Source: data.js (available in the [Here](https://github.com/baileyvo/UFOs/tree/main/static/js))
- Software: Visual Studio Code 1.63.2

## Results

### Using the Search Criteria
There are five items that can be used to filter the entire available UFO dataset: **Date, City, State, Country, and Shape** (as seen below):

![Filters](https://github.com/baileyvo/UFOs/blob/main/Images/Filters.PNG)

In order to apply filters, enter desired criteria and then either press enter or click out of field. To reset all filters, click on UFO Sightings title at top left of screen (as pictured below):

![UFOSightings](https://github.com/baileyvo/UFOs/blob/main/Images/UFOSightings.PNG)

An example of how to fill in fields is shown below:

![filledFields](https://github.com/baileyvo/UFOs/blob/main/Images/filledFileds.PNG)

Some important items to note:
- All dates are from January 2010. When filling the date field do not put a zero before the one. Instead use 1/xx/2010.
- City cannot be capitalized and cannot be followed by a space
- State cannot be capitalized and will be the two letter abreviation (for example California would become "ca")
- Country cannot be capitalized and will be the two letter abreviation (for example United States of America would become "us")
- Shape cannot be capitalized and must exactly match. Some examples include: circle, light, formation, fireball. 

## Summary

### Drawback
One drawback of the new design is there is no button to click to apply filters, instead the filters are applied individually and requires loading between entering each field.

### Recommendations
While this is already a well-functioning, attractive webpage, a few improvements could go a long way:
- Instead of shape filter being a text field, where the user may not know the shape, it would work better as a drop down menu where all available shapes could be selected from.
- It would be helpful to be able to select multiple filters from each category. For example, being able to filter for shapes circle and light, while excluding all others. 
