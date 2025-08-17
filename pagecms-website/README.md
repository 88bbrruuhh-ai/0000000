# Pages CMS Website

A simple, responsive website built with Pages CMS for easy content management.

## Features

- **Easy Content Management**: Edit content through Pages CMS interface
- **Responsive Design**: Works on all devices
- **Blog System**: Manage blog posts with rich content
- **Media Management**: Upload and organize images
- **Flexible Configuration**: Customize content types and fields

## Structure

```
pagecms-website/
├── .pages.yml              # Pages CMS configuration
├── index.html              # Main website file
├── src/
│   ├── _data/
│   │   ├── homepage.json   # Homepage content
│   │   └── site.json       # Site settings
│   └── posts/              # Blog posts
│       ├── 2025-01-17-getting-started.md
│       └── 2025-01-16-why-choose-pagecms.md
└── media/                  # Media files (images, etc.)
```

## Configuration

The `.pages.yml` file configures Pages CMS with:

- **Homepage Content**: Title, subtitle, about section, and features
- **Blog Posts**: Collection of markdown posts with metadata
- **Site Settings**: Global site configuration and social links
- **Media Management**: Image and file upload configuration

## Content Types

### 1. Homepage (`src/_data/homepage.json`)
- Page title and subtitle
- Hero image
- About section with rich text
- Features list with icons and descriptions

### 2. Blog Posts (`src/posts/`)
- Title, date, and publication status
- Excerpt and featured image
- Tags for categorization
- Rich text content body

### 3. Site Settings (`src/_data/site.json`)
- Site name and description
- Logo and URL configuration
- Social media links

## Getting Started

1. **Setup Pages CMS**: Connect your repository to Pages CMS
2. **Edit Content**: Use the CMS interface to modify content
3. **Add Posts**: Create new blog posts through the CMS
4. **Upload Media**: Add images and files via the media manager
5. **Customize**: Modify the configuration to add new fields

## Pages CMS Features Used

- **Rich Text Editor**: For formatted content
- **Image Fields**: For logos, featured images, and media
- **Object Fields**: For structured data like features and social links
- **List Fields**: For multiple items (features, social links, tags)
- **Select Fields**: For predefined options with custom values
- **Boolean Fields**: For published status and settings
- **Date Fields**: For post scheduling
- **Pattern Validation**: For URLs and other formatted inputs

## Customization

The website is fully customizable through the Pages CMS interface:

- Edit homepage content without touching code
- Add new blog posts with rich formatting
- Update site settings and social links
- Upload and manage media files
- Configure SEO metadata

## Development

The website uses:
- Pure HTML, CSS, and JavaScript
- Responsive CSS Grid and Flexbox
- Font Awesome icons
- Google Fonts (Inter)
- Fetch API for loading JSON content

## Browser Support

Works in all modern browsers that support:
- CSS Grid
- Flexbox
- Fetch API
- ES6+ JavaScript features
