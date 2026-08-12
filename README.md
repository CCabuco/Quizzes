# Quizzes

A static quiz app for game design review.

## Pages

- `index.html` - mobile-friendly home page and navigation hub
- `All Modules Game.html` - full module review quiz with MCQ/FITB modes
- `game_design_quiz_70.html` - focused game design quiz with MCQ/FITB modes
- `game_design_fitb_quiz.html` - legacy standalone fill-in-the-blank page, no longer linked from the home page
- `app.css` - shared layout, navigation, and theme styles

Each main quiz page includes previous/next navigation, a horizontally scrollable question picker, and a mode toggle. Switching between MCQ and FITB keeps the current question number.

## Deploying To Vercel

1. Push these files to the repository.
2. Import the repository in Vercel.
3. Use the default static site settings. No build command is needed.
4. Keep the output directory setting empty.

Vercel will serve `index.html` as the home page.
