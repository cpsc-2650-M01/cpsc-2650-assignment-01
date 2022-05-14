# cpsc-2650-assignment-01

- Create a new Express application calculator.
- Add a route for /add.
- On the /add page:
  - Display a form with two text fields “A” and “B”.
  - If the parameters for “A” and “B” are present in the request, pre-fill the fields with those values.
  - If the parameters for “A” and “B” are present in the request, display the sum of “A” and “B”.
  - Display a button “Add” that the user can press which submits the form with “A” and “B”.
- Add a route for /multiply.
- Make the /multiply plage work basically like the /add page except that it calculates the product of “A” and “B”.
- On the index page (“/”) display links to the /add and /multiply pages.
- Test the application locally.
- Create a “Dockerfile” for the application.
- Build the image.
- Test the image locallay.
- Push the image to the container registry.
- Test.
- Push the the assignment to this repository. Be sure to create a .gitignore file to exclude the node_modules\ directory.
