# Search Github Users

**Search Github Users** is an web application that empowers users to effortlessly delve into the GitHub coding universe. User can search for GitHub profiles, gaining instant insights into repositories, followers, and programming languages used.


## 📦 Technologies

  - `React`
  - `CSS`
  - `Fusion Charts`
  - `Context API`
  - `0Auth Authentication`
  - `React Router Dom`

# 🚦 How to run the project

  ### Clone the repository
  - Clone this repository and cd into the project directory:
    ```bash
    git clone git@github.com:moinulhossainmahim/Search-github-users.git
    cd Search-github-users
    ```
  ### Update Environment Variables
  - Replace `env.example` file to `.env`
  - Create new apps in 0Auth and config the URL's and save the **ClientId and Auth Domain**
  - Update env environment variables
    ```bash
      REACT_APP_AUTH_DOMAIN="Your 0Auth app auth domain"
      REACT_APP_API_CLIENT_ID="Your 0Auth client ID"
    ```

  ### Install Dependencies
  - Run `npm install` inside the main project folder to install all dependencies from **NPM**.

  ### Start the application
  - 
    ```bash
      npm run dev
    ```

# ⚙️ Features

  - **User Authentication**: Supports manual login and social media login via Google, Facebook, and GitHub for easy access.
  - **GitHub User Search:**: Allows users to search for any GitHub username to retrieve detailed information.
  - **Profile Details:**: Displays comprehensive profile information including bio, location, and profile picture.
  - **Repositories Overview:**: Lists all public repositories with details such as stars, forks, and descriptions.
  - **Followers and Following:**: Provides information about the user's followers and the users they are following.
  - **Responsive Design:**: Ensures a seamless experience across different devices with a mobile-friendly interface.

