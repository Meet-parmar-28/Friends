Friends App
Overview
Friends App is a web application built on Ruby on Rails that helps you manage your friend list efficiently. The app allows you to add, edit, and remove friends, keeping track of your social connections in a simple and organized manner.

Features
Add new friends to your list
Edit existing friend details
Remove friends from your list
View a list of all your friends
Responsive design for mobile and desktop use
Getting Started
Prerequisites
Ensure you have the following installed on your local machine:

Ruby (version 2.7.0 or higher)
Rails (version 6.0.0 or higher)
SQLite3 (or another preferred database)
Git
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/friends-app.git
cd friends-app
Install the required gems:

bash
Copy code
bundle install
Set up the database:

bash
Copy code
rails db:create
rails db:migrate
Start the Rails server:

bash
Copy code
rails server
Open your browser and navigate to http://localhost:3000 to see the app in action.

Usage
Adding a Friend
Click on the "Add Friend" button.
Fill in the friend's details (name, email, etc.).
Click "Create Friend" to save the new friend to your list.
Editing a Friend
Click on the "Edit" button next to the friend's name.
Update the friend's details as needed.
Click "Update Friend" to save the changes.
Deleting a Friend
Click on the "Delete" button next to the friend's name.
Confirm the deletion in the popup dialog.
Contributing
We welcome contributions from the community. To contribute, please follow these steps:

Fork the repository.
Create a new branch for your feature or bugfix.
bash
Copy code
git checkout -b my-new-feature
Make your changes and commit them.
bash
Copy code
git commit -am 'Add some feature'
Push your branch to GitHub.
bash
Copy code
git push origin my-new-feature
Create a new Pull Request.
License
This project is licensed under the MIT License - see the LICENSE file for details.