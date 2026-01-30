# Himanshu Bhusari - Personal Website

A clean, modern personal website and blog built with pure HTML, CSS, and JavaScript. No frameworks, no build tools - just simple, fast-loading pages.

## Live Site

🌐 **[himanshub15.github.io](https://himanshub15.github.io)**

---

## Features

- **Dark/Light Theme Toggle** - Respects system preference, remembers user choice
- **Responsive Design** - Works on desktop, tablet, and mobile
- **Matte Navy Blue Theme** - Easy on the eyes, professional look
- **No Dependencies** - Pure HTML/CSS/JS, fast loading
- **Blog with Posts** - Individual blog post pages with share functionality

---

## Project Structure

```
/
├── index.html                      # Homepage with intro and recent posts
├── photo.jpg                       # Profile photo
├── README.md                       # This file
│
├── posts/
│   ├── index.html                  # Posts listing page (organized by year)
│   └── two-photo-syndrome.html     # Blog post: The Two Photo Syndrome
│
└── about/
    └── index.html                  # About page with skills & contact
```

---

## Pages Overview

### 1. Homepage (`/index.html`)
- Profile section with photo, name, and tagline
- Social links (GitHub, LinkedIn, Email)
- Recent blog posts with orange accent headings
- RSS feed link

### 2. Posts Page (`/posts/index.html`)
- All blog posts organized by year
- Date displayed alongside each post
- Post excerpts and read time
- Clean, scannable layout

### 3. Blog Post (`/posts/two-photo-syndrome.html`)
- Full article with styled typography
- Monospace font for technical blog feel
- Calendar icon with date and read time
- Tags section (#photography, #storage, #mobile)
- Share buttons (X/Twitter, LinkedIn, Email)
- Back to Top link

### 4. About Page (`/about/index.html`)
- Profile photo with bio
- Two-paragraph introduction
- **Skill Cards** organized into categories:
  - Languages: Python, SQL, Linux
  - Databases & ETL: MySQL, PostgreSQL, Oracle, MariaDB, DBeaver, Alteryx, Talend
  - Analytics & Visualization: Tableau, Power BI, Grafana, Excel, Jupyter, PyCharm
  - Cloud Services: AWS, GCP, BigQuery, Looker
  - Project Management: JIRA, Notion
- "Let's Connect" section with contact buttons

---

## Color Scheme

### Dark Mode (Default)
| Element    | Color     | Hex       |
|------------|-----------|-----------|
| Background | Navy Blue | `#1a2332` |
| Text       | Off-White | `#d4dce8` |
| Accent     | Warm Orange | `#e07850` |
| Muted      | Blue-Gray | `#8899aa` |
| Border     | Dark Navy | `#2a3444` |
| Surface    | Card BG   | `#232f40` |

### Light Mode
| Element    | Color     | Hex       |
|------------|-----------|-----------|
| Background | Off-White | `#fafafa` |
| Text       | Dark Gray | `#1a1a1a` |
| Accent     | Blue      | `#0969da` |
| Muted      | Gray      | `#6b7280` |
| Border     | Light Gray| `#e5e5e5` |
| Surface    | Light Gray| `#f5f5f5` |

---

## Typography

- **Headings**: Geist (Sans-serif)
- **Body (Blog)**: Geist Mono (Monospace)
- **Meta/Dates**: Geist Mono (Monospace)

Fonts loaded from Google Fonts.

---

## How to Update

### Adding a New Blog Post

1. Create a new HTML file in `/posts/` (copy `two-photo-syndrome.html` as template)
2. Update the title, date, content, and tags
3. Add an entry to `/posts/index.html` under the appropriate year
4. Add an entry to `/index.html` in the posts section (for recent posts)

### Updating About/Skills

Edit `/about/index.html` - skills are organized in `.skill-card` divs with `.skill-tag` spans.

### Changing Colors

Update the CSS variables in the `<style>` section of each HTML file:
- `:root` for light mode
- `html[data-theme="dark"]` for dark mode

---

## Deployment

This site is hosted on **GitHub Pages**. Any push to the `main` branch automatically deploys.

To deploy manually:
```bash
git add .
git commit -m "Update site"
git push origin main
```

---

## Credits

- **Design Inspiration**: [steipete.me](https://steipete.me)
- **Fonts**: [Geist by Vercel](https://vercel.com/font)
- **Icons**: Custom SVG icons

---

## Contact

- **GitHub**: [@Himanshub15](https://github.com/Himanshub15)
- **LinkedIn**: [himanshubhusari](https://www.linkedin.com/in/himanshubhusari/)
- **Email**: himanshubhusari@gmail.com

---

Made with ☕ and curiosity.
