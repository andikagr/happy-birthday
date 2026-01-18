# Happy Birthday Animation Project

A beautiful and interactive birthday greeting website featuring smooth animations, background music, and a personalized experience. Perfect for sending a special digital surprise to your friends or loved ones!

## Features

-   **Interactive Entrance**: Starts with a polite prompt asking the user if they want to play background music.
-   **Stunning Animations**: Powered by [GSAP (GreenSock Animation Platform)](https://greensock.com/gsap/), featuring smooth transitions, text effects, and floating elements.
-   **Background Music**: Plays a celebration song (`birthday.mp3`) to set the mood.
-   **Dynamic Storytelling**: Displays a sequence of heartwarming messages, chat-like bubbles, and "idea" text animations.
-   **Celebratory Elements**: Includes floating balloons, a profile picture display, and fireworks/confetti effects.
-   **Responsive Design**: Works well on both desktop and mobile devices.

## Technologies Used

-   **HTML5**: Semantic markup for the page structure.
-   **CSS3**: Custom styles for layout, colors, and responsive design.
-   **JavaScript**: Logic for the animation timeline and user interaction.
-   **GSAP (TimelineMax)**: For handling complex animation sequences.
-   **SweetAlert2**: For the beautiful music prompt popup.

## How to Use & Customize

1.  **Clone the Repository**
    ```bash
    git clone https://github.com/yourusername/happy-birthday.git
    cd happy-birthday
    ```

2.  **Personalize the Content**
    Open `index.html` in your text editor and modify the following sections to fit your needs:

    -   **Name**: Change the text inside `<span id="name">...</span>` (Line 28).
    -   **Greeting**: Update `<p id="greetingText">...</p>` (Line 30).
    -   **Chat Message**: Edit the text inside `.hbd-chatbox` (Line 40).
    -   **Profile Picture**: Replace `./img/cewek.jpg` with your own image, or update the `src` attribute in the `<img>` tag (Line 66).

3.  **Change the Music**
    -   Replace the `music/birthday.mp3` file with your preferred song (keep the name `birthday.mp3` or update the path in `index.html` Line 19).

4.  **Run the Project**
    -   Simply open `index.html` in your web browser.
    -   Or use a local server (e.g., VS Code "Live Server" extension) for the best experience.

## Project Structure

```
happy-birthday/
├── img/                # Images (favicon, balloons, profile pic, etc.)
├── music/              # Audio files
├── script/
│   └── main.js         # Main logic and GSAP animation timeline
├── style/
│   └── main.css        # Stylesheet
├── index.html          # Main HTML file
└── README.md           # Project documentation
```

## Credits

-   **Animations**: Built with [GSAP](https://greensock.com/).
-   **Alerts**: Styled with [SweetAlert2](https://sweetalert2.github.io/).
-   **Fonts**: [Google Fonts (Poppins)](https://fonts.google.com/).

---

Made with ❤️ for a special someone.
