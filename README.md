# Engineering Unit Converter

## Overview
Engineering Unit Converter is a web-based application that allows users to convert between various engineering units (force, pressure, energy, power, torque, velocity) with detailed formula explanations and a built-in quiz mode for learning.

## Features
- **Unit Conversion:** Convert values between different units for force, pressure, energy, power, torque, and velocity.
- **Formula Explanations:** View the formula and details for each conversion, including SI base units.
- **Unit Prefixes:** Quickly apply metric prefixes (T, G, M, k, m, µ) to input values.
- **Dark Mode:** Toggle between light and dark themes.
- **Print Support:** Print conversion results and explanations in a printer-friendly format.
- **Quiz Mode:** Test your knowledge of unit conversions with interactive quizzes and instant feedback.

## Usage
1. **Select a Unit Category:** Choose from force, pressure, energy, power, torque, or velocity.
2. **Enter a Value:** Input the value you want to convert.
3. **Choose Units:** Select the source and target units.
4. **Apply Prefix (Optional):** Click a prefix button to multiply the input value.
5. **View Result:** The conversion result and formula are displayed instantly.
6. **Copy Result:** Click the copy button to copy the result to your clipboard.
7. **Formula Explanation:** Expand the formula section for detailed explanations.
8. **Print:** Click the print button for a printer-friendly version.
9. **Quiz Mode:** Switch to quiz mode to answer questions and track your score.

## Technologies Used
- **HTML5 & CSS3** (with Tailwind CSS for styling)
- **JavaScript** (vanilla, no frameworks)
- **FontAwesome** (for icons)

## File Structure
- `index.html` — Main application file (contains all HTML, CSS, and JavaScript)
- `old.html` — (Optional) Backup or previous version of the app

## Accessibility & Responsiveness
- Fully responsive layout for desktop and mobile
- Keyboard accessible controls
- ARIA labels and semantic HTML for improved accessibility

## Customization
- To add more unit categories or units, edit the `unitData` object in the JavaScript section.
- To add more quiz questions, edit the `quizQuestions` object.

## License
This project is open source and free to use for educational and personal purposes.

---
For questions or contributions, please contact the project maintainer.
