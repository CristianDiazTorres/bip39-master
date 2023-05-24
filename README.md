## How to use

-   Choose between 24, 21, 18, 15, and 12 words
-   Generate a complete random phrase at any time
    - The button will use the browser's random number generator
    - The text input will use the SHA-256 hash of whatever you type in (should be something random, or very long)
-   Drop down interface for selecting and searching for individual words
-   The list of valid last words will dynamically update as word selections are made

## Technical details

This project was built with the [Gatsby](https://www.gatsbyjs.org) static site generator, including [React](https://reactjs.org) and [Styled Components](https://www.styled-components.com/).

### Running locally

To run the site locally for development or offline usage, [NodeJS](https://nodejs.org/en/download/) is required. Then clone the repository and run the following commands from the project directory:

`npm install`

`npm run develop` for development (hot reloading)

`npm run build` and `npm run serve` for a production build

## Security considerations

Choosing your own mnemonic is less secure than using a randomly generated one. There is a greater chance an attacker can guess your phrase if it is not random. On the flip side, there is also a greater chance of remembering a custom phrase in case you lose your backups by accident. Overall, random is still better, but if you're willing to accept the tradeoffs, a custom mnemonic can be useful. It is another tool to have in the wide spectrum of security systems.
