# Ak-VideoTube Frontend

This is the frontend for AkVideoTube, built using React and Vite. It provides a modern, fast, and responsive user interface for interacting with the AkVideoTube platform.

## Features

- **React**: A powerful library for building user interfaces.
- **Vite**: Lightning-fast development environment with HMR (Hot Module Replacement).
- **TailwindCSS**: Utility-first CSS framework for styling.
- **Redux Toolkit**: State management for React applications.
- **React Router**: Declarative routing for React apps.
- **Axios**: Promise-based HTTP client for API requests.

## Project Structure

The project is organized as follows:

```
.env
.env.sample
.eslintrc.cjs
.gitignore
components.json
index.html
package.json
postcss.config.js
README.md
tailwind.config.js
vite.config.js
public/
    video.svg
    vite.svg
src/
    App.jsx
    constants.js
    index.css
    Layout.jsx
    main.jsx
    package.json
    components/
        AuthLayout.jsx
        Avatar.jsx
        Button.jsx
        ChangePassword.jsx
        CommentsList.jsx
        Container.jsx
        DeleteConfirmation.jsx
        Description.jsx
        Edit.jsx
        EditAvatar.jsx
        EditPersonalInfo.jsx
        ...
    helpers/
    pages/
    skeleton/
    store/
```

## Installation

1. Clone the repository:
     ```sh
     git clone https://github.com/akmroyal/Video-Tube-frontend.git
     cd akvideotube-frontend
     ```

2. Install dependencies:
     ```sh
     npm install
     ```

3. Create a `.env` file based on `.env.sample` and configure your environment variables.

## Scripts

### Start Development Server
To start the development server, run:
```sh
npm run dev
```

### Build for Production
To build the project for production, run:
```sh
npm run build
```

### Preview Production Build
To preview the production build locally, run:
```sh
npm run preview
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push them to your fork.
4. Submit a pull request.
