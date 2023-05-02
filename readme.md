# React Article Summary App

This app is a React-based article summarization tool that allows users to paste a link to an article and receive a summary of its content. The app saves the link and summary to local storage for future reference, and users can browse their browsing history to quickly access past summaries.

The app uses the useLazyGetSummaryQuery hook from the article service to fetch article summaries via a server endpoint. The summary data is then displayed in a section below the search form.

## Getting Started

To use the app, you can simply clone this repository and run npm install to install the necessary dependencies. Afterward, run npm start to start the development server and open the app in your browser.

## Dependencies

This app uses the following dependencies:

- React: A JavaScript library for building user interfaces.

- React-Redux: A library for managing application state in React.

- Redux Toolkit: A package that provides utilities to simplify common Redux use cases.

- Axios: A library for making HTTP requests.

- Tailwind CSS: A utility-first CSS framework for rapidly building custom user interfaces.

## Usage

To use the app, simply paste a link to an article in the search form and hit enter or click the submit button. The app will fetch a summary of the article content and display it in the section below the search form.

You can also browse your past browsing history by scrolling through the list of saved articles below the search form. To copy the link of a saved article to your clipboard, simply click the copy button beside the link.

## Conclusion

This is a simple but powerful tool for anyone who wants to quickly summarize articles and keep track of their browsing history. With this app, you can quickly access past summaries and save time by avoiding the need to reread articles you've already read.