# Klever Junior Frontend Test

Hello, this is the Frontend test for junior developers from Klever. The objective is to analyze the skills of candidates, focusing on the core fundamentals of HTML, CSS, and JS.

## Pages

### Home

#### Actions

- When clicking on the "Add Token" button go to the "Add Token" page
- When click on the icon "Edit" go to the "Edit Token" page

### Add Token

#### From

- The Token field is required
- The Balance field is required

#### Actions

- When clicking on the "Back" button go to the "Home" page
- When clicking on the icon "Save" button
  - Save the data in localStorage from Browser
  - Navigate user to home page

#### Bonus

- The Token name should be unique, the user shouldn't has token names repeated
- Display the error messages from form to the user

### Edit Token

#### Actions

- When clicking on the "Back" button go to the "Home" page
- When clicking on the "Save" button
  - Save the data in localStorage
  - Navigate user to home page
- When clicking on the "Remove" button
  - Remove the date from local storage
  - Navigate user to home page

#### Bonus

- When the user clicks on the "Remove" button should display an alert to the user to confirm the remotion.
  - If confirmed, the token should be deleted
  - If denied, the alert closes and the token not should be deleted,

## Bonus

- Use the React Framework
- Unit Tests

## FAQ

1. Can I just use HTML, CSS, JS?

- Yes

2. Can I use other javascript frameworks?

- Yes

3. Can I use some CSS framework like Bootstrap, Material UI?

- Yes, and try to follow the proposed design
