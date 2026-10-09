# Task 6: Host a Static Website with GitHub Pages

## Project Overview

This project demonstrates how to create and publish a static website using **HTML, CSS, Git, GitHub, and GitHub Pages**. It was completed as part of the DevOps Internship Task 6.

GitHub Pages hosts static website files directly from a GitHub repository, making it possible to publish a simple website without managing a web server.

## Objectives

- Create a static website using HTML and CSS.
- Track and manage the source code with Git.
- Push the project to a GitHub repository.
- Configure GitHub Pages to publish the website.
- Verify the deployed website using its public URL.

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Defines the structure and content of the webpage. |
| CSS3 | Styles the website, including colors, spacing, cards, and responsive layout. |
| Git | Tracks source-code changes and records commits. |
| GitHub | Stores the repository remotely. |
| GitHub Pages | Publishes the static website online. |

## Project Structure

```text
task-6-github-pages/
├── index.html
├── README.md
└── css/
    └── style.css
```

- **`index.html`** — the main webpage and default entry point.
- **`css/style.css`** — styles the page and adjusts its layout for smaller screens.
- **`README.md`** — project overview, deployment steps, and screenshot documentation.

## Website Features

- Welcome/hero section.
- Navigation link to the About section.
- Project description and technology cards.
- Custom dark-blue gradient styling.
- Responsive card layout for different screen sizes.
- Smooth scrolling between sections.

## How It Works

1. The browser loads `index.html`.
2. The HTML file links to `css/style.css` to apply the design.
3. Git records the source files in commits.
4. GitHub stores the repository.
5. GitHub Pages publishes the static files from the selected branch and folder.

## Deployment Steps

### 1. Create the website

Create `index.html` and `css/style.css`. Open `index.html` in a browser and confirm that the content and styling appear correctly.

### 2. Initialize Git and commit the files

```bash
git init
git add index.html css/style.css README.md
git commit -m "Create static website for Task 6"
git branch -M main
```

### 3. Create a GitHub repository

Create a repository named `task-6-github-pages`.

### 4. Push the project

```bash
 git remote add origin https://github.com/Workwithaditya01/task-6-github-pages.git
push -u origin main
```

### 5. Enable GitHub Pages

In the repository, open **Settings → Pages**. Under **Build and deployment**, select:

- **Source:** Deploy from a branch
- **Branch:** `main`
- **Folder:** `/ (root)`

Click **Save** and wait for the deployment to finish.

![GitHub-Pages](https://github.com/Workwithaditya01/task-6-github-pages/blob/f87e77c1d447251192c15d4b2a24826558712544/Images/github%20Pages.png)

### 6. Verify the deployment

Open the published URL shown in **Settings → Pages**. Confirm that the website loads and that its CSS styling is visible.

```
https://workwithaditya01.github.io/task-6-github-pages/
```

## Screenshots

Add your own screenshots to a folder named `Images/` in the repository. Use these filenames, or update the paths below to match your files.

### 1. GitHub Repository

Shows the repository name and uploaded project files.

![GitHub repository screenshot](https://github.com/Workwithaditya01/task-6-github-pages/blob/f87e77c1d447251192c15d4b2a24826558712544/Images/Github%20Repo.png)

### 2. GitHub Pages Configuration

Shows the Pages deployment configuration and published status or URL.

![GitHub Pages settings screenshot](https://github.com/Workwithaditya01/task-6-github-pages/blob/f87e77c1d447251192c15d4b2a24826558712544/Images/github%20Pages.png)

### 3. Live Website

Shows the published website open in a browser, preferably with the URL visible.

![Live website screenshot](https://github.com/Workwithaditya01/task-6-github-pages/blob/f87e77c1d447251192c15d4b2a24826558712544/Images/Website%20Image.png)

> **Screenshot note:** The image paths above are placeholders. Take real screenshots of your own repository, Pages settings, and live website, then save them in the `Images/` folder using the filenames shown. Do not leave placeholder images in the final submission.

## Updating the Website

After editing any project files, run:

```bash
git add .
git commit -m "Update website content and styling"
git push
```

GitHub Pages will publish the updated version after the deployment completes.

## Limitations

GitHub Pages is intended for static websites. It does not run server-side applications such as Node.js, Python, or PHP. A static website can still communicate with a separately hosted backend API.

## Learning Outcomes

- Practiced writing HTML and CSS.
- Learned basic Git commands and commit workflow.
- Created and pushed a GitHub repository.
- Configured a branch-based GitHub Pages deployment.
- Learned how to verify and update a published static website.

## Project Links

- **GitHub Repository:** `https://github.com/Workwithaditya01/task-6-github-pages`
- **Live Website:** `https://workwithaditya01.github.io/task-6-github-pages/`

Replace `YOUR-USERNAME` with your actual GitHub username and verify both links before submission.

## Interview Questions and Answers

### 1. What is GitHub Pages?

GitHub Pages is a hosting service that publishes static website files from a GitHub repository.

### 2. Can you host dynamic applications on GitHub Pages?

It cannot run server-side code. A static frontend may call an API hosted elsewhere.

### 3. What are the limits of GitHub Pages?

It is designed for static content and has published build, deployment, and site-size limits. Check the official GitHub Pages documentation for current limits.

### 4. How do you update a deployed website?

Edit the source files, commit the changes, and push them to the configured branch. GitHub Pages then deploys the update.

### 5. What happens if the repository is deleted?

The Pages site associated with that repository will no longer be served from that repository.

### 6. What is the default file that loads?

Typically, `index.html` in the configured publishing directory.

### 7. Can you use a custom domain?

Yes. GitHub Pages supports custom domains when the domain and DNS records are configured correctly.

## References

- [GitHub Pages documentation](https://docs.github.com/en/pages)
- [Creating a GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)

---

**Task:** DevOps Internship — Task 6  
**Topic:** Host a Static Website with GitHub Pages
