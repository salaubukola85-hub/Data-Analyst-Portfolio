SALAU BUKOLA | DATA ANALYST PORTFOLIO

PROJECT FILES

index.html
  The page content: profile details, skills, project summaries, findings, evidence
  links and contact details. The four featured projects appear first; all eight
  original project cards remain available.

style.css
  Colours, typography, responsive layout and screenshot gallery styling. Images keep
  their aspect ratio and scale to fit desktop, tablet and mobile layouts.

script.js
  Mobile navigation and the automatic copyright year.

EDIT YOUR CONTENT

Open index.html and edit the visible text. Each project is an article with the
project-card class. Project findings are transcribed from public repository READMEs
and have not been independently recalculated. The dashboard images are actual assets
from the matching public project repositories.

SCREENSHOT FILES

Screenshots are stored locally in images/projects/ and copied from the matching
public GitHub repositories:

  images/projects/coffee-shop-dashboard.png
  images/projects/adidas-sales-dashboard.png
  images/projects/hr-analytics-dashboard-1.png
  images/projects/hr-analytics-dashboard-2.png
  images/projects/student-performance-overview.png
  images/projects/student-performance-detail.png
  images/projects/titanic-dashboard.png
  images/projects/inventory-risk-dashboard.png
  images/projects/inventory-risk-analysis.png
  images/projects/fintrust-loan-dashboard.png
  images/projects/fintrust-repayment-dashboard.png
  images/projects/sales-revenue-dashboard.png
  images/projects/sales-customer-dashboard.png
  images/projects/sales-revenue-dashboard-2.png

ADD OR REPLACE A SCREENSHOT

1. Add the image file to images/projects/.
2. In the matching project-gallery in index.html, set both the enclosing link's
  href and the image's src to the relative path, such as:

  <a href="images/projects/my-dashboard.png" target="_blank" rel="noreferrer">
    <img src="images/projects/my-dashboard.png" alt="Dashboard showing monthly sales by region">
  </a>

3. Write concise alt text describing the dashboard content. Keep the href and src
  identical so clicking the preview opens its full-size image.

The gallery uses object-fit: contain, so screenshots are not cropped or distorted.
Images lazy-load on the page; original files open separately when selected. Do not
label a screenshot as an interactive dashboard. Add an interactive-dashboard link
only if the repository has a real public interactive destination.

UPDATE LINKS

Contact links are configured in the contact section of index.html. Review the
LinkedIn, GitHub and email destinations before publishing; they were not
click-tested during this update.

Each project card links to its public GitHub repository. Update those href values if
repository URLs or files change. Project titles, summaries, tools, findings and
evidence links are editable in the same card.

ADD A CV

No CV was present in the supplied project files. To provide one:

1. Create the folder assets/cv/ if it does not exist.
2. Add your real CV as assets/cv/Salau-Bukola-CV.pdf.
3. In index.html, replace the disabled Download CV button and its status message
   with a link to that file, using href="assets/cv/Salau-Bukola-CV.pdf" and the
   download attribute.

The button is intentionally disabled until a real CV is supplied; no empty or
placeholder download link is used.

EDUCATION, CERTIFICATIONS AND TRAINING

The Education and Professional Development section distinguishes the B.Sc.
Psychology from the University of Ibadan, the Google Data Analytics Professional
Certificate from Google/Coursera, Data Analytics Training from Tech Studio Academy,
and the Data Visualization Internship at Excelerate. The January 2026 Easy
Technologies sales and customer growth internship project links to its repository.
No credential dates, IDs or verification links are asserted.

PUBLISH WITH GITHUB PAGES

1. Create a GitHub repository and upload the portfolio files, keeping index.html,
   style.css and script.js in the repository root.
2. Open the repository's Settings, then Pages.
3. Under Build and deployment, choose Deploy from a branch.
4. Select the main branch and the /(root) folder, then save.
5. Wait for the deployment to finish. GitHub Pages will show the published URL in
   the Pages settings.

The Google Fonts link is optional; the site falls back to system fonts if it cannot
load. No framework or build step is required.
