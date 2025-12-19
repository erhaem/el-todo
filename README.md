# el-todo

Simple todo list using Ruby on Rails.

## Setup

### Clone Repository

```bash
git clone https://github.com/erhaem/el-todo
cd el-todo
```

### Install dependencies

```bash
bundle install
```

### Database setup

This project uses PostgreSQL. Please create a PostgreSQL user and development/test databases. Example database names: `el_todo_development` and `el_todo_test`

Then do the configuration in [config/database.yml](config/database.yml). Run this following afterwards:

```bash
rails db:prepare
```

### Run the app

```bash
rails s
```

Access the app at:
http://localhost:3000

### Project Structure

Directories or files that matter in this project.

```
app/
├── models/
│   └── todo.rb
├── controllers/
│   └── todos_controller.rb
├── views/
│   └── todos/
│       ├── index.html.erb
│       ├── show.html.erb
│       ├── new.html.erb
│       ├── edit.html.erb
│       └── _form.html.erb
config/
├── routes.rb
├── database.yml
db/
└── migrate/
    └── 20251219095513_create_todos.rb

```
