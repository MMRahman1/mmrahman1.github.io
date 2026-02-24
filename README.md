# mmrahman1.github.io — Blog Portfolio

A personal blog portfolio site built with Jekyll and Bulma CSS, inspired by [pariscall.international](https://github.com/ambanum/pariscall.international).

Live site: **https://mmrahman1.github.io**

---

## 📋 Information Needed (Placeholders to Replace)

Please provide the following information so all `[PLACEHOLDER]` values can be filled in:

### 👤 Personal Info
| Placeholder | Description | Replace with |
|-------------|-------------|---------|
| `[YOUR_FULL_NAME]` | Your full name (appears in navbar, hero, footer) | `Md Mahmudur Rahman` |
| `[YOUR_PROFESSIONAL_TITLE]` | Your job title or role | `Full Stack Developer` |
| `[YOUR_TAGLINE]` | A one-line summary for SEO/meta description | `Building elegant web applications` |
| `[YOUR_SHORT_BIO]` | 1–2 sentence bio for hero section | `I'm a software engineer...` |
| `[YOUR_EXTENDED_BIO_PARAGRAPH_1]` | First paragraph of detailed bio (About page) | — |
| `[YOUR_EXTENDED_BIO_PARAGRAPH_2]` | Second paragraph of detailed bio | — |
| `[YOUR_HOBBIES_AND_INTERESTS]` | What you do outside work | `hiking, photography, chess` |
| `[YOUR_CONTACT_INTRO]` | Intro text for Contact section | `I'm open to new opportunities…` |

### 📷 Media
| Placeholder | Description |
|-------------|-------------|
| `/assets/images/avatar.jpg` | Hero profile photo (square, ~400×400px) |
| `/assets/images/about.jpg` | About page photo (portrait or landscape) |
| `/assets/images/projects/[name].jpg` | Screenshots for each project |

### 🔗 Contact & Social
| Placeholder | Description |
|-------------|-------------|
| `[YOUR_EMAIL]` | Contact email address |
| `[YOUR_TWITTER_HANDLE]` | Twitter/X username (without `@`) |
| `[YOUR_LINKEDIN_USERNAME]` | LinkedIn profile slug (from `linkedin.com/in/SLUG`) |
| `[YOUR_RESUME_PDF_URL]` | URL to a downloadable PDF resume |

### 💼 Projects (repeat for each project)
For each project, create a file in `_projects/` using `sample-project.md` as a template:

| Placeholder | Description |
|-------------|-------------|
| `[PROJECT_TITLE]` | Name of the project |
| `[SHORT_DESCRIPTION]` | One-sentence summary |
| `[TECH_1]`, `[TECH_2]`, … | Technologies/languages used |
| `[LIVE_DEMO_URL]` | URL to live demo (if any) |
| `[REPO_NAME]` | GitHub repository name |
| `[PROJECT_IMAGE]` | Screenshot filename in `assets/images/projects/` |
| `[PROJECT_OVERVIEW]` | Full description (markdown) |
| `[FEATURE_1]`, `[FEATURE_2]`, … | Key feature bullet points |
| `[CHALLENGES]` | What you learned |

### ✍️ Blog Posts (repeat for each post)
Create `.md` files in `_posts/` named `YYYY-MM-DD-title.md`:

| Placeholder | Description |
|-------------|-------------|
| Post title | Title of the blog post |
| Post categories | e.g., `[tutorial, javascript]` |
| Post content | Full markdown content |

### 🎓 Education (About page)
| Placeholder | Description |
|-------------|-------------|
| `[DEGREE_TITLE]` | e.g., `BSc Computer Science` |
| `[INSTITUTION_NAME]` | Name of university/college |
| `[START_YEAR]` / `[END_YEAR]` | e.g., `2019` / `2023` |
| `[ADDITIONAL_INFO]` | GPA, major, thesis, etc. |

### 💼 Work Experience (About page)
| Placeholder | Description |
|-------------|-------------|
| `[JOB_TITLE]` | e.g., `Software Engineer Intern` |
| `[COMPANY_NAME]` | Name of company |
| `[START_DATE]` / `[END_DATE]` | e.g., `June 2022` / `August 2022` |
| `[JOB_DESCRIPTION]` | Responsibilities and achievements |

### 🏅 Certifications (About page)
| Placeholder | Description |
|-------------|-------------|
| `[CERTIFICATION_NAME]` | e.g., `AWS Certified Developer` |
| `[ISSUING_ORGANIZATION]` | e.g., `Amazon Web Services` |
| `[YEAR]` | Year obtained |

### 🛠 Skills
| Placeholder | Description |
|-------------|-------------|
| `[LANGUAGE_1..4]` | Programming languages (e.g., Python, JavaScript) |
| `[FRAMEWORK_1..3]` | Frameworks/libraries (e.g., React, Django) |
| `[TOOL_1..3]` | Tools/platforms (e.g., Docker, AWS) |
| `[SOFT_SKILL_1..3]` | Soft skills (e.g., Team Leadership) |

---

## 🚀 Local Development

```bash
# Install dependencies
bundle install

# Serve locally
bundle exec jekyll serve

# Open http://localhost:4000
```

## 📁 Project Structure

```
├── _config.yml          # Site configuration (fill in your info here first)
├── index.html           # Landing page (hero, about, skills, projects, blog, contact)
├── about.html           # Detailed about page (experience, education, skills)
├── blog.html            # Blog post listing
├── projects.html        # Projects portfolio grid
├── _layouts/            # Page templates
│   ├── default.html     # Base layout (navbar + footer)
│   ├── post.html        # Blog post layout
│   ├── project.html     # Project detail layout
│   └── page.html        # Generic page layout
├── _includes/           # Reusable components
│   ├── navbar.html      # Navigation bar
│   └── footer.html      # Footer
├── _posts/              # Blog posts (YYYY-MM-DD-title.md)
├── _projects/           # Project files (title.md)
└── assets/
    ├── css/style.scss   # Custom styles (Bulma-based)
    └── images/          # Photos and screenshots
```

