# 404 Error Page Template

A simple, clean, and responsive 404 error page template for web applications.

## Overview

This repository contains a minimalist "Page Not Found" error page that can be easily implemented in any web project. The design features a clean, monochromatic aesthetic with proper responsive layout.

## Features

- Clean, minimalist design
- Fully responsive layout
- Lightweight (no external dependencies)
- Easy to customize
- Cross-browser compatible

## Preview

When a user navigates to a non-existent page on your website, they will see:
- A large "Error 404" heading
- "Page Not Found" message
- A link to return to the homepage

## Implementation

Simply add the `index.html` file to your project and configure your server to display this page when a 404 error occurs.

### Server Configuration Examples

#### Apache
Add to .htaccess:
```
ErrorDocument 404 /index.html
```

#### Nginx
Add to your server block:
```
error_page 404 /index.html;
```

## Customization

You can easily customize the page by modifying the CSS within the `<style>` tag. Some customization options include:
- Changing colors (currently using light background with gray text)
- Modifying font sizes or families
- Adding additional content or branding elements

## License

Feel free to use and modify this template for your projects.

## Contact

If you have any questions or suggestions for improvement, please open an issue in this repository.
