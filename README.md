# YouTube Clone

A modern and fully responsive **YouTube-style video platform** built with **React**.  
It allows users to browse trending videos, filter by categories, and watch selected videos along with recommendations — replicating the core experience of YouTube.

## Live Demo

You can see the live demo <a href="https://youtube-clone-peach-three.vercel.app/">HERE</a>

## Key Features

- **Browse Trending Videos** — Fetches the latest trending videos via the YouTube Data API v3
- **Filter by Categories** — Explore videos across Music, Sports, Gaming, News, and more
- **Video Playback** — Watch videos seamlessly with an embedded player
- **Related Recommendations** — Displays suggested videos based on selected category
- **Responsive UI** — Optimized for both desktop and mobile screens
- **Reusable Components** — Clean, modular structure following best React practices

## Tools Used

**React**: UI development using functional components.  
**React Router DOM**: Client-side routing for navigation.  
**YouTube Data API v3**: Fetching real-time video data.
**Moment.js**: Formatting dates and “time ago” functionality.  
**CSS**: Custom styling and responsive layout.  
**Vercel**: Deployment and hosting platform.

## Folder Structure

<img src="/FolderStructure.png" />

## Installation & Setup

Follow the steps below to run this project locally:

1. **Clone the repository**

   ```bash
   git clone https://github.com/Altamash-khn/Youtube-Clone.git
   cd Youtube-Clone
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Add your YouTube API Key**

   - Create a `.env` file in the root directory.
   - Add your API key:
     ```
     VITE_YOUTUBE_API_KEY=your_api_key_here
     ```

4. **Run the development server**

   ```bash
   npm run dev
   ```

5. **Open in your browser**
   ```
   http://localhost:5173
   ```
