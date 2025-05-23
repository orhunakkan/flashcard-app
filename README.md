# Flashcard Study App

A simple, single-file flashcard app designed for mobile studying during commutes. Built with HTML, CSS, and vanilla JavaScript.

## Features

- Dark mode design with optimal contrast for readability
- Fira Code Medium font for clear text display
- Touch-friendly interface for mobile use
- Mouse click support for desktop use
- Shows random questions and answers
- Minimalist design with no dependencies

## How to Use

1. Open the app in a browser (works well on mobile devices)
2. A random question will be displayed immediately
3. Tap anywhere on the screen (or click with a mouse) to see the answer
4. Tap/click again to see another random question
5. Continue this cycle to study your flashcards

## Customizing Flashcards

To add your own study content, edit the `flashcards` array in the JavaScript section of the `index.html` file:

```javascript
const flashcards = [
    { 
        question: "Your question here", 
        answer: "Your answer here" 
    },
    // Add more question/answer pairs as needed
];
```

## GitHub Pages Deployment

To deploy this app to GitHub Pages:

1. Create a GitHub repository
2. Upload the `index.html` file to the repository
3. Go to repository Settings > Pages
4. Select the branch containing your code (usually `main`)
5. Save the settings and wait for deployment to complete
6. Access your app at `https://[your-username].github.io/[repository-name]/`

The simplicity of this single-file app makes it perfect for GitHub Pages hosting and quick updates.
