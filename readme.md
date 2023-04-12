# Know a country

Try this web application at https://knowacountry.herokuapp.com/

It's a web application that provides users with information about different countries around the world. It allows users to select a country from a dropdown menu, and upon selection, the website displays various information about that country, such as its location in an earth globe and flag, population, language, and currency on a card.

Here are some tips on how to use the website:

1. Use the dropdown menu to select a country that you want to learn more about. The dropdown menu is located at the top of the website, just below the navigation bar.
2. Once you have selected a country, the website will display information about that country in the main content area. If the country has special administrative regions or similar areas, multiple location markers are displayed on the globe and the user can rotate the globe and click on the markers with the mouse and the information for the corresponding location is displayed on the card.

If you want to setup and use this web application locally please read the following stuffs.

## Table of Contents

- [Prerequisites](#Prerequisites)
- [Installation](#Installation)
- [Test](#test)
- [Usage](#Usage)

## Prerequisites

Before you begin, make sure you have the following software installed:

- Node.js (16+)

## Installation

To install the application, follow these steps:

1. Server

```shell
cd backend
npm install
```

2. Client

```shell
cd frontend
npm install
```

## Test
To test the client, run the following command:
```shell
cd frontend
npm test
```

## Usage

To start the server, run the following command:

```shell
cd backend
node ./bin/www
```

To start the client, run the following command:

```shell
cd frontend
npm start
```

You can access the application at `http://localhost:3001`.

