# UI/UX Design Fundamentals

Static site. No build step.

- index.html: the whole app
- data/curriculum.json: lessons and tasks (edit this to change content)
- data/quiz.json: module quizzes and final exam (answer is the 0-based index of the correct option)

## Deploy to Vercel
1. Unzip, then in this folder run: npx vercel --prod
   (or drag the folder into vercel.com/new, or push it to GitHub and import the repo)
2. Framework preset: Other. Leave build command and output directory empty.

The site loads the JSON with fetch, so test locally with: npx serve .
Opening index.html directly from disk will not work.
