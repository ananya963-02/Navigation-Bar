🌐 HTML & CSS Navigation Bar

A simple and beginner-friendly webpage demonstrating a navigation bar styled with HTML and CSS. The project includes a gradient background, rounded navigation menu, hover animations, and links to multiple pages.

📌 Features

- Responsive viewport setup
- Horizontal navigation bar
- Brown rounded navigation menu
- White navigation links
- Blue-to-pink gradient background
- Hover effect with scaling animation
- Links to:
  - Home
  - About Us
  - Gallery
  - Achievements
  - Contact Us

🛠️ Technologies Used

- HTML5
- CSS3

📂 Project Structure

project-folder/
│
├── index.html
├── About.html
├── Galllery.html
├── Achivements.html
└── Contact Us.html

🚀 How to Run

1. Download or clone this project.
2. Make sure all HTML files are in the same folder.
3. Open "index.html" in any modern web browser.
4. Click the navigation links to move between pages.

🎨 CSS Highlights

Navigation Bar

The navigation menu uses Flexbox to arrange the links horizontally:

ul {
    width: 80%;
    list-style-type: none;
    display: flex;
    justify-content: space-evenly;
    height: 100px;
    align-items: center;
    background-color: brown;
    color: white;
    border-radius: 40px;
}

Gradient Background

The main container has a blue-to-pink gradient:

.box {
    height: 900px;
    justify-content: center;
    align-items: center;
    display: flex;
    background: linear-gradient(blue, pink);
}

Hover Animation

When the mouse is placed over a navigation item, it becomes larger:

li:hover {
    transform: scale(1.5);
}

🔗 Navigation Links

Page| File
Home| "index.html"
About Us| "About.html"
Gallery| "Galllery.html"
Achievements| "Achivements.html"
Contact Us| "Contact Us.html"

📖 Purpose

This project is useful for beginners learning:

- HTML page structure
- CSS styling
- Flexbox
- Navigation menus
- CSS gradients
- Hover effects
- Basic webpage linking

✨ Future Improvements

Some possible improvements include:

- Making the navigation bar fully responsive for mobile devices
- Adding smooth hover transitions
- Improving accessibility
- Correcting file naming and spelling ("Galllery.html", "Achivements.html")
- Moving CSS into a separate "style.css" file
- Adding icons to navigation items

📄 License

This project is free to use for learning and educational purposes.# Navigation-Bar
