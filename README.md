Todo
====

Awesome TODO list:


## Usage:

```elixir
{:ok, todo_server} = Todo.Server.start

# Adding entries
Todo.Server.add_entry(todo_server, %{date: {2013, 12, 19}, title: "Dentist"})

# Get entries for a specific day
Todo.Server.entries(todo_server, {2013, 12, 19})
```
