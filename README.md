# Yang Wang's Personal Website

This repository contains the source code for my personal academic website, built with Jekyll and hosted via GitHub Pages at [yangcheme.github.io](https://yangcheme.github.io).

## Overview

This is a responsive, modern personal website designed to showcase my:
- Professional background
- Research interests and projects
- Publications
- CV/Resume
- Contact information

## Structure

The website is built using Jekyll with a clean, modular structure:

```
/
├── _config.yml                # Jekyll configuration
├── _data/                     # Data files
│   ├── education.yml          # Education history
│   └── experience.yml         # Professional experience
├── _includes/                 # Reusable components
│   ├── header.html            # Header component
│   ├── footer.html            # Footer component
│   └── contact.html           # Contact section
├── _layouts/                  # Page templates
│   ├── default.html           # Default layout
│   └── home.html              # Home page layout
├── _publications/             # Publication collection
│   ├── publication-1.md       # Publication entries
│   └── publication-2.md
├── _research/                 # Research collection
│   ├── molecular-dynamics.md  # Research entries
│   ├── computational-chemistry.md
│   └── biomolecular-interactions.md
├── assets/                    # Static assets
│   ├── css/
│   │   └── style.css          # Main stylesheet
│   ├── js/
│   │   └── script.js          # JavaScript functionality
│   ├── images/                # Image files
│   │   └── profile.jpg        # Profile photo
│   └── docs/                  # Documents
│       └── CV_YangWang.pdf    # CV/Resume file
├── index.md                   # Home page content
├── Gemfile                    # Ruby dependencies
└── README.md                  # This file
```

## Development

### Local Development

To run this site locally:

1. Install Ruby and Jekyll (if not already installed)
   ```
   gem install bundler jekyll
   ```

2. Clone this repository
   ```
   git clone https://github.com/YangChemE/YangChemE.github.io.git
   cd YangChemE.github.io
   ```

3. Install dependencies
   ```
   bundle install
   ```

4. Start the Jekyll server
   ```
   bundle exec jekyll serve
   ```

5. View the site at http://localhost:4000

### Content Updates

To update the website content:

- **About**: Edit the content in `index.md`
- **Research**: Add/edit files in the `_research/` directory
- **Publications**: Add/edit files in the `_publications/` directory
- **CV**: Update the entries in `_data/education.yml` and `_data/experience.yml`
- **Contact**: Edit the contact information in `_config.yml`

### Design Updates

To modify the visual style:

1. Edit the CSS variables at the top of `assets/css/style.css` to change colors, spacing, etc.
2. Modify specific CSS rules for more detailed styling changes

## Deployment

This site is automatically deployed to GitHub Pages when changes are pushed to the main branch. 

## Contact Form

The contact form is set up to use Formspree. To make it functional:

1. Sign up for a free account at [Formspree](https://formspree.io/)
2. Create a new form and get your form ID
3. Add your form ID to the `formspree_id` field in `_config.yml`

## License

This project is open source and available under the [MIT License](LICENSE).

---

Created by Yang Wang
