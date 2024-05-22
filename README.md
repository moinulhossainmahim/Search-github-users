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

# 📚 What I have Learned

  - **React and Component-Based Architecture:**: Deepened understanding of React for building reusable UI components, enhancing modularity and maintainability of the application.
  - **State Management and API Handling**: Improved handling of application state and asynchronous data fetching using React's state management and lifecycle methods.

    ### Discovering New Tools:

     - **FusionCharts for Data Visualization:**: Learned to integrate FusionCharts to create interactive and visually appealing charts and graphs, providing insightful data representations.
     - **OAuth for Social Login Authentication**: Mastered the implementation of OAuth protocols for enabling secure social logins with Google, Facebook, and GitHub.
     - **Consuming GitHub API**: Acquired skills in fetching data from GitHub's free API, including user profiles, followers, and repositories, to display real-time information.
     - **React Router Dom for Navigation**: Gained expertise in implementing client-side routing to create a dynamic and seamless user experience.

## 💭 How can it be improved?

  - Show recent activities of the searched GitHub user, such as commits, pull requests, and issues.
  - Allow users to bookmark profiles and maintain a search history for quick access to frequently searched users.
  - Implement a dark mode option to enhance user experience, especially in low-light environments.
  - Increase test coverage by adding unit and integration tests, ensuring the reliability and stability of the application.
    
