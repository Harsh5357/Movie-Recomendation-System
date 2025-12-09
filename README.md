# 🎬 Movie Recommender

A beautiful, interactive movie recommendation platform built with HTML, CSS (Tailwind), and vanilla JavaScript. Discover your next favorite film from a curated collection of 800+ movies across multiple genres!

## ✨ Features

- **800+ Curated Movies** - Handpicked collection spanning multiple genres and decades
- **Smart Filtering** - Filter by genre, mood, and streaming platform
- **Beautiful UI** - Modern gradient design with smooth animations
- **Fully Responsive** - Works perfectly on desktop, tablet, and mobile
- **Direct IMDb Links** - One-click access to full movie information
- **Zero Dependencies** - Pure vanilla JavaScript, no frameworks required

## 🎯 Filter Options

### Genres
- Action
- Comedy
- Drama
- Horror
- Romance
- Sci-Fi
- Thriller
- Documentary

### Moods
- Exciting
- Funny
- Emotional
- Scary
- Romantic
- Mind-bending
- Inspiring

### Streaming Platforms
- Netflix
- HBO Max
- Disney+
- Hulu
- Prime Video
- Apple TV+
- Paramount+

💻 Usage
Browse all movies - Scroll through the complete collection
Filter by genre - Click any genre button to see movies in that category
Set your mood - Choose how you're feeling to get mood-appropriate recommendations
Select platform - Filter by your available streaming services
Combine filters - Use multiple filters together for precise results
Click to learn more - Each movie card links directly to its IMDb page
🎨 Customization
Changing Colors
The app uses a purple gradient theme. To customize colors, update these classes in the code:

/* Main gradient */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Change to your preferred gradient */
background: linear-gradient(135deg, #your-color-1 0%, #your-color-2 100%);

Adding Movies
To add more movies, append to the moviesDatabase array:

{
  title: "Your Movie Title",
  year: 2024,
  genre: "Action",
  mood: "Exciting",
  rating: 8.5,
  platform: "Netflix",
  imdb: "tt1234567"
}

Modifying Filters
Add new filter options in the HTML and they'll automatically work with the existing JavaScript logic.

📱 Browser Support
✅ Chrome (latest)
✅ Firefox (latest)
✅ Safari (latest)
✅ Edge (latest)
✅ Mobile browsers (iOS Safari, Chrome Mobile)

🏗️ Tech Stack
HTML5 - Semantic markup
Tailwind CSS - Utility-first styling via CDN
Vanilla JavaScript - No frameworks, just pure JS
CSS Animations - Smooth transitions and hover effects

📂 Project Structure
movie-recommender/
├── index.html          # Main HTML file (contains all code)
└── README.md          # This file

🎯 Performance

Lightweight - Single HTML file, ~100KB total
Fast Loading - No external dependencies except Tailwind CDN
Smooth Animations - Hardware-accelerated CSS transforms
Efficient Filtering - Client-side filtering with instant results

🤝 Contributing

Contributions are welcome! Here's how you can help:
Fork the repository
Create a feature branch (git checkout -b feature/AmazingFeature)
Add more movies to the database
Improve the UI/UX
Add new filter categories
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request
Ideas for Contributions.

[ ] Add more movies (target: 1000+)
[ ] Add year range filter
[ ] Add rating filter
[ ] Add search functionality
[ ] Add movie trailers (YouTube integration)
[ ] Add "Save favorites" feature (localStorage)
[ ] Add dark/light theme toggle
[ ] Add movie posters (via API)

📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments
Movie data includes ratings and information from IMDb
UI inspiration from modern streaming platforms
Tailwind CSS for the amazing utility classes

Project Link: https:https://movie-recomendation-system-lilac.vercel.app/

Made with ❤️ and 🍿

Happy movie watching!



- Contributing guidelines
- Professional formatting
