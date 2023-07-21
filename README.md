# Todo_App

## Framework and Language

> Framework: SpringBoot Language: Java 8

## Data flow

1.  Controller

        1.1  Todo Controller
                - @GetMapping("todos") : To get list of all Todo's
                - @GetMapping("todo/done") : To get list of all done Todo's
                - @GetMapping("todos/{todoId}") : To get Todo by id
                - @GetMapping("todo/undone") : To get a list of undone a todo's
                - @PostMapping("todo") : To post a todo
                - @PutMapping("todo/{todoId}/{status}") : To update todo status by id
                - @DeleteMapping("todo") : To delete a todo


2.  Services

        2.1  Todo Service
                - getAllTodos() : To get list of all Todo's
                - getAllDoneTodos() : To get list of all done Todo's
                - getTodoById(Integer todoId) : To get Todo by id
                - getUndoneTodos() : To get a list of undone a todo's
                - addTodo(Todo myTodo) : To post a todo
                - updateTodoStatus(Integer todoId,boolean status) : To update todo status by id
                - removeTodo(Integer todoId) : To delete a todo

3.  Repository

        3.1 Todo Repo
        

4.  Database Design

        4.1 Todo Model:
                - Integer todoId
                - String todoName
                - boolean isTodoDoneStatus
        

## Data Structure Used in Project

    ArrayList has been used as primay datastructure

## Project Summary

    The Todo API  is a comprehensive software solution designed to keep track of todo's . The system provides a centralized platform that enables  user to create, read, edit, and delete todo.
