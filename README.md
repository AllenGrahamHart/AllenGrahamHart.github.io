# Academic Website

Personal academic website built with Hugo and the Hugo Blox (Academic) theme.

## Quick Start

### Preview Locally

To preview your site locally:

```bash
./hugo server -D
```

Then visit `http://localhost:1313` in your browser.

### Content Structure

- `content/authors/admin/_index.md` - Your bio and profile information
- `content/publication/` - Your publications
- `content/post/` - Blog posts
- `hugo.toml` - Main site configuration

### Customization

1. **Update your profile**: Edit `content/authors/admin/_index.md`
2. **Site settings**: Edit `hugo.toml` to change:
   - `baseURL` to your GitHub Pages URL (e.g., `https://username.github.io/`)
   - `title` to your name
   - Contact information in the `[params]` section
3. **Add publications**: Create new folders in `content/publication/` with an `index.md` file
4. **Write blog posts**: Create new folders in `content/post/` with an `index.md` file

### Deployment to GitHub Pages

1. Create a new repository on GitHub (e.g., `username.github.io`)
2. Push this code to the repository:
   ```bash
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/username/username.github.io.git
   git push -u origin main
   ```
3. In your GitHub repository, go to Settings > Pages
4. Under "Build and deployment", set Source to "GitHub Actions"
5. The site will automatically deploy when you push changes to the main branch

### Adding Content

#### Add a Publication

```bash
./hugo new content/publication/my-paper/index.md
```

Then edit the created file with your publication details.

#### Add a Blog Post

```bash
./hugo new content/post/my-post/index.md
```

Then edit the created file with your post content.

## Resources

- [Hugo Documentation](https://gohugo.io/documentation/)
- [Hugo Blox Documentation](https://docs.hugoblox.com/)
- [Markdown Guide](https://www.markdownguide.org/)

## License

This website template is based on Hugo Blox, which is licensed under the MIT License.
