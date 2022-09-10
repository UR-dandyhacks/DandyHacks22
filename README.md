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

### Notes:

- if an SVG isn't scaling propely, based on the content, make sure to add (preserveAspectRatio="none") to the SVG file.
- If you're importing an SVG that has a shadow, make sure to export a version WITHOUT any shadows, then apply the shadow to the img or div using class="shadow"
- Make sure to always use percentages whenever possible instead of haerd coded numbers. This way, things translate easily in phone view.

## Next steps:

- [ ] Import the cloud SVG, and place 3 seperate images of it in the scene. Place them so they they have negative margins to the left/right of the screen. This way they will always be placed at the edge.
- [ ] Create wooden signs with strings (like in FAQ)

  - To do this, we can do the same process that was used to create the large wooden planks for text. Which is class="wooden-sign".
    1. Create a div, and add background to the div. The background will be the same wooden plank used in the big one. But this time, it will have less padding around it to make it smaller.
    2. The div created in step 1 will hold all these remaining elements:
       a. The title text if any (as an h2, h3, or h4)
       b. Description text (as a paragraph)
       c. The ropes. Will be imported as an SVG image. Make sure this is always placed at the top center of the div.

- [x] Make the signs with ropes collapsiable (For FAQ)
  1. If the signs with ropes are designed in a way where it's a div with a background, that incapsulates the text, this should be simply done adjusting the "description" text's visibility, to either be shown or hidden.
  2. Preferably, only one question can be opened at a time. This will prevent the layout from getting messy if the user expands all questions at once.
- [ ] change the text at the top of the page to match the Figma deisgn.
  - Logo and title will both be SVGs.
  - Date and location will be text, and the location will have a url that takes to a google maps link of the location.
- [ ] Modify the phone view to be more mobile-friendly.
  - [ ] Add additional padding to the top and bottom of the planks that have long text.
  - [ ] Scale up the hills so that they cover up the background.
  - [ ] Make the stick for the top sign viewable.
- [ ] Make the height of the wooden-sign sticks adjustable.
- [ ] Add groundboi speech bubble next to tracks. (It can be collapsible in both and phone and desktop view)
- [ ] Change the icons on the website to the new simplified ones. Impirt them as SVGs, and change the color on hover. (Check the sample for Instagram in the Figma)
