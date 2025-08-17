# Pages CMS Setup Instructions

## What is Pages CMS?

Pages CMS is an open-source Content Management System for static websites that enables you to edit content directly through a user-friendly interface. It integrates with GitHub and works with static site generators.

## How to Use This Website with Pages CMS

### Step 1: Setup Your Repository

1. **Create a GitHub Repository**
   - Upload this website code to a new GitHub repository
   - Make sure all files are in the root directory of your repository

2. **Enable GitHub Pages** (Optional)
   - Go to your repository settings
   - Enable GitHub Pages to host your website
   - Your website will be available at `https://yourusername.github.io/repository-name`

### Step 2: Access Pages CMS

1. **Visit Pages CMS**
   - Go to [https://pagescms.org](https://pagescms.org)
   - Sign in with your GitHub account

2. **Connect Your Repository**
   - Select your repository from the list
   - Pages CMS will detect the `.pages.yml` configuration file

### Step 3: Start Editing

Once connected, you can edit your website content through the Pages CMS interface:

#### Homepage Content
- **Homepage Settings**: Edit title, subtitle, and hero image
- **About Section**: Update the about title and content using the rich text editor
- **Features**: Add, edit, or remove feature cards with icons and descriptions

#### Blog Posts
- **Create New Posts**: Click "New Post" to create blog articles
- **Edit Existing Posts**: Modify titles, content, tags, and publication status
- **Media**: Upload featured images for your posts

#### Site Settings
- **General Settings**: Update site name, description, and URL
- **Social Media**: Add or modify social media links
- **Logo**: Upload and set your site logo

### Step 4: Content Management Features

#### Rich Text Editor
- Format text with bold, italic, headings
- Add links and lists
- Insert images directly into content

#### Media Management
- Upload images and files
- Organize media in folders
- Reference media in your content

#### Advanced Features
- **Tags**: Categorize blog posts with tags
- **Publishing**: Control which posts are published
- **SEO**: Manage meta descriptions and titles
- **Validation**: URL pattern validation for links

### Step 5: Viewing Changes

- Changes made in Pages CMS are automatically saved to your GitHub repository
- If using GitHub Pages, your website will update automatically
- You can also download the files and host them anywhere

## Configuration Details

The `.pages.yml` file defines:

```yaml
media: media                    # Media files location
content:
  - name: homepage             # Homepage content
    type: file
    path: src/_data/homepage.json
    
  - name: posts               # Blog posts collection
    type: collection
    path: src/posts
    
  - name: settings            # Site settings
    type: file  
    path: src/_data/site.json
```

## Customizing Fields

You can modify the `.pages.yml` file to:
- Add new content fields
- Change field types (text, rich-text, image, etc.)
- Add validation rules
- Configure field options

## Support

- **Pages CMS Documentation**: [https://pagescms.org/docs](https://pagescms.org/docs)
- **GitHub Issues**: Report issues on the Pages CMS GitHub repository
- **Community**: Join the Pages CMS community for support and discussions

## Tips for Success

1. **Regular Backups**: Your content is stored in GitHub, which provides version control
2. **Test Changes**: Preview your changes before publishing
3. **Organize Media**: Keep your media files organized in folders
4. **Use Tags**: Tag your blog posts for better organization
5. **SEO**: Fill in meta descriptions and titles for better search visibility

Start editing your content through Pages CMS and see how easy it is to manage your website!
