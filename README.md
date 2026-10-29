# CSE Department Website

A simple, responsive departmental website developed using **HTML5 and CSS3** for the Computer Science and Engineering Department of the Federal Institute of Science and Technology (FISAT), Angamaly.

## About the Project

This project demonstrates how HTML and CSS can be used to design a college department website that presents academic and departmental information in a structured and user-friendly format.

The website follows a navy blue, orange, and white colour scheme and includes navigation links, an expandable semester-wise curriculum, faculty information, departmental facilities, and a student enquiry form.

## Features

- **Department Information:** Introduction, vision, and mission.
- **Semester-wise Curriculum:** Expandable sections for Semesters 1–8.
- **Faculty Information:** Faculty details displayed in a structured table.
- **Department Facilities:** Information about laboratories, learning resources, and project facilities.
- **Useful Links:** Links to the official FISAT website and internal sections.
- **Student Enquiry Form:** Fields for name, email, phone number, course preference, and enquiry message.
- **Contact Information:** College address and official website.
- **Responsive Design:** CSS media queries help adapt the layout to smaller screens.
- **Interactive Styling:** Hover and focus effects for links, buttons, and form controls.

## Technologies Used

- HTML5
- CSS3
- Visual Studio Code
- Web browser for testing
- Git and GitHub for version control and repository hosting

## Project Structure

```text
FISAT-CSE-Department-Website/
│
├── index.html
├── README.md
├── image/
│   └── fisat.jpg
└── report.tex
```

**Note:** Keep `image/fisat.jpg` in the specified folder if you want the college image to display correctly. Include `report.tex` only if you are storing the LaTeX report in the same repository.

## How to Run the Project

1. Clone or download this repository.
2. Open the project folder in Visual Studio Code.
3. Check that the image file is available at `image/fisat.jpg`.
4. Open `index.html` in a web browser.

Alternatively, install the **Live Server** extension in Visual Studio Code, right-click `index.html`, and select **Open with Live Server**.

No backend server, database, or package installation is required to display the current website.

## Implementation Details

### HTML

HTML is used to structure the website using semantic elements such as `header`, `nav`, `main`, `section`, `article`, and `footer`. Tables, lists, images, hyperlinks, and form elements are used to organize the content.

### CSS

CSS is embedded in the HTML file and is used for colours, typography, spacing, borders, layout, hover effects, and responsive styling. CSS variables provide reusable colour values.

### Expandable Curriculum

The curriculum uses the HTML `details` and `summary` elements. Clicking a semester heading expands or collapses its list of subjects without requiring JavaScript.

### Enquiry Form

The form demonstrates HTML input fields and browser-side validation using attributes such as `required`, `type="email"`, and `pattern`.

**Limitation:** The current form does not permanently store submissions or send them to the department. Backend processing or a form service would be required for that functionality.

## Future Enhancements

- Connect the enquiry form to a backend and database.
- Add an administration interface for updating faculty and curriculum details.
- Verify and maintain curriculum information using the applicable university scheme.
- Improve accessibility and test the layout across different browsers and devices.
- Deploy the website using GitHub Pages or another web hosting service.

## References

- [FISAT Official Website](https://www.fisat.ac.in/)
- [MDN Web Docs — HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [MDN Web Docs — CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [WHATWG — HTML Living Standard](https://html.spec.whatwg.org/)

## Author

**Aleena K J**  
B.Tech Computer Science and Engineering  
Federal Institute of Science and Technology (FISAT)

---

*This project was developed for educational purposes as part of an HTML and CSS website design assignment.*
