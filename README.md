# Friends App

## Overview

Friends App is a web application built on Ruby on Rails that helps you manage your friend list efficiently. The app allows you to add, edit, and remove friends, keeping track of your social connections in a simple and organized manner.

## Features

- Add new friends to your list
- Edit existing friend details
- Remove friends from your list
- View a list of all your friends
- Responsive design for mobile and desktop use

## Getting Started

### Prerequisites

Ensure you have the following installed on your local machine:

- Ruby (version 2.7.0 or higher)
- Rails (version 6.0.0 or higher)
- SQLite3 (or another preferred database)
- Git

### Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/Meet-parmar-28/railsfriend.git
    cd friends-app
    ```

2. **Install the required gems:**

    ```sh
    bundle install
    ```

3. **Set up the database:**

    ```sh
    rails db:create
    rails db:migrate
    ```

4. **Start the Rails server:**

    ```sh
    rails server
    ```

5. **Open your browser and navigate to `http://localhost:3000` to see the app in action.**

## Usage

### Adding a Friend

1. Click on the "Add Friend" button.
2. Fill in the friend's details (name, email, etc.).
3. Click "Create Friend" to save the new friend to your list.

### Editing a Friend

1. Click on the "Edit" button next to the friend's name.
2. Update the friend's details as needed.
3. Click "Update Friend" to save the changes.

### Deleting a Friend

1. Click on the "Delete" button next to the friend's name.
2. Confirm the deletion in the popup dialog.

## Contributing

We welcome contributions from the community. To contribute, please follow these steps:

1. **Fork the repository.**
2. **Create a new branch for your feature or bugfix:**

    ```sh
    git checkout -b my-new-feature
    ```

3. **Make your changes and commit them:**

    ```sh
    git commit -am 'Add some feature'
    ```

4. **Push your branch to GitHub:**

    ```sh
    git push origin my-new-feature
    ```

5. **Create a new Pull Request.**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.