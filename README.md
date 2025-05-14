# My Jekyll Site

This is a simple Jekyll website project that serves as a starting point for building your own site. Below are the details of the project structure and how to get started.

## Project Structure

- **_config.yml**: Configuration settings for the Jekyll site, including site title and description.
- **_data/navigation.yml**: Navigation data used for generating menus or links throughout the site.
- **_includes/**: Contains reusable HTML snippets for the header and footer.
  - **footer.html**: HTML for the footer section.
  - **header.html**: HTML for the header section.
- **_layouts/**: Layout files that define the structure of the pages.
  - **default.html**: Default layout for all pages.
  - **page.html**: Layout for standard pages.
  - **post.html**: Layout for blog posts.
- **_posts/**: Contains blog posts in Markdown format.
  - **2023-01-01-welcome-to-jekyll.md**: Sample blog post.
- **_sass/**: Sass stylesheets for the site.
  - **main.scss**: Main Sass file for styles.
- **assets/**: Contains static assets like CSS and JavaScript.
  - **css/styles.scss**: Custom styles in Sass format.
  - **js/main.js**: JavaScript code for interactivity.
- **index.md**: Main landing page of the site in Markdown format.
- **pages/**: Additional pages for the site.
  - **about.md**: About page content.
  - **contact.md**: Contact page content.
- **Gemfile**: Specifies the Ruby gems required for the Jekyll site.

## Getting Started

1. **Install Jekyll**: Make sure you have Ruby and Bundler installed. Then, install Jekyll by running:
   ```
   gem install jekyll bundler
   ```

2. **Install Dependencies**: Navigate to the project directory and run:
   ```
   bundle install
   ```

3. **Run the Site**: Start the Jekyll server with:
   ```
   bundle exec jekyll serve
   ```
   Your site will be available at `http://localhost:4000`.

4. **Customize**: Modify the content in the `_posts`, `pages`, and other directories to personalize your site.

## License

This project is open-source and available under the [MIT License](LICENSE).