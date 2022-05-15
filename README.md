# DMA_TO_DO

## About the Installation of the Todo App
#### *** 1 Register and Sign Up:***
Fill in the Information that is required in Register and Sign Up.
#### *** 2 Login:***
After Filling up the register form and signing Up, Login with the same credentials.
##### ***3 Todo List:***
Click on the floating Add icon on the bottom right of the screen and create a task you want to track with its required infos
#### ***4 Todo Item:*** 
After creating a Todo Item, Now click on the create and Create your Todo Items.
#### ***5 Editing the Todo Items:***
Click on the Todo Item to update and edit it.
#### ***6 Deleting the todo items and Undo if you mistakenly deleted it ***.
You can swipe to delete the todo-list items and snackbar shows undo to undelete the item.
#### ***7 Deleting all List item***.
You can delete all the taks by clicking upon the menu option/more option near logout which will provide you delete all task options.
#### ***8 Logout Button***.
You can logout using the Logout button which will save all your tasks in your account only.

---

### Design Architecture 
# MODEL
* `adapter`  consists of recyclerviews adapters.<br>
-`SwipeLeftDelete`<br>
-`TodoListCallbacks`<br>
* `Database` consists of dao(class for room database) ,UserAuthentication,db..<br>
-`DataAccessObject`<br>
-`AppDatabase`<br>
-`Dateconvert`<br>
-`RegisterUserAuthentication`<br>
-`TodoLists`<br>


# `VIEW`
* `Data`  consists of all the datas i.e notification, session, task, user<br>
-`Screens` consists all the screens i.e addeditTask, login, menu, splash, tasks <br>



# `ViewModel`
* `LoginRegisterViewModel`  <br>
* `LogoutViewModel` <br>
* `AddEditTaskViewModel` <br>
* `SplashViewModel` <br>
* `DeleteAllTasksViewModel` <br>
* `MainActivityViewModel` <br>

## Features
Sign-IN                   |  Register                    | Adding Task 
:----------------------------:|:--------------------------------------:|:----------------------:|

![login](https://user-images.githubusercontent.com/50354345/168484285-bf0e3cfa-f311-45b0-a42f-0a900c7352c6.gif)


![registration](https://user-images.githubusercontent.com/50354345/168484306-f66bcd6a-2cc2-479d-80c9-2f788f8fae67.gif)


![add list](https://user-images.githubusercontent.com/50354345/168484253-698ff41d-3d51-4149-a60c-cac0075aee03.gif)

Undo         |  Menu-DeleteAllTask                  |      Notificaton
:----------------------------:|:--------------------------------------:|:----------------------:|

![delete and undo](https://user-images.githubusercontent.com/50354345/168484375-3435dbbe-56e2-486f-b546-6e5b844c5103.gif)


![delete all](https://user-images.githubusercontent.com/50354345/168484380-a910afa3-da5f-46d3-8026-4fdd520479e8.gif)


![notification](https://user-images.githubusercontent.com/50354345/168484390-16f3503f-72bd-4135-aa1a-d07af1c3e617.gif)

----------------------------
