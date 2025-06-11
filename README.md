# MovieBox
Features:

1.Movie Search: Search for movies by title or keywords.
2.Type Filtering: Filter results by movies, TV series, or episodes.
3.Pagination: Navigate through large sets of search results.
4.Movie Details: View comprehensive movie information including plot, cast, ratings, and more.
5.Favorites Management: Add/remove movies to/from your favorites list.
6.Responsive Design: Optimized for desktop and mobile devices.
7.Error Handling: User-friendly error messages and loading states.

Tech Stack:

React.js: Frontend framework
JavaScript: Core functionality
HTML/CSS: Structure and styling
Tailwind CSS: Utility-first CSS framework
Lucide React: Icon library
OMDB API: Movie database API

Prerequisites
Before running this application, make sure you have:

Node.js (version 14 or higher)
npm or yarn package manager
OMDB API Key - Get your free API key from https://www.omdbapi.com/.

Project Structure:

movie-search-app/
├── public/
│   └── index.html
├── src/
│   ├── App.js          # Main application component
│   ├── index.js        # React DOM rendering
│   └── index.css       # Global styles with Tailwind
├── package.json        # Dependencies and scripts
├── tailwind.config.js  # Tailwind configuration
├── postcss.config.js   # PostCSS configuration
└── README.md          # Project documentation

Component Architecture
Main Components:

Router Component: Handles navigation between pages
SearchPage Component:
Search functionality
Results display
Pagination
Favorites management


MovieDetailsPage Component:
Detailed movie information
Add/remove from favorites

Features Implementation
Search & Filtering
Real-time search with Enter key support
Type filtering (All, Movies, TV Series, Episodes)
API-based filtering (not client-side filtering)

Pagination
Server-side pagination with 10 results per page
Navigation buttons with page numbers
Scroll to top on page change

Favorites System
Local storage persistence
Heart icon toggle
Favorites preview section
Cross-page favorites management

Error Handling
API error messages
Network failure handling
Empty results handling
Loading states

Styling:
The application uses Tailwind CSS with a dark theme:

Primary Colors: Gray scale with blue accents
Responsive Design: Mobile-first approach
Hover Effects: Smooth transitions and scale effects
Custom Scrollbar: Styled for better UX

Usage:
Search for Movies:
Enter a movie title in the search bar
Optionally select a type filter
Click Search or press Enter


Browse Results:
View movie posters and basic information
Use pagination to navigate through results
Click the heart icon to add/remove favorites


View Movie Details:
Click on any movie card to view detailed information
See plot, cast, ratings, and technical details
Add/remove from favorites


Manage Favorites:
View favorites section on the main page
Click on favorite movies to view details
Remove movies from favorites using the heart icon
