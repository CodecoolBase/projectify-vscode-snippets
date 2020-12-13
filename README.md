# Projectify

Developing curriculum in Codecool is not the simplest thing to do as a mentor.
With this code snippet collection I would like to help to make easier and more pleasant to create new content in our curriculum.

> Before you dive into creating new projects please investigate our [projectify guide](https://codecool.atlassian.net/wiki/spaces/WOR/pages/982450199/Guide+How+to+create+projects+in+the+curriculum+Projectify)

## Features

### `project.yaml`

* `proj-meta`: generating `project.yaml` body

### `tasks.yaml`

* `task`: creates a task with all necessary attributes
* `req`: creates a requirement for a task
* `general`: creates GENERAL requirement block

![Tasks yaml snippets](images/tasks.gif)

#### General tasks

![General task](images/general.gif)

### `course.yaml`

* `group`: generates a group node
* `proj`: generates a project node
* `tut`: generates a tutorial node, id automatically parsed to label
* `mile`: generates a milestone node, id automatically parsed to label

![Course yaml snippets](/images/course.gif)

> You can read more about the different types of building blocks in coruse.yaml in our `[Guide: How to build and update a course in Journey](https://codecool.atlassian.net/wiki/spaces/WOR/pages/1276706892/Guide+How+to+build+and+update+a+course+in+Journey+technical+quide#Group)`

### Inside markdown files

* `comps`: creates competencies block
* `link-yt`: youtube link with thumbnail image
* `link-in`: inner link reference to our materials, icon type selectable
* `link-out`: outer link
* `link-vid`: video link
* `if-lang`: Project language switch in case of multi-language projects
* `img`: image
* `code`: Syntax highlighted code block
* `uml`: basic plant uml template for class diagram
* `quiz`: creates an empty quiz without questions
* `quiz-q`: question template inside a a quiz block
* `tutorial`: generates a skeleton for a tutorial page

## Installation

1. Clone the repository
2. Open a terminal
3. Navigate to the repo folder
4. Run the following command:

    `code --install-extension projectify-1.1.1.vsix`

5. Restart your VS Code
