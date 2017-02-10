# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
To store or access data on the server to let others access the same data.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
 utilizes both the model and the view components to perform the desired behavior and produce a response.
```

Which layer in the MVC pattern communicates with the model?

```md
Controller
```

Why don't we use views in our interpretation of the MVC pattern?

```md
serializers replace all the views that we care about for this program, so we can safely skip the views folder
```

What does C.R.U.D stand for?

```md
create,read, update, destroy - each refers to a specific type of action that can be performed on our data storage system
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
model
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
show, create, update, destroy
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
GET will retrieve data from the server only for reading, sql will select it and
and rails will show it.
```

What is the command to generate a new rails-api app?

```bash
rails new app
```

What is the command to start an instance of a rails server?

```bash

bin/rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
rake db:drop
rake db:create
rake db:migrate
rake db:seed
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash

$ bin/rails generate scaffold Pet name:string age:integer
```
