# Deployment Instructions

Since this is a simple static HTML site (`index.html`), you have several easy options to deploy it for free.

## Option 1: Netlify Drop (Easiest)
1.  Go to [app.netlify.com/drop](https://app.netlify.com/drop).
2.  Open your Finder to the folder:
    `/Users/barad/.gemini/antigravity/scratch/intent91-landing`
3.  Drag and drop the `intent91-landing` folder onto the Netlify page.
4.  It will deploy instantly and give you a public URL.

## Option 2: GitHub Pages (Recommended for long term)
1.  Initialize a git repository:
    ```bash
    cd intent91-landing
    git init
    git add .
    git commit -m "Initial commit"
    ```
2.  Create a new repository on GitHub.
3.  Push your code to GitHub.
4.  Go to Repository Settings -> Pages.
5.  Select `main` branch and `/root` folder, then Save.

## Option 3: Vercel
1.  Install Vercel CLI: `npm i -g vercel`
2.  Run `vercel` in the project directory.
3.  Follow the prompts (defaults are usually fine).
