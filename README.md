# Todo List in Angular with Codespaces

## Approach
Forked from Austen Stone's 'Angular Codespace' starter to setup docker and environment in GitHub Codespaces :
https://github.com/austenstone/angular-codespace

Build a simple ToDo List following tutorial :
https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/Angular_todo_list_beginning

Then design and build project's 4 requested user stories :

# User stories

## 1 : List my TODOs
### Description :
As a user I would like to list my current todos
### Acceptance criterias :
- [ ] Each todo could have, at minimal, a related state and title
- [ ] Some hard-coded todos will be initialized in this context to demonstrate the tool 

## 2 : Change a TODO state
### Description :
As a user I would like to change a todo state by checking a "box"
### Acceptance criterias :
- [ ] When a todo is done, it should be placed at the bottom of the list and should be crossed out

## 3 : Detail a TODO
### Description :
As a user I would like to display one of my todo in a separate or dedicated view.
This todo will contain its title and a description (which is a new information not shown in the previous view).
### Acceptance criterias :
- [ ] We can click on a todo (by any way) to access the details view of the todo
- [ ] The todo could be accessed via a unique URL

## 4 : Add a new TODO
### Description :
As a user I would like to add a new todo in my list
### Acceptance criterias :
- [ ] The todo title is required
- [ ] The todo description can be empty
- [ ] The newly created todo has to be on top of the list of todos
- [ ] You are free to choose the design / interaction 

# Technical environment checklist
You're working in the WebFactory which provides the following technical recommendations :
- [ ] **Angular** - The backend application should be based on your preferred languages (Java , JS, PHP, Python, Go, C++, ...) and/or Framework (Spring Boot, Django, .NetCore , NodeJS, Angular, React, ...)
- [ ] **Use GoogleKeep as a minimalist model** - To keep the UI simple
- [ ] **OOP to keep code simple and scalable | Add unit testing** - Code quality is very important, so all the code has to be covered by unit tests
- [ ] **Branch and pull-request to master for each user story** - Each user story should be realized in its own commit on master
- [ ] **To investigate - check testing with Pages** - The product owner is curious and likes to read the application code on Github and test it via Github Pages
- [ ] **To investigate - Stackblitz/Codespaces may offer backend - build with mock hooks regardless** - The application should have a mocked backend and store all todos on it (extension of HttpXhrBackend)
example - https://stackblitz.com/edit/angular-http-backend-with-one-interceptor
- [ ] **Docker for Angular 13 in Codespaces** - You must configure Dockerfile and Docker-Compose to start this amazing application.
