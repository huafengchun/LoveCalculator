Love Calculator Website
A fun, interactive website featuring multiple love-related tools: Love Calculator by Name, Love Calculator by Date of Birth, Love Language Test, Love Quotes, and Is It Real Love Quiz. All tools are designed for entertainment purposes with a responsive, mobile-friendly interface.

✨ Features
1. Love Calculator by Name
Uses the classic LOVES algorithm to calculate a compatibility percentage based on the occurrence of letters L, O, V, E, S in two names.

Step-by-step reduction to a two-digit percentage.

Results include a descriptive message based on the score.

2. Love Calculator by Date of Birth
Numerology-based compatibility calculation.

Computes Life Path Numbers for both persons and compares them using a compatibility table.

Displays life path numbers and a percentage score.

3. Love Test Quiz
20-question quiz that analyzes behavior and body language to gauge romantic interest.

Each question has four options with point values (0–3).

Total score converted to a 0–100 scale with detailed feedback and next-step advice.

4. Love Quotes
Collection of beautiful love quotes with category filters (romantic, short, deep, famous, funny, long-distance, heartbreak).

Each quote card includes copy and share buttons.

Featured quotes slider and a "Quote of the Day" section.

🛠️ Technology Stack
HTML5 – Semantic markup

CSS3 – Custom styling with variables, Flexbox, Grid, and responsive media queries

JavaScript (ES6) – Interactive logic, form handling, dynamic updates

Font Awesome 6 – Icons

No external dependencies – Vanilla JS only, runs entirely in the browser

📁 File Structure

love-calculator-website/
│
├── index.html                # Home page (name & birth date calculators)
├── love-test-quiz.html   # Love Language Test (20 questions)
├── love-quotes.html          # Love quotes gallery
├── README.txt                # This file
└── assets/                   # (optional) – images, if any

Note: The site uses inline CSS and JS for simplicity and portability. Each HTML file is self-contained.

🚀 How to Run
Download all HTML files to your computer.

Open any .html file in a modern web browser (Chrome, Firefox, Safari, Edge).

No internet connection required after the first load (except for Font Awesome icons, which are loaded via CDN).

To deploy online, simply upload the files to any static hosting service (GitHub Pages, Netlify, Vercel, etc.).

📖 Usage Guide
Home Page (index.html): Switch between the two calculators using the tabs. Enter names or birth dates and click the calculate button.

Love Language Test: Answer all 20 questions by clicking on the options. The submit button enables only after all are answered. Scroll down to see the detailed results.

Love Quotes: Use category buttons to filter quotes. Click the "Copy" button to copy a quote to clipboard. Use the "Load More" button to reveal additional quotes.

Is It Real Love Quiz: Answer 15 questions honestly. After submission, you'll get a score and interpretation. All data stays in your browser – no information is stored.

🧠 Customization
Adding New Quotes
Open love-quotes.html, find the quotes-grid div. Copy an existing quote card and modify:

data-categories attribute (comma-separated category names)

quote-text and quote-author

quote-tag spans

Update the copy-btn and share-btn data-quote attributes.

Modifying Questions
For Love Language Test, questions are defined as divs with class question. Each option is a div with data-value (0–3). Update text as needed.

For Is It Real Love Quiz, questions are in Chinese. Modify the HTML inside each .question block, and ensure options have data-value attributes (0–3). The scoring logic remains the same.

Styling
All CSS variables are defined in the :root selector at the top of each file. Change the color scheme by adjusting:

--primary (main pink)

--secondary (purple)

--dark, --gray, --light, etc.

⚠️ Important Notes
Entertainment Purpose Only: All calculators and tests are for fun and self-reflection. They are not scientifically validated and should not be used for making real-life relationship decisions.

Privacy: No user data is collected, stored, or transmitted. All calculations happen locally in your browser.

Copyright: All content is original. Quotes are either public domain or used with credit to authors. If you believe any content infringes your rights, please contact us.

📝 License
This project is open-source and available for personal and educational use. Feel free to modify and adapt it for your own website. Commercial use requires permission.

For questions or suggestions, please open an issue on the project repository or contact us via the website contact page.

Enjoy exploring the mysteries of love! ❤️

Last updated: March 2025
