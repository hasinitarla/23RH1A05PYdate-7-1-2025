🌐 MRECW Static Website
A simple static website built with HTML and CSS for showcasing a basic layout structure, including:

Header

Navigation bar (menu)

Main content area

Footer

📁 Project Structure
pgsql
Copy code
project-folder/
├── index.html
└── style.css
📄 index.html
The HTML file defines the structure of the web page:

<head>: Links to the external style.css file

<body>:

.container: Wraps the full content

.header: Displays the welcome message

#menubar: Contains navigation links

.maincontent: Placeholder for main content

.footer: Reserved for footer content

🎨 style.css
The CSS file (style.css) controls the appearance and layout of elements like the header, menu, content, and footer. You can style it as needed to enhance visual appeal and responsiveness.

⚠️ Known Issues
There is a small error in the HTML code you may want to fix:

html
Copy code
</div class="maincontent"></div>
✅ Correct it as:

html
Copy code
<div class="maincontent"></div>
🚀 How to Run
Clone or download the project folder.

Open index.html in a web browser (double-click or use Live Server in VS Code).

Make sure style.css is in the same directory and properly linked.



