# Jorge's notes

The application is a simple React application that allows the user view, sort and filter the veterenary appoitments along with CRUD operations.
This version works of a file data.json that contains the data. Nothing is stored in a database.

## Technologies

- React
- Tailwind CSS
- React-Icons

## React Icons

` npm install react-icons --save`
Webpage: https://react-icons.github.io/react-icons/

# Tailwind CSS

https://tailwindcss.com/docs/guides/create-react-app

# CRACO

- React-Scripts 4 supports POSTCSS 8, which is incompatible with Tailwind CSS 3.0.
- Project is using "react-scripts": "^5.0.1"
- Therefore, we need to install CRACO.

# TODOs

- I dislike creating IDs based on next number. UUID is a better option.
- I dislike sorting based on the records loaded in the component. Real cases have more records than the ones loaded in the component.
- User will like to sort by multiple columns.
