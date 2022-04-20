# TODO List Part 1: Frontend Basics
Build a TODO list React App.

## Links
  
  - [create-react-app](https://create-react-app.dev/)
  - [React Docs](https://reactjs.org/)
  - [Airbnb React Style Guide](https://airbnb.io/javascript/react/)
  - [Airbnb JS Style Guide](https://github.com/airbnb/javascript)
  - [eslint](https://eslint.org/)
  - [Bootstrap Components](https://react-bootstrap.github.io/)
  - [Material UI Components](https://mui.com/)

## Instructions

To get started, create a new repository on your github account to push it to, be sure to make it public so that you can show it off on your resume. Add [me (JWA111)](https://github.com/JWA111) as a contributor so that I can provide code review and feedback. Create a branch called something like `part-1` to contain everything for this first part of the project. Next reate a react app with `create-react-app`, and name it "frontend" so that it creates everything in a folder named `frontend`. Now lets get building the app!

This app will consist of a list of iteams that can be:

  - Added to
  - Removed From
  - Items Edited
  - Items "checked" off

Style it as you please, you are welcome to also leverage react component libraries such as material-ui, bootstrap, semantic, etc but bonus points if you build your own components from scratch!

Make the TODO list component consist of:

  - a list of items
  - the ability to add items
  - the ability to order the items
 
 Each item having:

  - a checkbox
  - the text of the item
  - a way to edit the item
  - a way delete the item
 
Feel free to add any additional features that you would like, but be sure to cover all features described here.

The data structure of the item should include:

String: the text of the item
Boolean: the state of the item (checked or not)
Number: order of the item in the list

Feel free to add any additional fields to the item object. Hold the data in the app's state using your preferred method.

**Considerations:**
  - Edge cases
  - Empty states
  - Different browsers
  - Responsiveness (mobile vs web)
  - Project organization
  - Code style

When you are done, submit the assignment and we will do a code review process where changes will be requested and you'll need to adress the feedback. Be sure to include a readme with instructions for running the app.
