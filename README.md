# Roadmap App Development

## September

### 17 - 23

#### Git and github introduction

- [Git Tutorial (w3schools.com)](https://www.w3schools.com/git/default.asp)
- [How to Use Git and GitHub – Introduction for Beginners (freecodecamp.org)](https://www.freecodecamp.org/news/introduction-to-git-and-github/)
- [Learn Git Branching](https://learngitbranching.js.org/) (Interactive tutorial)
- [Git - Basic Branching and Merging (git-scm.com)](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging)
- [Pull Requests in VS Code - YouTube](https://www.youtube.com/watch?v=LdSwWxVzUpo)

#### Project: Create a Simple Website

Description: You will create a simple static website with a few pages and use Git and GitHub to manage the project's version control.
Tasks:

1. Setup:
   - Set up Git on your local machine if you haven't already.
   - Create a GitHub account if you don't have one.
   - Create a new GitHub repository (let's call it "SimpleWebsite").
2. Initial Commit:
   - Create a folder on your local machine for the project.
   - Inside the folder, create an HTML file (e.g., index.html) and add some basic content.
   - Initialize a Git repository in the project folder using the git init command.
   - Add the HTML file to the repository using git add.
   - Commit the changes using git commit.
3. Branching:
   - Create a new branch named "feature" using git branch feature.
   - Switch to the "feature" branch using git checkout feature.
   - Make some changes to the HTML file in the "feature" branch, like adding a new page or modifying existing content.
4. Merging:
   - Switch back to the main branch using git checkout main.
   - Merge the changes from the "feature" branch into the main branch using git merge feature.
   - Remote Repository:
   - Link your local repository to the GitHub repository you created earlier using git remote add origin `<repository URL>`.
   - Push your local repository to GitHub using git push -u origin main.
5. Pull Requests:
   - Go to the GitHub repository.
   - Create a new Pull Request (PR) to merge the "feature" branch into the main branch.
   - Add a description for the PR.
   - Review the changes and create the PR.
6. Collaboration (Optional):
   - Invite a friend to collaborate on the project by adding them as a collaborator on the GitHub repository.
   - Have your friend clone the repository, create a branch, make changes, and create a Pull Request as well.

### 24 - 30

#### Introduction to Dart

- [Dart basics | Dart](https://dart.dev/language)
- [Variables | Dart](https://dart.dev/language/variables)
- [Error handling | Dart](https://dart.dev/language/error-handling)
- [Classes | Dart](https://dart.dev/language/classes)
- [Constructors | Dart](https://dart.dev/language/constructors)
- [Understanding null safety | Dart](https://dart.dev/null-safety/understanding-null-safety)

#### Project: Building a Simple Task List App

Description: You will create a simple command-line task list application using Dart. This project will cover various Dart concepts.

1. Setup:
   - Install Dart on your local machine by following the official Dart installation guide: [https://dart.dev/get-dart]
2. Variables:
   - Create a Dart program that declares and initializes different types of variables (integers, strings, booleans, lists, etc.).
   - Print the values of these variables to the console.
3. Error Handling:
   - Modify your Dart program to include error handling using try-catch blocks.
   - Create a situation where an error can occur, catch the error, and handle it gracefully.
4. Classes:
   - Define a Dart class called Task to represent a task with properties like id, title, description, and isCompleted.
   - Create instances of the Task class and manipulate their properties.
5. Constructors:
   - Add a constructor to the Task class to simplify the creation of task objects.
   - Create new task objects using the constructor.
6. Understanding Null Safety:
   - Refactor your Dart program to enable null safety.
   - Annotate variables and function parameters with appropriate null safety syntax (e.g., int?, String?, Task?).
   - Ensure that you handle null values appropriately in your code.
7. Task List App:
   - Build a simple task list app that allows users to add, view, update, and delete tasks.
   - Implement a menu-driven interface in the command line to interact with the task list.

## October

### 1 - 14

#### Introduction to Flutter

- [Flutter - Beautiful native apps in record time](https://flutter.dev/)
- [Flutter - Get started: install](https://flutter.dev/docs/get-started/install)
- [Flutter - Get started: test drive](https://flutter.dev/docs/get-started/test-drive)
- [Flutter - Building layouts](https://flutter.dev/docs/development/ui/layout)

#### Challenge: How do I tell the weather?

Description: You will create a simple weather app that displays the current weather conditions for a given location. This will only be front-end development, so you will not need to worry about fetching data from an API.

1. Setup:
   - Install Flutter on your local machine by following the official Flutter installation guide: [https://flutter.dev/docs/get-started/install]
   - Create a new repository on GitHub (let's call it "WeatherApp").
   - Create a new Flutter project using the flutter create command.
   - Run the project in an emulator or on a physical device to ensure that everything is working properly.
   - Delete the default code in the main.dart file and start with a clean slate.
2. Layout (These are just ideas)
    - Create a simple layout for the app that includes a text field for entering a location and a button to submit the location.
    - Display the current weather conditions for the location in a card or container.
3. Styling (Optional)
    - Add some styling to the app to make it look nicer.
    - Use a custom font for the text.
    - Add some animations to the app.

### 15 - 28

#### Midterm Break

## November

### 29 - 11

#### Introduction to state management

- [Stateful widgets | Flutter](https://www.geeksforgeeks.org/flutter-stateful-widget/)
- [State Management | Flutter](https://flutter.dev/docs/development/data-and-backend/state-mgmt/intro)
- [Todo app with flutter](https://www.freecodecamp.org/news/learn-state-management-in-flutter/)

#### Challenge: How do organize my tasks?

Description: You will create a simple task list app that allows users to add, view, update, and delete tasks. This will be front-end development only, so you will not need to worry about fetching data from an API.

1. Setup:
   - Create a new repository on GitHub (let's call it "TaskListApp").
   - Create a new Flutter project using the flutter create command.
   - Run the project in an emulator or on a physical device to ensure that everything is working properly.
   - Delete the default code in the main.dart file and start with a clean slate.

2. Layout (These are just ideas)
    - Create a simple layout for the app that includes a text field for entering a task and a button to submit the task.
    - Display the list of tasks in a list view.
    - Add a checkbox to each task to mark it as completed.
    - Add a button to delete a task.
3. Styling (Optional)
    - Add some styling to the app to make it look nicer.
    - Use a custom font for the text.
    - Add some animations to the app.

### 12 - 25

#### Introduction to pub.dev

- [pub.dev](https://pub.dev/)
- [Flutter - Packages](https://flutter.dev/docs/development/packages-and-plugins/using-packages)
- Example Design Packages:
  - [Slider](https://pub.dev/packages/flutter_xlider)
  - [Cards](https://pub.dev/packages/card_swiper)
  - [Payment](https://pub.dev/packages/flutter_credit_card)

#### Challenge: How do I pay for my coffee?

Description: You will create a simple E-commerce app that allows users to add items to a cart and pay for them. This will be front-end development only, so you will not need to worry about fetching data from an API.

1. Setup:
   - Create a new repository on GitHub (let's call it "E-commerceApp").
   - Create a new Flutter project using the flutter create command.
   - Run the project in an emulator or on a physical device to ensure that everything is working properly.
   - Delete the default code in the main.dart file and start with a clean slate.
2. Layout (These are just ideas)
    - Create a simple layout for the app that includes a list of items and a button to add them to a cart.
    - Display the list of items in a grid view.
    - Add a button to view the cart.
    - Display the list of items in the cart.
    - Add a button to pay for the items in the cart.
3. Styling (Optional)
   - Add some styling to the app to make it look nicer.
   - Use a custom font for the text.
   - Add some animations to the app.
   - Add some cool packages from pub.dev to make the app more interesting.

## December

### 26 - 9

#### Introduction to Working with APIs

- [Flutter - Networking & http](https://flutter.dev/docs/development/data-and-backend/networking)
- [Flutter - JSON and serialization](https://flutter.dev/docs/development/data-and-backend/json)
- [Flutter - Using packages](https://flutter.dev/docs/development/packages-and-plugins/using-packages)
- [Freezed](https://pub.dev/packages/freezed)

#### Challenge: How do I tell the weather, Part 2?

Description: You will use your weather app from the first task, except now you will fetch the weather data from an API instead of hard-coding it.

1. Setup:
   - Create a new repository on GitHub (let's call it "WeatherApp2").
   - Create a new Flutter project using the flutter create command.
   - Run the project in an emulator or on a physical device to ensure that everything is working properly.
   - Delete the default code in the main.dart file and start with a clean slate.
2. Layout (These are just ideas)
    - Create a simple layout for the app that includes a text field for entering a location and a button to submit the location.
    - Display the current weather conditions for the location in a card or container.
3. Styling (Optional)
      - Add some styling to the app to make it look nicer.
      - Use a custom font for the text.
      - Add some animations to the app.
4. API:
      - Find an API that provides weather data for a given location.
      - Fetch the weather data from the API and display it in the app.
      - Handle any errors that may occur when fetching the data.

### 10 - 23

#### Introduction to Firebase

- [FlutterFire | Firebase](https://firebase.flutter.dev/)
- [Firebase - Get started](https://firebase.google.com/docs/flutter/setup)
- [Firebase - Authentication](https://firebase.google.com/docs/auth)
- [Firebase - Cloud Firestore](https://firebase.google.com/docs/firestore)
- [Firebase - Cloud Storage](https://firebase.google.com/docs/storage)
- [Firebase - Cloud Functions](https://firebase.google.com/docs/functions)

#### Challenge: How do I organize my tasks, Part 2?

Description: You will use your task list app from the second task, except now you will store the tasks in a database instead of in memory.

1. Setup:
   - Create a new repository on GitHub (let's call it "TaskListApp2").
   - Create a new Flutter project using the flutter create command.
   - Run the project in an emulator or on a physical device to ensure that everything is working properly.
   - Delete the default code in the main.dart file and start with a clean slate.
2. Layout (These are just ideas)
    - Create a simple layout for the app that includes a text field for entering a task and a button to submit the task.
    - Display the list of tasks in a list view.
    - Add a checkbox to each task to mark it as completed.
    - Add a button to delete a task.
3. Styling (Optional)
      - Add some styling to the app to make it look nicer.
      - Use a custom font for the text.
      - Add some animations to the app.
4. Database:
      - Create a Firebase project and enable Cloud Firestore.
      - Connect your Flutter app to the Firebase project.
      - Store the tasks in the database instead of in memory.
      - Fetch the tasks from the database and display them in the app.
      - Add, update, and delete tasks in the database when the user interacts with the app.

## January

## February
