# Radiant Edges Developer Blog

This repository contains all blog content for the Radiant Edges community site.

## Repository Structure

```
blog/
├── articles/           # Blog posts organized by year/quarter
│   ├── 2025/
│   │   ├── q3-jul-sep/
│   │   │   └── welcome-to-radiant-edges-developer-blog.md
│   │   └── q4-oct-dec/
│   └── 2026/
│       ├── q1-jan-mar/
│       ├── q2-apr-jun/
│       ├── q3-jul-sep/
│       └── q4-oct-dec/
├── authors/           # Author profiles and information
├── assets/           # Shared images, videos, code samples
├── templates/        # Article templates
└── README.md
```

## Getting Started

**For Blog Writers**: 
1. If needed, delete the placeholder article in `q3-jul-sep/`
2. Create your first real article using the template in `templates/`
3. Follow the naming convention and frontmatter format
4. Submit via pull request

## Publishing Schedule

**Current Quarter**: Q3 2025 (Jul-Sep)
- Placeholder content available for testing
- Ready for real content creation

**Upcoming Quarters**:
- **Q4 2025 (Oct-Dec)**: Technical deep-dives
- **Q1 2026 (Jan-Mar)**: Industry analysis and case studies
- **Q2 2026 (Apr-Jun)**: Emerging technologies and trends

## Article Naming Convention

- Use kebab-case for filenames
- Organize by quarter: `YYYY/qN-month-month/article-name.md`
- Example: `articles/2025/q3-jul-sep/your-article-title.md`

## Article Template

Each article should follow this frontmatter structure:

```yaml
---
title: "Your Article Title"
author: "Author Name"
date: "2025-07-15"
tags: ["AI", "UI/UX", "Engineering"]
excerpt: "Brief description of the article content..."
slug: "your-article-slug"
---
```

# Article Title

Your article content here in Markdown format.

## Submission Process

### Internal Team Process
1. Create a new branch: git checkout -b article/your-article-name
2. Add your article following the template
3. Include any assets in the assets/ folder with descriptive names
4. Commit and push: git push origin article/your-article-name
5. Create pull request for review
6. Merge after approval

### External Contributors
1. Fork this repository
2. Create a new branch: git checkout -b article/your-article-name
3. Add your article in the appropriate date folder
4. Create a pull request with a clear description
5. Wait for review and approval

## Publishing Workflow

- Articles are automatically pulled from this repository by the community site
- Published articles appear at: https://community.radiantedges.com/blog/article-slug
- Share buttons are automatically added to each article

## Writing Guidelines

- **Audience**: Engineers, designers, researchers, founders
- **Tone**: Technical but accessible, professional yet engaging
- **Topics**: AI-native applications, edge computing, modern architecture
- **Length**: 800-2000 words typically
- **Code**: Include relevant examples with proper syntax highlighting
- **Images**: Use descriptive alt text, optimize for web
- **Links**: Reference credible sources, avoid excessive external links

## Content Categories

- **Engineering Deep-Dives**: Technical architecture, implementation details
- **Industry Analysis**: Trends, market insights, technology adoption
- **Case Studies**: Real-world applications, lessons learned
- **Tutorials**: Step-by-step guides, how-to content
- **Opinion**: Thought leadership, predictions, commentary

## SEO Best Practices

- Use descriptive, keyword-rich titles
- Write compelling meta descriptions (excerpt field)
- Include relevant tags
- Use proper heading hierarchy (H1, H2, H3)
- Optimize images with alt text
- Include internal and external links where relevant
