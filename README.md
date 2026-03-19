# Karishma Yadav - Personal Portfolio

This is the source code for my personal portfolio, built using HTML, CSS, and modern web design principles.

## How to push this project to GitHub

Follow these steps in your terminal (Command Prompt, PowerShell, or Git Bash):

1. **Navigate to your project folder:**
   ```bash
   cd c:\Users\hp\OneDrive\Desktop\2Factor
   ```

2. **Initialize a local Git repository:**
   ```bash
   git init
   ```

3. **Add all your files to the staging area:**
   ```bash
   git add .
   ```

4. **Commit your files:**
   ```bash
   git commit -m "Initial portfolio commit"
   ```

5. **Create a new repository on GitHub:**
   - Go to [GitHub.com](https://github.com/) and log in.
   - Click the **+** icon in the top right and select **New repository**.
   - Name it `portfolio` (or `karishma108.github.io` if you want it as your primary GitHub page).
   - Leave it public and **do not** check "Add a README file". Click **Create repository**.

6. **Link and Push:**
   Copy the URL of your new repository and run the following commands (replace the URL with your actual repository URL):
   ```bash
   git remote add origin https://github.com/karishma108/portfolio.git
   git branch -M main
   git push -u origin main
   ```

## How to Host it for Free (GitHub Pages)

1. Go to your repository on GitHub.
2. Click on **Settings** (the gear icon).
3. On the left sidebar, click on **Pages**.
4. Under "Build and deployment" -> "Branch", select **main** (or master) and click **Save**.
5. Wait a few minutes, and GitHub will provide you with a live link to your deployed portfolio!

## How to Deploy to Vercel

Since you are connecting through GitHub, deploying to Vercel is straightforward:

1. **Push your code to GitHub** (follow the Git push instructions above).
2. Go to **[Vercel.com](https://vercel.com/)** and sign up or log in using your GitHub account.
3. Click on the **Add New...** dropdown on your dashboard and select **Project**.
4. Under the "Import Git Repository" section, find your portfolio repository and click **Import**.
5. On the "Configure Project" screen, Vercel will automatically detect that it is a static HTML/CSS site. Leave the "Framework Preset" as "Other" and do not change the build commands.
6. Click the **Deploy** button.
7. Wait a few seconds for the deployment to complete. Vercel will provide you with a live URL (e.g., `your-project-name.vercel.app`) that you can share!

## How to push changes (Updates) to GitHub

Whenever you modify your files and want to update your GitHub repository (which will also auto-update Vercel), run these commands in your terminal:

1. **Stage all your changes:**
   ```bash
   git add .
   ```

2. **Commit your changes with a message:**
   ```bash
   git commit -m "Updated portfolio content and UI"
   ```

3. **Push the changes to GitHub:**
   ```bash
   git push
   ```
