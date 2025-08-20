Please code the following responsive landing page using strictly HTML, CSS, and JavaScript/jQuery.
- We are strictly concerned with layout skills. Do not worry about linking any of the content
elements to another page.
- Use responsive design principles.

For desktop, the background colors will extend 100% of the screen, but the content
container will have a max width of 1620px.
When the screen is sized down to 580px or less, we will display the “mobile” view which calls for stacking our layers (see examples below for more details)

- [ ] Font Family: Arial

- [ ] Background colors:
    - [ ] Navigation bar: #000
    - [ ] Main content: #2E083D

- [ ] Content Images
    - [ ] Images should have a responsive class that helps them fill their content area.
    - [ ] All main content images/cards will be presented with a border radius of 6px.

- [ ] Hero Image
    - Use the <picture> element to display the desktop versus mobile version of the hero image. The breakpoint for mobile will be 580px.

- [ ] Now Playing
    - This is a static area that must be created using flexbox. When you reach the mobile breakpoint, you will add rules that stack the elements vertically.

- [ ] Tomorrow’s Schedule
    - This area is populated dynamically.
    - [ ] You will use the TVmaze API to retrieve the list of shows to display.
    - [ ] Use the Schedule API to retrieve shows airing in the US with tomorrow’s date.
    - Use the jQuery ajax() method to request the data from Tvmaze.
    - [ ] Create a horizontal scrolling UI that displays the first 24 shows returned in the JSON object.

- [ ] Optional challenge: styled gradient scroll bar (this is a nice to have)
Hex code for horizontal scrollbar goes from #FF5C00 to #CB2DF on a black bar: #000

Resource Links:
- Static Image Assets: https://drive.google.com/drive/folders/1sH7VPsABdlvINT1b76iHvMUiMBvOMfGk?usp=sharing
- Flexbox: https://css-tricks.com/snippets/css/a-guide-to-flexbox/
- TVmaze API Documentation: https://www.tvmaze.com/api
- jQuery: https://www.w3schools.com/jquery/
- jQuery Ajax: https://www.w3schools.com/jquery/ajax_ajax.asp
- Horizontal Scrolling UI: https://webdesign.tutsplus.com/horizontal-scrolling-card-ui-flexboxand-css-grid--cms-41922t