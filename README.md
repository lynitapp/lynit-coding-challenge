# Lynit Coding Challenge



## Instructions

In this challenge you'll be in charge of creating a Full Stack Web Application in which you should display the books data (you can decide if in a grid or a list), edit a book's data, create new books and delete them.

On the repository you will be able to access to the base dataset that must be used to fill your database, this file is called `books.json`. In this file there are three arrays:
1. The books array: this array will be the main data that you will show as default data. You should be able to create new books, edit and delete them.

2. The authors array: this array exist in order to filter out the books on the frontend by a selected author. Everytime you create a new book with a new author, this new author should be pushed into the authors array. Don't mind deleting authors.

3. The genres array:  this array exist in order to filter out the books on the frontend by a selected genre. Everytime you create a new book with a new genre, this new genre should be pushed into the authors array. Don't mind deleting genres.

On the overall view the books should only display the image, the name and the author. You should be able to create books in this view and delete them.

There must be a detailed view in which all the book's data should be displayed, such as genres, rating and description. In this detailed view the book should be able to be edited and deleted. When deleting a book on detailed it should return to the overall view.

The images are url, so for new books if the `imageUrl` field in the object is not filled, there must be and empty image as default. We'll leave you an example that you can use: 

[Example image](https://st4.depositphotos.com/14953852/24787/v/600/depositphotos_247872612-stock-illustration-no-image-available-icon-vector.jpg)

#### Stack:
Frontend:
- React (with Javascript)
- Styling (your choice)

Backend:
- NodeJs
- Framework (your choice)
- Database (your choice)

You should deploy your app and connected it to a remote database. You choose how.

## What will we evaluate?

1. Coding standards.
2. Project structure.
3. Commits and branches usage (Git)

### Bonus
- Add pagination in order to display the books in a certain amount, this amount definition will be up to you!
- Filter books by rating thresholds:
  - 0-1.9 
  - 2-3.9 
  - 4+

- Use Apollo Server, GraphQL and Apollo Client.
- Unit testing 

## Happy Coding!