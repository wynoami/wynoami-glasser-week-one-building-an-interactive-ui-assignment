# Assignment: Building an Interactive UI

## Introduction

In this assignment, we will build a task management dashboard in a Blazor application. Our dashboard will be able to list, view, add, modify, and delete tasks. This will allow us to practice a variety of Razor syntax.

## Requirements

In the `Models` folder of our application, we have the `TaskItem` class that represents a task on a to-do list. We will need to build a dashboard that allows us to manage our task list. Here are the requirements that we will need to fulfill:

### List all tasks

We will need to be able to list all tasks on the page.

### Search tasks by title

We will need a free-text input field that would allow us to filter tasks by title. The filtering functionality needs to be triggered automatically when the user types anything in the box.

### Search tasks by status

We will need to be able to search tasks by their status. This needs to be done via a drop-down list. The filter will get triggered every time a value is selected in the drop-down list. The values allowed in the drop-down list are as follows:

* Not Started
* In Progress
* Completed

It also needs to have the additional value of **All Statuses**, which will reset the filter if selected.

### Add a task

We will need the ability to add a new task. The list of tasks on the page needs to be updated as soon as a new task is added.

### Edit tasks

We will need the ability to select and edit any existing task. The task status needs to be represented by a drop-down list with the values specified above.

## Deliverables

The deliverable of this assignment is a task-management app that adheres to the requirements above. It doesn't have to be styled in any particular way. It doesn't have to look good. It merely needs to fulfill its functional requirements.

## Conclusion

To get familiar with various types of Razor syntax, we need to practice it by building our own applications. This assignment provided us with such an opportunity.