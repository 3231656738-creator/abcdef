# Find Your Inner Compass — 探索你的人格罗盘

This project is a personality quiz application that helps users discover their inner self through various personality frameworks (MBTI, Big Five, Enneagram, CliftonStrengths).

## Features

-   **Interactive Quiz**: A series of questions to determine your personality traits.
-   **Personalized Letter**: A generated letter based on your quiz results.
-   **Pet Companions**: Interactive cat and dog avatars that accompany you.
-   **Visual Effects**: Dynamic background, particle effects, and elegant typography.
-   **Smart Pet Display Control**: Automatically hides pet companions during the quiz selection phase to ensure a distraction-free environment, and smoothly reappears them on other pages.

## Technologies

-   HTML5
-   Tailwind CSS
-   Vanilla JavaScript
-   SVG Graphics

## How to Run

1.  Open the project directory.
2.  Serve the `index.html` file using a local server (e.g., `python -m http.server`).
3.  Open the browser and navigate to the local server address.

## Recent Updates

-   **Smart Pet Display Control**: Implemented logic to hide pets on the quiz page (`page-quiz`) with a smooth fade transition (`opacity 0.3s ease`).
-   **History Navigation**: Added browser history support (`pushState` / `popstate`) to allow navigating between pages using the browser's Back/Forward buttons, ensuring pet visibility state updates correctly.
-   **Consistency**: Unified user greeting to "亲爱的" (Dear) across all interfaces.
