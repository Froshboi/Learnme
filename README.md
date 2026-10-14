# Learnme — UI/UX Design Studio

An approachable, five-week UI/UX course with short lessons, interactive design challenges, accessible color and layout labs, practice quizzes, and a scored final exam. Progress, personal-best quiz scores, theme preference, and the usability test-plan draft are saved in the learner's browser.

## Course content

- `index.html`: responsive course dashboard, lessons, interactive workspaces, quizzes, scoring, and the hands-on studio
- `data/curriculum.json`: five modules, lesson examples, and design tasks
- `data/quiz.json`: module practice questions and the cumulative final exam (each answer is the 0-based index of the correct option)
- `vercel.json`: static-site deployment configuration

The course includes 30 practice questions, an 18-question cumulative exam, and ten studio challenges. Week 5 adds accessibility foundations, inclusive usability testing, practical measures, and a score-based test-plan workbench.

## Deploy to Vercel

1. Import this repository in Vercel or run `npx vercel --prod` from this folder.
2. Use the **Other** framework preset with no build command or output directory.

Run locally with `npx serve .` (or another static HTTP server). The site fetches its course data, so opening `index.html` directly from disk will not work.
