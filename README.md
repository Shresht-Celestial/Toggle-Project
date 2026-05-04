👁️ Toggle Info App

A minimal JavaScript application that demonstrates how to show and hide content dynamically using DOM manipulation and class toggling.

🚀 Features
Toggle visibility of a paragraph
Uses classList.toggle()
Simple and clean DOM interaction
Beginner-friendly logic


🛠️ Tech Stack
HTML5
CSS3
Vanilla JavaScript


📂 Project Structure
/project-root
├── index.html
├── style.css
├── script.js
└── README.md


⚙️ How to Run
Clone the repository
git clone https://github.com/your-username/toggle-info-app.git
Open the folder
cd toggle-info-app
Run the project
Open index.html in browser
OR
Use Live Server in VS Code
🧠 How It Works
JavaScript Function
function toggleInfo() {
    console.log("Toggling");
    const para = document.getElementById("myParagraph");

    para.classList.toggle("hidden");
    console.log(para.classList);
}


Explanation
Selects paragraph using getElementById
Uses classList.toggle("hidden"):
Adds class if not present
Removes class if already present
CSS Example
.hidden {
  display: none;
}


▶️ Usage

Add a button in HTML:

<button onclick="toggleInfo()">Toggle Info</button>
<p id="myParagraph">This is some hidden information.</p>


📸 Example
Click button → paragraph hides
Click again → paragraph shows


💡 Use Cases
Show/hide details
FAQ sections
Dropdown content
UI interactivity


📈 Future Improvements
Add animation effects ✨
Add multiple toggle sections
Add smooth transitions
Improve UI design


👨‍💻 Author
Shresht Gupta
GitHub: https://github.com/Shresht-Celestial
