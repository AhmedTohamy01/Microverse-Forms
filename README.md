## Forms

> In this project, we built a Rails app to demonstrate how to work with Active Forms.

> The project description can be found [here](https://www.theodinproject.com/courses/ruby-on-rails/lessons/forms#introduction).


* Ruby version  - 2.7.0

* Rails version - 5.2.4.3

* System dependencies - required gems are bundled with Gemfile 

* Configuration - from the project directory, run``` bundle install ```from command line (terminal) to install all the required gems.

* Database creation - After cloning the project, navigate to the project directory (``` cd Micro-Reddit ```), then execute the following command ``` rails db:migrate ```or``` bin/rails db:migrate ``` to 'migrate' database.

* How to run the test - Test should be run from CLI, by first starting the Rails server ``` rails server ```or```bin/rails server ``` from the project director. Then, open a new terminal in the same project directory, start a Rails console ``` rails console ``` to interact with the database via rails Active Record.

### Adding entries to Active Record
* Create a new user by executing the following command format in the rails console:
```
  u1 = User.new
  u1.username = "username"
  u1.password = "password"
  ui.email = "email"
  u1.save
```

* Execute ``` User.all ``` to list all the users with their ids

* Create a new post by executing the following command format in the rails console:
```
  p1 = Post.new
  p1.title = "Post title"
  p1.body = "Post body"
  p1.user_id = User id (listed by User.all)
  p1.save
```

* Comment on any post by executing the following command format in the rails console:
```
  c1 = Comment.new
  c1.body = "Comment body"
  c1.post_id = Post id (listed by Post.all)
  c1.user_id = User id (listed by Post.all)
  c1.save
```

> The following operations were involved in this project:
* Install Rails App.
* Add User Model, Add Post Model, Add Comment Model.
* Migrate the Database.
* Add Validations to all Models.
* Add Associations Between All Models.


## Authors

👤 **Ahmed Tohamy**

- Github: [@githubhandle](https://github.com/AhmedTohamy01) 
- Twitter: [@twitterhandle](https://twitter.com/AhmedTohamy01) 
- Linkedin: [linkedin](https://www.linkedin.com/in/ATohamy) 

👤 **Sunday Uche Ezeilo**

- Github: [@sundayezeilo](https://github.com/ezeilo-su)
- Twitter: [@SundayEzeilo](https://twitter.com/SundayEzeilo)
- Linkedin: [Sunday Ezeilo](https://www.linkedin.com/in/sunday-ezeilo-a6a67664/)

## 🤝 Contributing

Contributions, issues and feature requests will be appriciated.

Feel free to check the [issues page](https://github.com/AhmedTohamy01/Micro-Reddit/issues)

## Show your support

Show support by giving a ⭐️ if you like this project!