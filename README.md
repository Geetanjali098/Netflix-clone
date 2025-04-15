# Netflix Clone with React and Firebase

This Netflix clone application built with React, Redux, and Firebase.
The application mimics Netflix's core functionality with movie browsing, categorized content, and a responsive UI.

## Key Features

1. **React-Redux Architecture**: 
   - Uses Redux for state management to handle movies and genres
   - Implements async actions with `fetchMovies` and `getGenres`
   - Connects to the store using `useSelector` and `useDispatch`

2. **UI Components**:
   - Hero section with featured content (Superman in this example)
   - Custom styled components using `styled-components`
   - Responsive navigation bar (`TopNav`) that changes on scroll
   - Movie sliders (`SliderContainer`) for categorized content
   - Interactive buttons for playback and more information

3. **Technical Implementation**:
   - React hooks (`useState`, `useEffect`) for component state and side effects
   - Scroll detection for UI effects
   - React Router integration for navigation
   - Firebase backend (implied by the Redux actions) for data storage

4. **Visual Design**:
   - Gradient text effects
   - Image brightness control for better text visibility
   - Responsive layout with absolute positioning
   - Custom button styling

## About the Netflix Clone

This Netflix clone is a full-stack application that likely uses:
- **React** for the frontend framework
- **Firebase** for backend services including authentication and database
- **Redux** for state management
- **Styled Components** for CSS-in-JS styling

The application demonstrates modern web development practices including component-based architecture, state management, and responsive design.
The hero section showcases featured content with play buttons that would presumably connect to a video player component (`/player` route).
The movie data appears to be fetched from a Redux store that interfaces with Firebase, allowing for real-time updates to the movie catalog.

The styling shows attention to detail with Netflix-like UI elements including the dark theme, gradient text effects, and hover states on interactive elements.
The scroll behavior detection suggests a dynamic header similar to Netflix's implementation.
