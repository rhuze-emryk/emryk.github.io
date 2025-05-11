## Website Improvement Plan with Jekyll

**Goal:** Enhance the website by adding a logo, adapting the color scheme to complement the logo (orange and blue), and using Markdown for content management.

**Approach:** Migrate the existing HTML/CSS website to Jekyll, a static site generator.

**Why Jekyll?**

*   **Markdown Support:** Enables writing content in Markdown for easier content creation and editing.
*   **Themes:** Offers a wide range of pre-built themes for a professional and customizable design.
*   **Customization:** Themes can be adapted to integrate the logo and desired color scheme.
*   **GitHub Pages Compatibility:** Simplifies deployment on GitHub Pages.
*   **Ad-Free Websites:** Static site generators naturally create ad-free sites.

**Steps:**

1.  **Set up Jekyll:**
    *   Initialize a Jekyll project in the repository.
    *   Add a `Gemfile` to manage dependencies.
    *   Configure basic Jekyll project structure.

2.  **Choose a Jekyll Theme:**
    *   Explore minimalist, clean, and professional Jekyll themes.
    *   Prioritize themes that are customizable for color and logo integration.
    *   Examples: Minimalist blog themes, portfolio themes, documentation themes.
    *   Resources: [jekyllthemes.io](https://jekyllthemes.io/), GitHub.

3.  **Integrate Logo:**
    *   Add the logo to the navigation bar within the chosen theme.
    *   Modify theme layout files to include an `<img>` tag in the navigation section.

4.  **Adapt Color Scheme:**
    *   Customize the theme's CSS to incorporate the logo's orange and blue colors.
    *   Use blue for primary elements (background, navigation) for a calming feel.
    *   Use orange as an accent color for interactive elements or highlights for intrigue.

5.  **Migrate Content to Markdown:**
    *   Convert content from `index.html` to Markdown files.
    *   Structure content in a single Markdown file or split into sections based on theme requirements.
    *   Utilize Jekyll's `_posts` directory for blog content (if needed) and regular Markdown files for pages.

6.  **Test and Refine:**
    *   Test the Jekyll site locally to ensure proper functionality and visual appeal.
    *   Refine design and content as needed based on testing and user feedback.

**Next Steps After Plan Approval:**

*   Proceed with setting up Jekyll and selecting a theme.
*   Begin implementing the steps outlined above in "Code" mode.