UML Diagram Generator

A simple web-based tool to generate UML diagrams using PlantUML.
Users can enter PlantUML code and instantly visualize diagrams in the browser.

---

🚀 Features

- Generate UML diagrams from text
- Supports multiple diagram types:
  - Class Diagram
  - Use Case Diagram
  - Sequence Diagram
  - Activity Diagram
- Clean and simple user interface
- Works directly in the browser (no backend required)

---

🛠️ Technologies Used

- HTML
- CSS
- JavaScript
- PlantUML Encoder (CDN)

---

📂 Project Structure

UML-Diagram-Generator/
│── index.html
│── README.md

---

▶️ How to Run

1. Download or clone the repository:

git clone https://github.com/Hexa-Cortex/UML-GENERATOR-WEBSITE-

2. Open the project folder

3. Run the application:

- Simply open "index.html" in your browser

---

✍️ Sample UML Code

Paste this into the input box:

@startuml
class Student {
  -id: int
  -name: string
}

class Course {
  -courseName: string
}

Student --> Course : enrolls
@enduml

Click Generate Diagram to view the output.

---

⚠️ Important Notes

- Internet connection is required (uses PlantUML online server)
- Always include "@startuml" and "@enduml" in your code
- Ensure proper syntax to avoid errors

---

📌 Future Improvements

- Live preview while typing
- Download diagram as PNG
- Support for more UML templates
- Dark mode UI

---

🤝 Contributing

Feel free to fork this repository and contribute improvements.

---

📄 License

This project is open-source and available under the MIT License.

---

👨‍💻 Author

Developed as a mini project for learning and academic purposes.
