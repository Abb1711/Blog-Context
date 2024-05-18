# Blog Context Project

This project is a React-based blog application that displays blog posts and allows users to filter posts by tags and categories. The application uses React Router for navigation and context for state management.

## Features

- Display a list of blog posts.
- Filter blog posts by tags.
- Filter blog posts by categories.
- View individual blog posts.
- Toggle between different pages of blog posts.

## Technologies Used

- React
- React Router
- Context API
- CSS

## Getting Started

### Prerequisites

- Node.js
- npm (Node Package Manager)

### Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/your-username/blog-context-project.git
    ```

2. Navigate to the project directory:

    ```sh
    cd blog-context-project
    ```

3. Install the dependencies:

    ```sh
    npm install
    ```

4. Start the development server:

    ```sh
    npm start
    ```

5. Open your browser and navigate to `http://localhost:3000`.

## Usage

1. The home page displays a list of blog posts.
2. Click on a blog post to view the details.
3. Use the navigation to filter blog posts by tags or categories.
4. The application will automatically fetch and display the relevant blog posts based on the current route and search parameters.

## Code Overview

### Main Components

- **App**: The main component that sets up the routes and handles fetching blog posts based on the current location.
- **Home**: The component that displays the list of blog posts.
- **BlogPage**: The component that displays an individual blog post.
- **TagPage**: The component that displays blog posts filtered by a specific tag.
- **CategoryPage**: The component that displays blog posts filtered by a specific category.

### Context

- **AppContext**: Provides the context for fetching and storing blog posts.

### React Router

- **Routes**: Defines the routes for the application.
  - `/`: Home page displaying all blog posts.
  - `/blog/:blogId`: Page displaying an individual blog post.
  - `/tags/:tag`: Page displaying blog posts filtered by a specific tag.
  - `/categories/:category`: Page displaying blog posts filtered by a specific category.

### useEffect Hook

- **useEffect**: Fetches blog posts whenever the location or search parameters change.

  
## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [React](https://reactjs.org/)
- [React Router](https://reactrouter.com/)

