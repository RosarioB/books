# Books application
A React application where you can add, remove and update books. It takes random pictures from a [free API](https://picsum.photos/) for each book. 

![alt text](https://github.com/RosarioB/books/blob/main/github_images/books.png?raw=true)

There are four branches, and the application improves as you move to the latter branch:

1. **local_books**: the books are stored in memory, when you refresh the page you lose all data.
2. **book_persisted_with_api**: the books are stored in a JSON server which is a library that allows you to create very easily some Rest API for testing and saves the data in a file json called `db.json`. The CRUD APIs are definied in the file `api.http`
3. **external_api_and_context**: the application in the previous branch is refactored introducing context.
4. **custom_hook_refactoring**: the application in the previous branch is refactored using custom hooks.

# Acknowledgments

This code is adapted from the course [Modern React with Redux](https://www.udemy.com/course/react-redux) by Stephen Grider, with some modifications.