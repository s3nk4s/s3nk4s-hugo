
---
title: "Creating a Hugo Based Blog"
date: 2025-08-26
image: "/images/hugo-demo-hero.jpg"
description: "A quick demo of setting up a modern Hugo blog with a custom theme."
summary: "In this post, we demonstrate how to set up a Hugo-based blog using a custom theme that leverages Tailwind CSS for a modern look. We configured the theme to display hero images for both the site and individual posts, and set up a grid layout for the front page. Images are organized in the `assets/images` folder for easy management."
---

> Note: this post is mostly copilot generated based on the interation to create the theme and site. which is entirely copilot generated

In this post, we demonstrate how to set up a Hugo-based blog using a custom theme that leverages Tailwind CSS for a modern look. We configured the theme to display hero images for both the site and individual posts, and set up a grid layout for the front page. Images are organized in the `assets/images` folder for easy management.
## Recent Updates

Since this post was first written, we've made several improvements:

- Added a dedicated theme directory and integrated Tailwind CSS for styling.
- Created templates for the homepage, posts list, and individual blog posts.
- Fixed image handling by moving hero images to the `static/images` directory so they display correctly.
- Ensured the "Posts" section and individual blog posts render with hero images and modern layouts.
- Improved the overall structure for easier content and asset management.

Feel free to explore the site and add your own posts and images!

## Update #2

Since the last update, we've made further improvements:

- Switched the theme from Tailwind CSS to Bootstrap for easier styling and responsiveness.
- Added a top navigation bar with Home, Blog, and About links.
- Created dedicated templates for the About and Blog pages so they display correctly.
- Improved the front page to show all blog entries in two columns, with hero images scaled down for a cleaner look.
- Ensured all images are served from the static directory for proper rendering.

The site is now more user-friendly and visually appealing. More features and posts can be added easily!

## Update #3: Modernizing and Customizing the Blog (August 27, 2025)

Today, several improvements were made to the Hugo blog project:

- **Theme Modernization:** The sk-simple theme was created using the simple.css framework for a clean, modern, and uncluttered look.
- **Navigation:** The top menu now features Home, About, and RSS links. The About page was added with a custom template and content.
- **Front Page Layout:** Blog posts on the front page are now displayed in a responsive two-column grid, adapting to screen size for optimal readability.
- **Post Filtering:** Only markdown files within the `posts` folder are shown in the blog listing.
- **Styling:** Custom CSS was added for card-like post styling, subtle shadows, and improved spacing. The layout is now fully responsive.
- **.gitignore:** The repository now ignores build output, cache, editor files, and WSL Zone.Identifier files.

These changes make the blog visually appealing, easy to navigate, and maintain a minimal aesthetic. More updates coming soon!

## References
https://robinvanderknaap.dev/blog/building-robinvanderknaap-dev/

https://gohugo.io/host-and-deploy/host-on-github-pages/
