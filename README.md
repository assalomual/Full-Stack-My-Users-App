# My Users App
This application implements MVC (Model View Controller) architecture to support users.
# Description
In this project, a test application will be created to create, search, view, update and delete users. A ``User'' class is created and ``sqlite3'' is used.
# Task
The following functions are implemented in the program:
- Create users
- Search for users
- View all users
- Update users
- Delete users

The program returns data in JSON or HTML format, and the program places users in their session.
# Usage
To run the program, follow these steps:
1. Download the program.
2. Run the program: `ruby app.rb`.
3. Go to `http://localhost:4567/` in your browser and see the program activity.
# Installation
To install the program, you need to install the `sqlite3` and `sinatra` packages:
```bash
gem install sqlite3
gem install sinatra