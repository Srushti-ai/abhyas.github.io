# About GitHub Pages

1. GitHub Pages is a free hosting service offerred by GitHub that allows you to publish websites directly from your GitHub repositories.
2. GitHub Pages can only serve static content like HTML, CSS and client side JavaScript. It doesn't support server-side scripting like PHP or databases. So its best suited for static sites.
3. Jekyll Integration - GitHub Pages also integrates with Jekyll, a static site generator. Jekyll allows you to easily create blogs and other types of dynamic content without needing a backend.
4. Once you push your code to GitHub, the website is automatically built and made available at a specific URL.
5. GitHub Pages offers two types of sites
   - User (or Organization) Site
   - Project Site
6. User or Organization Site
   - A user site is meant to be a personal portfolio or main homepage for your GitHub Profile.
   - The repository **must** be named `<your-username>.github.io` . E.g. `Srushti-ai.github.io`
   - The URL will be `https://<your-username>.github.io/`. E.g `https://srushti-ai.github.io/`
   - Only **one** user site per GitHub account
   - The **index.html** file must be in the root of the repository
   - Use Case - Personal Website, Blog, Portfolio
7. Project Site
   - A Project Site is linked to a specific project or repository
   - The repository can have **any** name (except `<username>.github.io`)
   - The URL will be `https://<your-username>.github.io/<repo-name>/` (E.g. `https://srushti-ai.github.io/github-pages/`)
   - You can have **multiple** project sites.
   - The **index.html** file must be in the root of the repository.
   - Use Case - Hosting Documentation, apps, or project-specific sites.

# Steps to create your first website.

1. Create a new repository
2. Create a new file - "index.html"
3. Add your code (HTML / CSS)
4. Commit using a proper commit message "Create index.html"
5. You will have to enable GitHub Pages for this repository. Within your repo, go to Settings - GitHub Pages. Under Source, make sure that your repo is linked to your web page.
   If you see **None**, then select the **main** branch.
7. You can view your website a few minutes after each commit
