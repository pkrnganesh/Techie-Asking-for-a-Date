# Coffee Date Web App

#remodifying

## Overview

This simple web app is designed to invite someone on a coffee date in a fun and engaging way. The app presents an invitation and uses playful elements to interact with the user.

## File Structure

1. **index.html** - The main page of the app that presents the invitation to the user.
2. **confirmation.html** - The page shown after the user confirms the invitation, featuring a message and animated roses.

## Functionality

### index.html

- **Invitation Page:** 
  - Displays a message asking the user if they'd like to go on a coffee date.
  - Features two buttons: "Yes" and "No."
    - Clicking "Yes" redirects to `confirmation.html`.
    - Hovering over "No" makes the button move around to encourage clicking "Yes."

### confirmation.html

- **Confirmation Page:**
  - Displays a confirmation message indicating the coffee date details.
  - Features falling animated roses as a decorative element.
  - Automatically redirects to `index.html` after a short delay.

## Styles

- Utilizes custom fonts from Google Fonts: `Great Vibes` and `Lora`.
- Background gradients and animations to enhance the visual appeal.
- Button styles with hover effects for better user interaction.

## Scripts

- **index.html**
  - `moveButton()`: Moves the "No" button randomly within the container when hovered over.
  - `showMessage()`: Redirects to `confirmation.html` when the "Yes" button is clicked.

- **confirmation.html**
  - `createRoses()`: Generates and animates falling roses on the page.
  - `redirectToCoffeeDate()`: Redirects to `index.html` after a 5-second delay.

## Usage

1. Open `index.html` in a web browser to see the invitation page.
2. Interact with the buttons as described above.
3. After confirming, you will be redirected to `confirmation.html`, where you'll see the final message and animations.

## Contributing

Feel free to fork the repository and submit pull requests if you have suggestions for improvements or additional features.
