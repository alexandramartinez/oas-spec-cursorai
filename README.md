# 📝 To-Do API – OpenAPI Spec Generated with Cursor AI

This repository contains an OpenAPI 3.0 specification for a simple **To-Do App API**, created live using **Cursor AI**.

> 📺 This spec was generated during a live stream on the [MuleSoft Community Twitch channel](https://www.twitch.tv/mulesoft_community).  
> 📌 Watch the full recording [here](https://www.youtube.com/watch?v=DdyqNXW_lGo).

## 📋 Cursor AI Design Rules

See [`to-do-api-spec-rules.mdc`](/To%20Do%20App/.cursor/rules/to-do-api-spec-rules.mdc) for the design guidelines auto-generated by Cursor AI. These rules enforce consistency and best practices for future OpenAPI work in this repo.

## 🔍 Overview

This OpenAPI spec describes a RESTful API for managing to-do tasks. It includes standard CRUD operations:

- `GET /todos`: List all todos
- `POST /todos`: Create a new todo
- `GET /todos/{todoId}`: Get a specific todo by ID
- `PUT /todos/{todoId}`: Update a todo
- `DELETE /todos/{todoId}`: Delete a todo

The spec uses clean, reusable components (`Todo`, `TodoInput`, `Error`) and follows best practices outlined in the Cursor-generated API design rules.

## 📐 OpenAPI Highlights

- ✅ DRY schema design using `$ref`
- ✅ Centralized examples in component schemas
- ✅ Clean separation between `Todo` (output) and `TodoInput` (input)
- ✅ Standard error handling with a reusable `Error` schema
- ✅ Operation IDs, descriptions, and consistent naming conventions

