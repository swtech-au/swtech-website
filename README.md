# Capes Technology Services Website

This is the source code for the Capes Technology Services website, built with Jekyll and designed for hosting on GitHub Pages.

## How to use this repository

1.  **Refine Content:**
    *   Edit `index.md` to update the landing page.
    *   Edit `services.md` to add more specific details about your offerings.
    *   Edit `about.md` to add your personal background or team details.
    *   Update `_config.yml` with your actual email and (eventually) your social media links.

2.  **Local Development (Optional):**
    If you have Ruby and Jekyll installed:
    ```bash
    bundle install
    bundle exec jekyll serve
    ```

3.  **Publishing to GitHub:**
    *   Create a new repository on GitHub named `swtech-website` (or your preferred name).
    *   Initialize git in this folder:
        ```bash
        git init
        git add .
        git commit -m "Initial scaffold for SWTech website"
        git branch -M main
        git remote add origin https://github.com/[your-username]/[repo-name].git
        git push -u origin main
        ```
    *   Go to your Repository **Settings** > **Pages**.
    *   Under **Build and deployment** > **Source**, select **GitHub Actions**. Jekyll will automatically build and deploy your site.

## Directory Structure
*   `_config.yml`: Main configuration settings.
*   `index.md`: Home page.
*   `services.md`: Services page.
*   `about.md`: About page.
*   `contact.md`: Contact page.
*   `Gemfile`: Dependency management for GitHub Pages.
