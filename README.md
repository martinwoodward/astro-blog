# Astro Blog

Welcome to the Astro Blog project! This is a professional, clean, modern, and responsive blog built using Astro. The blog is designed to be published as a static HTML website.

## Project Structure

The project is organized as follows:

```
astro-blog
├── src
│   ├── components          # Reusable components for the blog
│   │   ├── Header.astro    # Header component with blog title and logo
│   │   ├── Footer.astro    # Footer component with copyright and social links
│   │   ├── Navigation.astro # Navigation component for site links
│   │   └── BlogPost.astro  # Component for rendering individual blog posts
│   ├── layouts             # Layouts for different pages
│   │   ├── BaseLayout.astro # Base layout for all pages
│   │   └── BlogLayout.astro # Layout specifically for blog pages
│   ├── pages               # Pages of the blog
│   │   ├── index.astro     # Homepage
│   │   ├── about.astro     # About page
│   │   ├── blog            # Blog section
│   │   │   ├── index.astro # List of all blog posts
│   │   │   └── [slug].astro # Dynamic blog post rendering
│   │   └── posts           # Markdown files for blog posts
│   │       ├── first-post.md
│   │       └── second-post.md
│   ├── styles              # Global styles
│   │   └── global.css      # CSS for consistent styling
│   └── content             # Content configuration
│       └── config.ts       # Blog configuration settings
├── public                  # Public assets
│   └── favicon.svg         # Favicon for the blog
├── astro.config.mjs        # Astro project configuration
├── package.json            # npm configuration and dependencies
├── tsconfig.json           # TypeScript configuration
└── README.md               # Project documentation
```

## Getting Started

To get started with the Astro Blog project, follow these steps:

1. **Clone the repository**:
   ```
   git clone <repository-url>
   cd astro-blog
   ```

2. **Install dependencies**:
   ```
   npm install
   ```

3. **Run the development server**:
   ```
   npm run dev
   ```

4. **Build for production**:
   ```
   npm run build
   ```

5. **Preview the production build**:
   ```
   npm run preview
   ```

## Usage

- Customize the blog by editing the components in the `src/components` directory.
- Add new blog posts by creating Markdown files in the `src/pages/posts` directory.
- Modify global styles in `src/styles/global.css`.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.