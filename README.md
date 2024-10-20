# YouTube Clone

This project is a YouTube Clone built using **ReactJS**. It mimics core functionalities of YouTube, allowing users to search for videos, view video details, and display a list of related videos.

## Features

- **Video Search**: Users can search for videos using the YouTube Data API.
- **Video Playback**: Selected videos are played with embedded player support.
- **Sidebar Navigation**: Quick access to different categories.
- **Related Videos**: Displays related videos for the current selection.
- **Responsive Design**: Optimized for different screen sizes.

## Components

The following are the core components of the project:

- **Feed**: Displays a feed of videos based on the current category.
- **Navbar**: Contains the search bar and quick navigation options.
- **PlayVideo**: Handles video playback and shows video details.
- **Recommended**: Shows a list of recommended or related videos.
- **Sidebar**: Provides navigation options to different video categories.
- 
## Technologies Used

- **ReactJS**: JavaScript library for building user interfaces.
- **Axios**: For making API requests to the YouTube Data API.
- **Material-UI**: For UI components and styling.
- **React Router**: For navigation between pages.
- **YouTube Data API**: For fetching video data.

## How It Works
1. Users can search for a video using the search bar in the Navbar.
2. The app sends a request to the YouTube Data API to fetch search results.
3. Clicking on a video opens the PlayVideo component, displaying the video and its details.
4. The Sidebar allows users to navigate through various categories, while the Feed component updates accordingly.
5. The Recommended component shows related videos to the currently selected video.

