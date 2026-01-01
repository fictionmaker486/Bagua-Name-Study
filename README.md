# Bagua-Name-Study
I Ching Name Numerology Analyzer
This is a browser-based name analysis tool that combines the traditional "Five Grids Method" (Wu Ge) with "I Ching Bagua" principles. By inputting a surname and given name, the system automatically calculates the Heavenly, Personality, Earthly, Total, and Outer Grids, and derives the corresponding Bagua symbols and Five Elements interactions.

✨ Features
Five Grids Auto-Calculation: Automatically calculates the numerology of the Five Grids based on Kangxi stroke counts.

Bagua Visualization: Converts numbers into intuitive Bagua symbols (☰ ☱ ☲ ☳ ☴ ☵ ☶ ☷).

Smart Stroke Correction: Includes a built-in simple Kangxi dictionary database and allows users to manually correct stroke counts for rare characters to ensure analysis accuracy.

Single File Design: All logic and styling are encapsulated in a single HTML file. It is ready to use upon download, with no backend server required.

Responsive Design: Built with Tailwind CSS, ensuring perfect display on both mobile devices and desktops.

🚀 How to Use (Online Version)
(Paste your GitHub Pages link here, e.g., https://your-username.github.io/bagua-name-solver/)

📦 How to Install & Run (Local Version)
Download the index.html file from this project.

Open the file directly using a web browser (Chrome, Edge, Safari, Firefox).

Enter the surname and name, then click "Start Analysis".

🛠️ Technical Architecture
HTML5 / CSS3

JavaScript (ES6+): Core logic and calculations.

Tailwind CSS (CDN): Rapid layout and UI styling.

Font: Noto Serif TC.

📝 Numerology Logic Explanation
This tool applies the following rules for calculation:

Stroke Standard: Based on Traditional Chinese strokes from the Kangxi Dictionary (e.g., the "water" radical 氵 counts as 4 strokes, the "grass" radical 艹 counts as 6 strokes).

Bagua Correspondence: The grid numbers are divided by 8, and the remainder is used to determine the corresponding Bagua numerology.

Five Elements Determination: Determined by the last digit of the number (1, 2 = Wood; 3, 4 = Fire; 5, 6 = Earth; 7, 8 = Metal; 9, 0 = Water).

⚠️ Disclaimer
This tool is intended for programming research and entertainment purposes only. There are many schools of name numerology; the calculation results do not represent any form of life advice or guarantees.

📄 License
MIT License
