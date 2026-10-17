# Vijayalakshmi R | Data Analyst Portfolio

A responsive personal portfolio website for **Vijayalakshmi R**, a Data Analyst focused on turning raw data into clear business insights through SQL, Python, Excel, Tableau, and Power BI.

The portfolio presents analytics projects, technical skills, education, professional experience, certifications, GitHub activity, and contact options in a single interactive page.

## Overview

This project is designed to give recruiters, hiring managers, and prospective collaborators a concise view of Vijayalakshmi's analytics background and project work.

The portfolio includes:

- Animated introduction and hero section
- Responsive navigation with mobile menu
- Dark and light themes
- About section with skills and career summary
- Searchable analytics project gallery
- Project links to GitHub and published demos
- Interactive analytics workflow visualization
- Experience and education timeline
- Certification showcase with PDF links
- GitHub repository and profile statistics loaded from the GitHub API
- Contact form powered by Formspree
- Responsive layouts for desktop, tablet, and mobile screens

## Analytics Project Portfolio

The portfolio features a comprehensive gallery of 26 end-to-end data analytics and business intelligence projects. By default, it displays the first 8 featured projects with an interactive **"View All Projects (26)"** button that smoothly reveals the full portfolio.

1. **Airport Flight Delay Analysis** — SQL, Python, Tableau
2. **Real Estate Market Analysis** — SQL, Tableau, Python, Excel
3. **Uber Analysis** — Tableau, SQL, Excel
4. **Retail Sales Analytics** — Tableau, SQL
5. **Expense Tracker Analysis** — Tableau, SQL, Python, Excel
6. **E-Commerce Sales Dashboard** — Power BI, Excel, DAX
7. **Hotel Booking Analysis** — Tableau, SQL, Excel
8. **Social Media Analysis** — Excel, Pivot Table
9. **Restaurant Order Analysis** — SQL, Tableau
10. **Logistic Shipment Analysis** — Excel, Pivot Table, Python
11. **Sales Dashboard** — Python, SQL, Tableau, Excel
12. **Healthcare Operation Intelligence Platform** — Power BI, DAX
13. **Startup Funding Intelligence Platform** — Power BI, DAX
14. **Personal Finance Dashboard** — SQL, Tableau
15. **Github Technology Trend Analyzer** — Power BI, DAX
16. **Job Market Intelligence Dashboard** — Power BI, DAX
17. **Banking Loan Risk Analysis** — Power BI, DAX, SQL, Excel
18. **Telecom Churn Analysis** — Tableau
19. **Pulse Board Analytics** — Tableau
20. **Movie OTT** — Power BI, DAX
21. **Movie Analysis** — SQL, Tableau
22. **Myntra Analysis** — Python, SQL, Excel, Power BI, DAX
23. **Nykaa Analysis** — Python, SQL, Tableau, Excel
24. **Smart City Traffic Analysis** — Power BI, DAX
25. **Airline Ticket Price Optimization** — Excel, Pivot Table
26. **College Placement Analytics** — Excel, Pivot Table

## Technology Stack

- **HTML5** for semantic page structure
- **CSS3** for responsive layouts, themes, animations, and visual styling
- **Vanilla JavaScript** for interactions and dynamic content
- **Font Awesome** for interface icons
- **AOS** for scroll-based reveal animations
- **Google Fonts**: Syne, DM Sans, and JetBrains Mono
- **GitHub REST API** for live profile and repository information
- **Formspree** for contact form submissions

## Project Structure

```text
Portfolio/
├── index.html              # Main portfolio page, styles, and scripts
├── images/                 # Project dashboard preview images
│   ├── E-Commerce.png
│   ├── Expense.png
│   ├── Overview.png
│   ├── Real.png
│   ├── Retail.png
│   └── Uber.png
└── pdf/                   # Resume and certificate documents
```

## Run Locally

This is a static website and does not require Node.js, Python, or a package installation.

### Option 1: Open directly

Open `index.html` in a modern web browser.

### Option 2: Use VS Code Live Server

1. Open the project folder in VS Code.
2. Start the project with the Live Server or Five Server extension.
3. Open the local URL shown by the extension.

Using a local server is recommended because it provides a more realistic browser environment for local assets and API requests.

## Customization

### Update portfolio content

Most visible content is maintained directly in `index.html`. Update the following areas as needed:

- Hero introduction and role labels
- About section and skill levels
- Project cards, images, descriptions, and links
- Timeline entries
- Certification details and PDF paths
- Contact details and social links

### Add a project

Add a new `.project-card` inside `#projectsGrid`. The current E-Commerce preview is stored at `images/E-Commerce.png`. Follow the existing card structure and provide:

- A project preview image in `images/`
- Project title and concise description
- Technology tags
- GitHub or demo links
- Descriptive `alt` text for the preview image

### Update GitHub repository cards

The live GitHub section is configured in the `dataAnalystRepos` array inside `index.html`. Add repository names there when they should appear in the featured repository list.

## External Services

The page uses the following external resources:

- Google Fonts CDN
- Font Awesome CDN
- AOS CDN
- GitHub public API
- Formspree contact form endpoint

An internet connection is required for external fonts, icons, animations, GitHub statistics, and contact form submission. The core page and local assets remain available without the GitHub API response.

## Deployment

Because this is a static website, it can be deployed to any static hosting provider, including:

- Vercel

For GitHub Pages, publish the repository or its deployment branch and use `index.html` as the site entry point.

## Accessibility and Responsive Design

The site includes semantic sections, navigation labels, descriptive image alt text, keyboard-friendly links and buttons, responsive breakpoints, and mobile navigation behavior. Before publishing, verify the page with a keyboard-only pass and a browser accessibility audit.

## Maintenance Checklist

- Keep project descriptions concise and outcome-focused.
- Replace placeholder or outdated social links before publishing.
- Confirm every project and PDF link opens correctly.
- Keep GitHub repository names synchronized with the live repository list.
- Test the page at desktop and mobile widths after content changes.
- Review external CDN availability and contact form configuration periodically.

## License

This portfolio is personal work by Vijayalakshmi R. Contact the owner before reusing its content, personal information, project descriptions, or visual assets.