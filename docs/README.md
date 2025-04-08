# Someone Discord Bridge Bot Documentation

This repository contains the documentation for the Someone Discord Bridge Bot, built with [Mintlify](https://mintlify.com/).

## Local Development

To preview the documentation site locally:

1. Install the Mintlify CLI:
   ```bash
   npm i -g mintlify
   ```

2. Clone this repository:
   ```bash
   git clone https://github.com/your-username/someone-docs.git
   cd someone-docs
   ```

3. Start the development server:
   ```bash
   mintlify dev
   ```

4. Visit [http://localhost:3000](http://localhost:3000) to see the documentation.

## Adding Content

The documentation is written in MDX (Markdown + JSX). To add a new page:

1. Create a new `.mdx` file in the appropriate directory.
2. Add frontmatter at the top of the file:
   ```mdx
   ---
   title: 'Page Title'
   description: 'Brief description of the page'
   ---
   ```
3. Add the page to the navigation in `docs.json`

## Adding Images

1. Place image files in the `/images` directory
2. Reference them in your MDX files:
   ```mdx
   <img src="/images/your-image.png" alt="Description of image" />
   ```

## Structure

- `docs.json` - Configuration file for the documentation site
- `introduction.mdx` - Landing page
- `features.mdx` - Key features of the bot
- `admin/` - Admin guides
- `users/` - User guides
- `troubleshooting.mdx` - FAQ and troubleshooting guide
- `images/` - Image assets

## Deployment

The documentation is automatically deployed when changes are pushed to the `main` branch.

## Feedback

If you find any issues or have suggestions for improvement, please open an issue or create a pull request.
