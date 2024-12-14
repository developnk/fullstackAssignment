# Interactive Webpage Implementation

## Project Overview
This project implements an interactive webpage as per the task requirements. It includes three interactive boxes, each dynamically expanding upon user interaction. The design closely follows the Figma prototype and the functionality demonstrated in the example video.

### Live Demo:
Access the live webpage: [zenithvista.in](http://webpage.zenithvista.in)

### Repository:
View the source code on GitHub: [GitHub Repository Link](https://github.com/developnk/fullstackAssignment.git)

---

## Features
1. **Interactive Boxes**:
   - Three boxes (top, middle, and bottom) that expand dynamically when clicked.
   - Each box displays options for colors and sizes when expanded.

2. **Pixel-Perfect Design**:
   - Matches the Figma design precisely.
   - Respects spacing, alignment, and proportions.

3. **Responsive Design**:
   - Works seamlessly across different screen sizes and resolutions.

4. **Built From Scratch**:
   - No libraries or frameworks used for HTML, CSS, or JavaScript.
   - Fully handcrafted implementation.

5. **CI/CD Pipeline**:
   - Includes a continuous integration and deployment pipeline.
   - Deployed on a Linux Apache server for hosting.

---

## Technical Details

### Tools & Technologies
- **HTML**: Semantic tags for structured and accessible markup.
- **CSS**: Custom styling, responsive media queries.
- **JavaScript**: Vanilla JavaScript for interactivity.
- **CI/CD Pipeline**: Automated testing, build, and deployment pipeline.
- **Linux Apache Server**: Hosting environment.

### File Structure
```
interactive-webpage/
├── index.html       # Main HTML file
├── styles.css       # Custom CSS for styling
├── README.md        # Documentation
├── .github/         # GitHub Actions for CI/CD
```

### Key Functionalities
#### 1. Box Expansion
- Boxes expand and collapse using `transition` properties in CSS and JavaScript `click` event listeners.

#### 2. Dynamic Options
- Upon expansion, boxes reveal additional UI elements to select colors and sizes.

#### 3. Responsive Design
- Media queries ensure the layout adapts to different screen sizes.

#### 4. CI/CD Pipeline
- Configured using GitHub Actions:
  - Runs tests on code push.
  - Automatically deploys to the Linux Apache server on passing tests.

### Hosting Details
- **Domain**: `http://webpage.zenithvista.in`
- **Server**: Linux Apache Server

---

## Task Report
### Implementation Steps
1. **Planning**:
   - Analyzed the Figma design and video example.
   - Identified the key components and functionality.

2. **Development**:
   - Structured the HTML with semantic tags.
   - Styled the boxes and layout using CSS, ensuring responsiveness.
   - Implemented interactivity with vanilla JavaScript.

3. **Testing**:
   - Verified functionality across browsers and screen sizes.
   - Debugged edge cases for the interactive elements.

4. **Deployment**:
   - Configured a CI/CD pipeline with GitHub Actions.
   - Set up hosting on a Linux Apache server.

### Challenges
- **Pixel-Perfect Alignment**: Ensured the design matches Figma by iterating through fine-tuning.
- **Responsive Behavior**: Adjusted breakpoints and layout to maintain usability on smaller screens.
- **Server Deployment**: Configured Apache settings for optimal performance and security.

---

## How to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/developnk/fullstackAssignment.git
   ```
2. Navigate to the project directory:
   ```bash
   cd interactive-webpage
   ```
3. Open `index.html` in a browser:
   ```bash
   open index.html
   ```

---

## CI/CD Pipeline Details
1. **Pipeline Configuration**:
   - Defined in `.github/workflows/deploy.yml`.
   - Includes build, test, and deploy steps.

2. **Deployment Script**:
   - Uses `deploy.sh` to sync files to the Linux Apache server via SSH.

3. **Triggers**:
   - Runs automatically on `git push` to the `main` branch.

---

## Future Enhancements
1. Add animations for smoother transitions.
2. Improve accessibility for screen readers.
3. Include unit tests for JavaScript functionality.

---

## Author
**Your Name**

Feel free to reach out for any queries regarding this project!
