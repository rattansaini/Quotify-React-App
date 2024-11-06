# Quotify-React-App
Quotify React App

Quotify is a simple React application where users can enter their name and a quote. The quote is added to a list of quotes displayed on the page. Users can add new quotes by pressing the Enter key while typing in the quote input field.

Features
Add a new quote by entering your name and a quote, then pressing Enter.
The added quotes are displayed below the input fields.
Auto-clears the input fields after each quote is added.
Getting Started
Prerequisites
You need a browser that supports ES6+ JavaScript to run this app, as it uses React.

Running the App
Clone this repository to your local machine.
Open the index.html file in your browser to start the app.
File Structure
graphql
Copy code
├── index.html     # Main HTML file with React setup and script
├── style.css      # Optional CSS file for styling (you can customize as needed)
└── README.md      # This file

Code Explanation
index.html
React and ReactDOM: Loaded through CDN links in the <head> section.
Babel: Included to support JSX in the inline <script type="text/babel">.

App Components:
App: The main component containing the title, form, and list of quotes.
Form: A component with two input fields (name and quote) that are connected to React refs.

handleQuote: A function triggered when the user presses Enter. It validates and adds the quote to an array, clears the inputs, and re-renders the App component to show the new quote.
Main Functions

handleQuote: Handles the Enter key press event, adds the new quote to the quotes array, clears the inputs, and re-renders the component.

clearInputs: Clears the input fields after a quote is added.


Example Usage
Open the app in your browser.
Enter a name and a quote in the respective input fields.
Press Enter to add the quote to the list below.

Customization
You can modify style.css to change the appearance of the app, such as:

Adding custom colors to the quotes.
Changing font sizes and styles.

Technologies Used
React: A JavaScript library for building user interfaces.
Babel: A JavaScript compiler to transform JSX into JavaScript.


Future Enhancements
Store quotes in localStorage to preserve them after page reloads.
Add an option to delete individual quotes.
Add animations to enhance the user experience.

License
This project is open-source and available under the MIT License.
