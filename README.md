React Image Gallery with Unsplash API

This is a dynamic and responsive Image Gallery application created with React. It uses the Unsplash API to get photos depending on user search queries, and TanStack Query for efficient data fetching and caching. To avoid prop drilling, the global state is controlled with the React Context API.

Features:
1.Dynamic Image Search
Users can search for images by entering keywords. The app fetches relevant images in real-time using Unsplash API.

2.Data Fetching with TanStack Query
Efficient API calls using useQuery from @tanstack/react-query with caching and loading/error states handled seamlessly.

3.Dark/Light Mode
The app supports dark mode and remembers the user’s preference using localStorage.

4.Global State Management with Context API
Search terms and theme settings are managed globally using React’s Context API, reducing prop drilling.

5.Responsive UI
Clean and responsive design to display image results.

Tech stack:
* React (Functional Components and Hooks)
* TanStack query (data fetching and caching)
* Context API (Global state management)
* Unsplash API (Image retrieval)
* CSS (styles for responsive layouts)