# DandyHacks22

[dandyhacks.net](https://dandyhacks.net/)

## Creating dynamic content

- To add a new hill:
  1. Create a div with a class 'hill', and give it an ID that is specific to it, ex. "hill-about"
  2. Create a new ID in the CSS file, and give it a 'background-image' of the hill's corresponding SVG.
  3. If the newly added hill isn't aligning properly with the hill in top of it, you can adjust the new hills 'margin-top'.
  4. If the newly added hill isn't filling the screen enough, you can adjust the new hill's height.
  5. Each hill must have a div with class 'hill-content' which will hold all the content on the hill, and insure that the content is within specific margins of the viewport. Elements that can be added as hill content include:
     a. A wooden sign, with one top plank for the title, and other blank plank for any other details (text/embed).
     b. A wooden sign, with one top plank for the title, and other planks with roped for a list of elements.
     c. The characters
