# Resume Builder

A lightweight, powerful single-page web application for creating professional resumes. Built with HTML, CSS (Bootstrap 5), and Vanilla JavaScript, this tool allows users to input their details, choose from multiple templates, customize themes, and export their resume as a PDF—all client-side with no server data storage.

## Features

* **Real-time Preview:** See changes instantly as you type in the split-screen editor.
* **5 Professional Templates:**
    * **Modern:** Clean sidebar layout with customizable accents.
    * **Classic:** Traditional serif font layout, perfect for formal applications.
    * **Minimal:** A clean, ATS-friendly design focusing on readability.
    * **Creative:** A timeline-based layout with a bold header design.
    * **Modern Color:** A vibrant two-column layout with background tints.
* **Theme Customization:** Integrated color picker allows you to change the primary theme color for any template (affecting headers, icons, and borders without compromising text readability).
* **Smart Image Handling:** Upload profile photos with automatic client-side compression to prevent storage issues.
* **Dynamic Sections:**
    * **Experience Toggle:** A dedicated checkbox to hide the "Experience" section entirely (ideal for freshers).
    * **QR Code Generator:** Automatically generates a QR code linking to your portfolio or LinkedIn.
    * **Declaration:** Add a customizable declaration statement at the bottom.
* **Manage Content:** Easily add, remove, or reorder entries for Education, Projects, Achievements, Certifications, Skills, and Languages.
* **Privacy First:** 100% client-side architecture. Your data is saved to your browser's LocalStorage and is never uploaded to a server.
* **PDF Export:** Built-in "Save as PDF" functionality optimized for A4 paper size.

## Technologies Used

* **HTML5**
* **CSS3** (Bootstrap 5 & Custom CSS Variables)
* **JavaScript** (Vanilla ES6+)
* **Font Awesome** (Icons)
* **Google Fonts** (Inter, Merriweather, Montserrat)

## Installation & Usage

Since this is a static web application, no backend installation or build process is required.

### Local Use
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/shubhambelbase/Resume_builder.git](https://github.com/shubhambelbase/Resume_builder.git)
    
    ```
2.  **Navigate to the project folder:**
    ```bash
    cd resume-builder
    ```
3.  **Run the App:**
    Simply double-click the `index.html` file to open it in your default web browser.

### Hosting
You can easily host this application for free on **GitHub Pages**, **Netlify**, or **Vercel** by simply uploading the `index.html` file.

## How to Use

1.  **Enter Your Data:** Use the editor panel on the left to fill in your Personal Details, Summary, Education, etc.
2.  **Upload Photo:** (Optional) Click "Choose File" to upload a profile picture. It will automatically resize and appear on compatible templates.
3.  **Customize Design:**
    * Select a **Template** from the dropdown menu.
    * Use the **Color Picker** to change the theme color.
    * Check/Uncheck "Show Experience" depending on your career level.
4.  **Save/Export:**
    * Your progress is auto-saved to your browser.
    * Click **"Save as PDF"** to generate the final document.
    * *Tip: In the print dialog, ensure "Background Graphics" is enabled for the colors to appear correctly.*

## Contributing

Contributions are welcome! If you have ideas for new templates or features, feel free to open an issue or submit a pull request.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/NewTemplate`)
3.  Commit your Changes (`git commit -m 'Add a new Minimalist template'`)
4.  Push to the Branch (`git push origin feature/NewTemplate`)
5.  Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

