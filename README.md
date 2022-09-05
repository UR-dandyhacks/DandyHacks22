# DandyHacks22

[dandyhacks.net](https://dandyhacks.net/)

## Creating dynamic content

- To add a new hill:
  1. Create a div with a class 'hill', and give it an ID that is specific to it, ex. "hill-about"
  2. Create a new ID in the CSS file, and give it a 'background-image' of the hill's corresponding SVG.
  3. If the newly added hill isn't aligning properly with the hill in top of it, you can adjust the new hills 'margin-top'.
  4. If the newly added hill isn't filling the screen enough, you can adjust the new hill's height.
  5. Each hill must have a div with class 'hill-content' which will hold all the content on the hill, and insure that the content is within specific margins of the viewport.
  6. To use a wooden sign, use class='wooden-sign'. It must include two sticks, and will have other contents which can be,
     a. Title wooden plank, to apply use class='title'
     b. Blank wooden plank, used for long text, to apply use class='details'. Ex. Used is the "about" section.
     c. Wooden planks with ropes, used for lists, to apply use class='list'. Ex. Used is the "tracks" section.
     d. You can adjust the width of the entire sign.

Notes:

- if an SVG isn't scaling propely, based on the content, make sure to add (preserveAspectRatio="none") to the SVG file.
- If you're importing an SVG that has a shadow, make sure to export a version without any shadows, then apply the shadow using class="shadow"
