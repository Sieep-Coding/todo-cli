# Todo List Application CLI

This project is a simple **Command-Line Interface (CLI) Todo List Manager** written in **Go.** 

It allows users to manage their tasks by **adding, deleting, editing, and toggling completion status.** 

Data is persistently stored in a *JSON file* for convenience.

## Available Flags

<table>
  <thead>
    <tr>
      <th>Flag</th>
      <th>Type</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>-add</code></td>
      <td>String</td>
      <td>Add a new todo. Specify the title of the task.</td>
    </tr>
    <tr>
      <td><code>-edit</code></td>
      <td>String</td>
      <td>Edit a todo by index. Use the format <code>id:new_title</code> to specify changes.</td>
    </tr>
    <tr>
      <td><code>-delete</code></td>
      <td>Int</td>
      <td>Specify a todo by index to delete.</td>
    </tr>
    <tr>
      <td><code>-toggle</code></td>
      <td>Int</td>
      <td>Specify a todo by index to toggle its completion status.</td>
    </tr>
    <tr>
      <td><code>-list</code></td>
      <td>Bool</td>
      <td>List all todos. Displays tasks in a formatted table.</td>
    </tr>
  </tbody>
</table>

## Installation

#### Step 1

Clone the repo

```bash
git clone https://github.com/sieep-coding/todo-cli.git
cd todo-cli
go mod tidy
```

#### Step 2

Build & run project

```bash
go build -o todo-cli main.go
./todo.cli
```
or

```bash
go run ./
```

## Author

Created By [Nick Stambaugh](https://www.linkedin.com/in/nick-s-694241139/)