# Netflix clone

The React application described above was meticulously crafted using a robust technical stack. Create React App (CRA) served as the foundational tool, streamlining the project setup, while Tailwind CSS elevated the user interface with a utility-first approach to styling. React Router facilitated smooth navigation, and Firebase played a pivotal role in user authentication and state management.
Redux was employed for global state management, and a dedicated userSlice was created to organize user-related actions and state. The integration of TMDB API enriched the application with real-time data on now playing movies, complemented by YouTube API for embedding autoplaying and muted trailer videos.
The implementation of GPT-powered search introduced a sophisticated natural language query feature. Git served as the version control system, ensuring collaboration and a well-documented project history. Additional tools included custom hooks for logic optimization, constants for managing hardcoded values, and multilingual support for a personalized user experience. This cohesive technical stack harmoniously blended foundational tools with advanced features, resulting in a secure, responsive, and feature-rich React application for an immersive exploration of the cinematic worlds
- Create React App
- Configured Tailwind
- Header
- Routing of App
- Login Form
- Sign Up Form
- Form Validations
- useRef Hook
- Firebase Setup
- Create Signup user account
- Implement Sign In user Api
- Created Redux Store with userSlice
- Implemented signout feature
- Update Profile
- BugFix: Sign up user displayname and profile picture update
- BugFix:if the user is not logged in redirect him to login page and viceversa
- Unsubscribe to the onauthStateChanged call back
- Add hardcoded values to the constants
- Register for TMDB api && create an app && get access token
- Get Data from TMDB now playing
- Custom hook for now playing movies
- Create movieslice
- Update store with movies data
- planning for maincontainer & secondary container
- Fetch data for trailer video
- update store with trailer video data
- embedded the youtube vide and make it autoplay and mute
- Build secondary component
- Build the movie list
- Build movie card
- TMDB imagecdn url
- Made the browse page amazing with tailwind
- Creating custom hook
- GPT Search Feature
- GPT Search Page and Search Bar
- Multilingual Feature

# Features Of Netflix Clone

- Login / SignUp
  - Sign In /Sign Up Form
  - Redirect to Browse Page
- Browse (After Authentication)
  - Header
  - Main Movie
    - Trailer in bg
    - Movie Title And Description
    - Movie Suggestions
      - Movie Lists X N
- NetflixClone
  - Search Bar
  - Movie Suggestions
