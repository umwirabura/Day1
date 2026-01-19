# Foundations of Modeling & Fabrication Documentation

Documentation website for the Foundations of Modeling & Fabrication course, built with MkDocs Material.

## 🚀 Quick Start (GitHub Method - No Local Install)

### Step 1: Fork This Repository
1. Click the "Fork" button at the top right of this page
2. This creates your own copy of the repository

### Step 2: Enable GitHub Pages
1. Go to your forked repository
2. Click **Settings** → **Pages** (left sidebar)
3. Under "Build and deployment":
   - Source: **GitHub Actions**
4. Wait 2-3 minutes for the first deployment

### Step 3: Edit Your Content
1. Click on the `docs/` folder
2. Click on any `.md` file (e.g., `index.md`)
3. Click the **pencil icon** (Edit this file)
4. Make your changes
5. Scroll down and click **Commit changes**
6. Wait 2-3 minutes - your site will automatically update!

### Step 4: Add Images
1. Go to `docs/assets/` folder
2. Click **Add file** → **Upload files**
3. Drag your images
4. Commit the changes
5. Reference them in your markdown: `![Description](assets/yourimage.png)`

### Step 5: View Your Site
Your site will be live at:
```
https://yourusername.github.io/repository-name/
```

---

## 📝 What to Edit

### Personal Information
- Open `mkdocs.yml` and update:
  - `site_author`
  - `site_description`

### Content Pages (in `docs/` folder)
- `index.md` - Home page with your introduction
- `modeling.md` - Your modeling work
- `fabrication.md` - Fabrication processes
- `prototyping.md` - Prototype iterations
- `reflection.md` - Critical reflection

### Adding Images
- Upload to `docs/assets/`
- Reference: `![Alt text](assets/image-name.png)`

---

## 🛠️ Local Development (Optional)

If you want to preview changes locally before pushing:

```bash
# Install Python dependencies
pip install mkdocs-material

# Run local server
mkdocs serve

# Open browser to http://127.0.0.1:8000
```

---

## 📚 Markdown Tips

### Headers
```markdown
# H1 Title
## H2 Subtitle
### H3 Section
```

### Images
```markdown
![Description](assets/image.png)
*Caption text*
```

### Lists
```markdown
- Item 1
- Item 2
  - Nested item
```

### Code
```markdown
\`\`\`python
print("Hello World")
\`\`\`
```

### Tables
```markdown
| Column 1 | Column 2 |
|----------|----------|
| Data 1   | Data 2   |
```

### Admonitions (Special Boxes)
```markdown
!!! info "Title"
    Your content here

!!! warning "Watch Out"
    Warning content

!!! tip "Pro Tip"
    Helpful advice
```

---

## 🎨 Customization

### Change Colors
Edit `mkdocs.yml` → `theme` → `palette` → `primary`

Options: red, pink, purple, indigo, blue, cyan, teal, green, lime, yellow, amber, orange, deep-orange

### Add More Pages
1. Create new `.md` file in `docs/`
2. Add to `mkdocs.yml` under `nav:`

---

## ✅ Checklist

- [ ] Fork this repository
- [ ] Enable GitHub Pages (Settings → Pages → GitHub Actions)
- [ ] Update `mkdocs.yml` with your name
- [ ] Edit `index.md` with your introduction
- [ ] Upload images to `docs/assets/`
- [ ] Complete all required pages
- [ ] Check your live site!

---

## 🆘 Troubleshooting

**Site not showing up?**
- Wait 3-5 minutes after first commit
- Check Settings → Pages → Make sure "GitHub Actions" is selected
- Check Actions tab for any errors

**Images not showing?**
- Make sure they're in `docs/assets/`
- Use correct path: `assets/image.png` (not `/assets/`)
- Check file name matches exactly (case-sensitive)

**Changes not appearing?**
- Wait 2-3 minutes after commit
- Hard refresh your browser (Ctrl+Shift+R)

---

## 📖 Resources

- [MkDocs Material Documentation](https://squidfunk.github.io/mkdocs-material/)
- [Markdown Guide](https://www.markdownguide.org/)
- [GitHub Pages Docs](https://docs.github.com/en/pages)

---

**Built with ❤️ using MkDocs Material**
