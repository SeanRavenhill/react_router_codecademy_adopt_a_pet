# Pet Adoption Website with React Router v6

This project is part of my coursework for the **Codecademy Front-End Engineer Career Path** certification. It demonstrates the use of React Router v6 to implement client-side routing for a pet adoption website.

The primary focus of this project was to further my understanding of routing concepts, dynamic paths, and URL parameters in a React application. I am fully aware that this project is not visually appealing, nor is it responsive. The emphasis was on learning and applying the theory taught in the module, rather than on design or responsiveness.

## Project Overview

The project implements the following functionality:

1. **Home Page**:
   - Displays a list of adoptable pets.
   - Filters the pets by species (dogs, cats, rabbits, birds) using dynamic URL parameters.
   
2. **Pet Details Page**:
   - Displays details for a specific pet based on the pet's species and unique ID, which are passed via the URL parameters.
   
3. **Search Feature**:
   - Users can search for a pet by name using a search bar. The app redirects them to a search results page using query parameters in the URL.
   
4. **Pet Not Found Page**:
   - If a user tries to view the details of a pet with incomplete or missing information, they are redirected to a "Pet Not Found" page.
   - From the "Pet Not Found" page, users can return to the homepage via a "Go Home" button.

## Key Concepts Practiced

This project was designed to apply the following React Router v6 concepts:

- **Router Setup**:
  - Installed and configured `react-router-dom` to enable client-side routing.
  - Used `RouterProvider` to manage routing for the application.

- **Static and Dynamic Routes**:
  - Created static and dynamic routes using `Route` and URL parameters.
  - Nested routes were implemented using the `Outlet` component.

- **Navigation**:
  - Used `NavLink` for navigation links with active state styling.
  - Used `Link` to prevent full page reloads when navigating between pages.

- **URL Parameters and Query Parameters**:
  - Used the `useParams` hook to access URL parameters for pet species and ID.
  - Implemented query parameters using the `useSearchParams` hook for the search functionality.

- **Imperative Navigation**:
  - Utilized the `useNavigate` hook to redirect users programmatically after certain actions (e.g., submitting the search form or clicking the "Go Home" button).

## Setup and Installation

To run this project locally:

1. Clone the repository.
2. Install the necessary dependencies:
   
   ```bash
   npm install
   ```
   
3. Start the application:
   
   ```bash
   npm start
   ```

The app should now be running at `http://localhost:3000`.

## Acknowledgements

This project is part of my certification coursework with **Codecademy** and focuses on the practical implementation of routing in a React application. The design is intentionally minimal, and no effort was made to ensure responsiveness or visual appeal. The goal was to enhance my understanding of React Router and apply the concepts learned throughout the module.

