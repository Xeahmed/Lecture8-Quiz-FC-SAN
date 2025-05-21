# FC-SAN Quiz Webpage

## Overview

This project is an interactive quiz webpage designed to test knowledge on Fibre Channel Storage Area Networks (FC-SAN), based on Lecture 8 content. The quiz consists of 20 multiple-choice questions (MCQs) and 13 true/false questions, covering key FC-SAN concepts such as protocols, topologies, addressing, layering, zoning, and data transfer mechanisms. The webpage is developed to be user-friendly, responsive, and bilingual, with questions in English and explanations in Arabic to cater to a diverse audience. It includes a progress bar, immediate feedback on answers, and a final score display.

The project was created by Eng. XE Ahmed Refat, an EELU student from the Sohag branch, as an educational tool to reinforce understanding of FC-SAN concepts.

## Features

- **Interactive Quiz**: 20 MCQs and 13 true/false questions with immediate feedback and detailed explanations in Arabic.
- **Bilingual Support**: Questions in English with technical terms highlighted, and explanations in Arabic for accessibility.
- **Responsive Design**: Optimized for both desktop and mobile devices using media queries and flexible layouts.
- **Progress Tracking**: A dynamic progress bar updates as users advance through the quiz.
- **Score Calculation**: Displays the final score and percentage upon quiz completion, with an option to restart.
- **Modern UI/UX**:
  - Clean design with a dark mode-compatible color scheme.
  - Hover effects and animations for a polished user experience.
  - Use of the `Tajawal` font for Arabic text readability.
- **Navigation**: Sticky header with links to Home, Quiz, and Contact sections.
- **Accessibility**: Proper text directionality (`dir="ltr"` for English, `dir="rtl"` for Arabic) and semantic HTML.

## Technologies Used

- **HTML5**: For structuring the webpage content and quiz form.
- **CSS3**: For styling, including Flexbox for layout, animations, and responsive design.
- **JavaScript**: For quiz logic, handling user interactions, progress updates, and score calculations.
- **Google Fonts**: `Tajawal` font for Arabic text and fallback to `Arial` for English.
- **External Resources**: Background image from Unsplash for the hero section.

## Setup Instructions

To run the quiz webpage locally or deploy it, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/your-username/fc-san-quiz.git
   cd fc-san-quiz
   ```

2. **Open the Webpage**:

   - No server is required since the project uses static HTML, CSS, and JavaScript.
   - Open `index.html` in a modern web browser (e.g., Chrome, Firefox, Edge) by double-clicking the file or using a local server.

3. **Optional: Run with a Local Server**: To avoid CORS issues with external resources (e.g., Unsplash images or Google Fonts), use a local server:

   ```bash
   python -m http.server 8000
   ```

   Then, access the webpage at `http://localhost:8000`.

4. **Dependencies**:

   - No external libraries or frameworks are required.
   - Ensure an internet connection for loading Google Fonts and the Unsplash background image.

## Usage

1. Open the webpage in a browser.
2. Navigate to the quiz section using the header navigation or scroll down.
3. Answer each question by selecting an option. The explanation will appear immediately, and the correct/wrong answers will be highlighted.
4. Click the "Next" button to proceed to the next question (enabled after selecting an answer).
5. After completing all 33 questions, view your score and percentage.
6. Click "Restart Quiz" to try again.

## Project Structure

```
fc-san-quiz/
├── index.html       # Main webpage with quiz content
├── README.md        # Project documentation
```

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request with a detailed description of your changes.

Please ensure your code follows the existing style and includes appropriate comments.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For questions or feedback, contact:

- **Eng. XE Ahmed Refat**
- **Email**: ahmed.refat@example.com
- **GitHub**: your-username

---

© 2025 XE Ahmed | Cloud Quiz. Developed by Eng. XE Ahmed Refat, EELU Student, Sohag Branch.
