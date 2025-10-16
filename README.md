# RandomRiffs

RandomRiffs is a personal productivity and blogging platform built with React. It combines a full-featured blog with task management capabilities and additional miscellaneous components for tracking books and axioms.

## About

This application serves as a personal hub for managing blog posts, tracking tasks, and maintaining a collection of thoughts and reading logs. The interface provides a clean, organized way to view and manage content with routing support for detailed views and editing capabilities.

## Features

### Blog Management
- Create, view, edit, and delete blog posts
- View individual blog post details
- Browse all posts with pagination support
- Recent posts displayed on the home page

### Task Management
- Track and organize personal tasks
- Integrated task component on the home page

### Additional Components
- Gypsy Axiom component for philosophical musings
- Book logs to track reading progress and notes

### Technical Features
- Built with React and Redux for state management
- React Router for navigation and routing
- Material-UI for consistent component design
- Responsive design for various screen sizes

## Prerequisites

Before running this application, ensure you have the following installed:
- Node.js (version 12 or higher recommended)
- npm (comes with Node.js)

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/pappater/randomriffs.git
   cd randomriffs
   ```

2. Install dependencies:
   ```
   npm install
   ```

## Development

To run the application in development mode:

```
npm start
```

This will start the development server and open the application in your default browser at [http://localhost:3000](http://localhost:3000). The page will automatically reload when you make changes to the code.

## Building for Production

To create a production-ready build:

```
npm run build
```

This command creates an optimized build of the application in the `build` folder. The build is minified and includes hashed filenames for caching purposes.

## Deployment

The application is configured for deployment to GitHub Pages. To deploy:

```
npm run deploy
```

This will build the application and deploy it to the GitHub Pages site configured in the package.json file.

## Testing

To run the test suite:

```
npm test
```

This launches the test runner in interactive watch mode.

## Project Structure

- `/src/components` - Contains all React components organized by feature
  - `blogComponent` - Blog listing and display
  - `blogDetailsComponent` - Individual blog post view
  - `blogEditForm` - Form for creating/editing posts
  - `homeComponent` - Main landing page
  - `taskComponent` - Task management interface
  - `navbarComponent` - Navigation bar
  - `miscellaneousComponent` - Additional features (Gypsy Axiom, Book Logs)
- `/src/store` - Redux store, actions, and reducers
- `/public` - Static assets and HTML template

## Technologies Used

- React 16.13
- Redux for state management
- Redux Saga for handling side effects
- React Router for navigation
- Material-UI for UI components
- Axios for API calls
- Moment.js for date handling

## License

This project is private and not licensed for public use.
