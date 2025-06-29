# DPblast! by DECS

<p align="center">
  <img src="dpblast_logo.png" alt="DPblast! by DECS" width="400"/>
</p>

<p align="center">
  A dynamic, client-side web application for students of the DECS department at Laguna College of Business and Arts to create a custom profile picture for the Academic Year 2025-2026 kickoff event.
</p>

<p align="center">
  <a href="https://comsci-decs.github.io/DPblaster/"><strong>View Live Demo »</strong></a>
</p>

---

## 📸 Screenshot

<p align="center">
  <img src="https://i.imgur.com/eba989b8-dd0a-49da-a446-64642c87e5a1.jpg" alt="Application Screenshot" width="300"/>
</p>

---

## ✨ Features

This project is built with vanilla HTML, CSS, and JavaScript, leveraging Tailwind CSS for rapid UI development. It's a single-page application with no backend dependencies, making it perfect for free hosting on GitHub Pages.

- **Dynamic Sticky Header**: A sleek, "glassmorphism" header that shrinks on scroll for a modern user experience.
- **Frame Selection**: Users can choose between two custom frames (CpE or CS).
- **Dynamic Caption Generation**: Automatically generates a detailed, pre-formatted caption based on user's name and section.
- **Image Upload & Preview**: Allows users to upload a photo from their device and see a live preview.
- **Center & Crop**: Automatically centers and crops non-square images to perfectly fit the 1:1 aspect ratio without stretching or distortion.
- **Client-Side Image Processing**: Merges the uploaded image and the selected frame using the HTML Canvas API.
- **One-Click Download**: Users can download the final framed picture as a `dpblast_profile.png` file.
- **Copy-to-Clipboard**: Easily copy the generated caption with a single button click.
- **Local Visitor Counter**: A simple widget in the footer that tracks page visits on a per-user basis using browser local storage.
- **Fully Responsive**: Designed to work seamlessly on mobile, tablet, and desktop devices.
- **Themed UI**: A modern, dark, "techy" theme with a red, orange, and white color palette.

---

## 🚀 How to Use

Creating your custom profile picture is simple. Follow these steps on the website:

1.  **Enter Your Name**: Type your full name into the first input field.
2.  **Select Your Section**: Choose your correct section from the dropdown menu. This will automatically determine your course for the caption.
3.  **Choose Your Frame**: Click on either the "CPE Frame" or "CS Frame" to select the design for your course.
4.  **Upload Your Picture**: Click the "Upload Your Picture" button and select a photo from your device.
5.  **Preview**: A live preview of your final image will appear.
6.  **Download Image**: Once you are happy with the result, click the "Download Image" button.
7.  **Copy Caption**: Click the "Copy Caption" button to copy the official caption to your clipboard, ready to be pasted on social media.

---

## 🛠️ Setup for GitHub Pages

To deploy this project on your own GitHub Pages for free:

1.  **Create a New Repository**: Go to your GitHub account and create a new public repository.
2.  **Upload Files**: Upload all the files listed in the [File Structure](#-file-structure) section to the root of your new repository.
3.  **Enable GitHub Pages**:
    - Go to your repository's **Settings** tab.
    - In the left sidebar, click on **Pages**.
    - Under "Build and deployment", select the **Source** as "Deploy from a branch".
    - Select the branch `main` (or `master`) and the folder `/root`. Click **Save**.
4.  **Done!** Your site will be live in a few minutes at `https://<your-github-username>.github.io/<your-repository-name>/`.

---

## 💻 Technologies Used

-   **HTML5**: For the core structure of the page.
-   **CSS3**: For custom styling and animations.
-   **Tailwind CSS**: A utility-first CSS framework for rapid UI development.
-   **JavaScript (ES6+)**: For all the application logic, including DOM manipulation, canvas image processing, and event handling.

---

## 👨‍💻 Credits

This project was designed and produced by:
-   **Ickoh Gecolea** (PRO-CpE)
-   **Michael Ordenes** (PRO-CS)

---

## 🌐 Follow Us

Stay updated with the latest from our student organizations on Facebook:

-   <a href="https://www.facebook.com/acoeslcba">**Association of Computer Engineering Students (ACOES)**</a>
-   <a href="https://www.facebook.com/ccsslcba">**Council of Computer Science Students (CCSS)**</a>

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for details.
