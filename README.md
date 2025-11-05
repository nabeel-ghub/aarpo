Aarpo 🔐

A lightweight Express.js application that validates users through a unique code verification system.
It checks if a user’s code exists in a local codes.json file using Node’s File System (fs) module.
If the code is valid, the user is granted access to the next page rendered via EJS templates; otherwise, an error message is displayed.

⸻

🚀 Features
	•	Validates users through a unique code input system.
	•	Reads and verifies codes from a local codes.json file.
	•	Uses EJS templating to render pages dynamically.
	•	Lightweight and easy to set up — built purely with Express.js and fs.
	•	Perfect for simple code-based access systems or event entry validation.

⸻

🛠️ Tech Stack
	•	Node.js
	•	Express.js
	•	EJS (Embedded JavaScript templates)
	•	fs (File System) module
	•	JSON-based data storage

⸻

⚙️ Setup & Installation
	1.	Clone the repository

git clone https://github.com/yourusername/aarpo.git
cd aarpo


	2.	Install dependencies

npm install


	3.	Create or update the codes.json file

[
  "ABC123",
  "XYZ789",
  "HELLO456"
]


	4.	Run the server

node index.js


	5.	Open your browser
Visit http://localhost:3000￼

⸻

🧠 How It Works
	1.	The home page (EJS) contains a form for entering the user’s unique code.
	2.	Upon form submission, the app reads codes.json using the fs module.
	3.	If the entered code exists, it renders a success page; otherwise, it shows an error page.

⸻

📜 License

This project is open-source and available under the MIT License￼.

⸻

Aarpo — Simple. Secure. Smart. Validate with ease. 🔐
