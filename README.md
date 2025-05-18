# Number Facts Fetcher

This is a simple web application that allows users to retrieve interesting facts about numbers using the [Numbers API](https://apis.ccbp.in/numbers-fact).

## Features

- Takes user input (a number).
- Fetches a fun fact related to that number.
- Displays the result on the webpage.
- Shows a loading spinner while fetching data.

## How It Works

1. User types a number into an input field and presses Enter.
2. A `fetch` request is sent to the Numbers API.
3. The app displays a fun fact about the entered number.

## Technologies Used

- HTML
- CSS (for spinner and visibility handling)
- JavaScript (Vanilla)

## How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/number-facts-fetcher.git
    cd number-facts-fetcher
    ```

2. Open the HTML file in your browser:
    ```bash
    open index.html
    ```

3. Enter a number in the input box and press **Enter** to see the magic!

## API Reference

- [CCBP Numbers Fact API](https://apis.ccbp.in/numbers-fact)

## Project Structure

```plaintext
project-directory/
├── index.html
├── styles.css
└── script.js    # Contains the main logic to fetch and display number facts
