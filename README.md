TS TECHSOLUTIONL
Professional website and static blog system for TS TECHSOLUTIONL, focused on Mechanical Engineering, Manufacturing, CAD & 3D Modeling, Product Visualization, Digital Solutions, CNC Machining, 3D Printing, and related engineering services.
🌐 Live Website: https://tstechsolutionl.github.io/tstechsolutionl/
📧 Email: tstechsolution.in@gmail.com
📌 Project Overview
This repository contains the website for TS TECHSOLUTIONL, built as a lightweight static website suitable for GitHub Pages.
The website includes:
Professional responsive homepage
Mechanical & Engineering services
Manufacturing services
CAD & 3D Modeling
CNC Machining
3D Printing
Product Visualization
Engineering Visualization
Projects section
Careers section
Contact section
Static Blog system
Individual blog post pages
SEO metadata
Google Search Console verification
XML sitemap
Mobile-friendly navigation
🗂️ Project Structure
tstechsolutionl/
│
├── index.html
├── blog.html
├── styles.css
├── logo.png
├── sitemap.xml
├── README.md
│
├── post-template.html
│
└── posts/
    ├── _post-template.html
    ├── multi-function-cnc-3d-printing.html
    ├── cad-to-prototype.html
    └── engineering-visualization.html
📰 Blog System
The blog is implemented as a static blog system, so it does not require a database, WordPress, PHP, or a server.
Current Posts
Developing a Multi-Function CNC & 3D Printing Machine
From CAD Model to Prototype: A Practical Workflow
Why Engineering Visualization Matters
Each article has its own HTML page inside the posts/ folder.
✍️ How to Add a New Blog Post
Step 1 — Copy the Post Template
Open:
post-template.html
Copy the file into:
posts/
For example:
posts/new-engineering-article.html
Step 2 — Change the Page Title
Find:
<title>Your Blog Post Title | TS TECHSOLUTIONL</title>
Replace it with your article title.
Example:
<title>5 Important CNC Design Considerations | TS TECHSOLUTIONL</title>
Step 3 — Update the Description
Find the meta description:
<meta name="description" content="Your blog post description.">
Replace it with a short description of the article.
Example:
<meta name="description" content="Learn five important CNC machine design considerations for accurate and reliable machining.">
Step 4 — Add the Article Content
Replace the sample article content with your own content.
A simple structure is:
<article class="post-content">

    <h1>5 Important CNC Design Considerations</h1>

    <p>
        Introduction to the topic...
    </p>

    <h2>1. Machine Structure</h2>

    <p>
        Explain the first topic...
    </p>

    <h2>2. Lead Screw Selection</h2>

    <p>
        Explain the second topic...
    </p>

    <h2>Conclusion</h2>

    <p>
        Final summary...
    </p>

</article>
Step 5 — Add the Post to blog.html
Open:
blog.html
Add a new blog card.
Example:
<article class="blog-card">

    <div class="blog-card-content">

        <span class="blog-category">
            Engineering
        </span>

        <h3>
            5 Important CNC Design Considerations
        </h3>

        <p>
            Learn the key factors to consider when designing
            a CNC machine.
        </p>

        <a href="posts/new-engineering-article.html">
            Read Article →
        </a>

    </div>

</article>
Step 6 — Add the Post to the Sitemap
Open:
sitemap.xml
Add the new page URL.
Example:
<url>
    <loc>https://tstechsolutionl.github.io/tstechsolutionl/posts/new-engineering-article.html</loc>
</url>
After publishing the change, Google can discover the new page through the sitemap.
🎨 Website Styling
The website uses a shared stylesheet:
styles.css
All major pages use this stylesheet to maintain a consistent design.
If you change colors, spacing, buttons, navigation, cards, typography, or responsive behavior, update styles.css.
🖼️ Logo
The website logo is stored as:
logo.png
If you replace the logo, keep the filename:
logo.png
This avoids having to update image references throughout the website.
📱 Responsive Design
The website is designed to work on:
Desktop
Laptop
Tablet
Android phones
iPhone
Other modern mobile browsers
The navigation includes a mobile menu for smaller screens.
🔎 SEO
The website includes basic SEO features such as:
Page titles
Meta descriptions
Responsive viewport metadata
Google Search Console verification
Sitemap
Individual URLs for blog articles
Descriptive blog titles
Internal links
Google Search Console
The site has been configured for Google Search Console verification.
After adding or changing important pages, use Google Search Console to inspect the URL and request indexing when appropriate.
🗺️ Sitemap
The sitemap is:
sitemap.xml
Website sitemap URL:
https://tstechsolutionl.github.io/tstechsolutionl/sitemap.xml
When new blog pages are added, update the sitemap with their URLs.
🚀 GitHub Pages Deployment
This project is designed for GitHub Pages.
1. Open the Repository
Open the TS TECHSOLUTIONL GitHub repository.
2. Upload the Files
Upload:
index.html
blog.html
styles.css
logo.png
sitemap.xml
post-template.html
README.md
posts/
Make sure the posts folder contains the individual article files.
3. Commit the Changes
Use a clear commit message such as:
Add complete static blog system
4. Check GitHub Pages
Open the repository's:
Settings → Pages
Select the appropriate branch and root folder if GitHub Pages is not already configured.
🔗 Important Website URLs
Homepage
https://tstechsolutionl.github.io/tstechsolutionl/
Blog
https://tstechsolutionl.github.io/tstechsolutionl/blog.html
Sitemap
https://tstechsolutionl.github.io/tstechsolutionl/sitemap.xml
📧 Contact
For business enquiries:
Email: tstechsolution.in@gmail.com
🛠️ Technologies Used
HTML5
CSS3
JavaScript
GitHub Pages
XML Sitemap
No backend server is required for the current website.
📄 License
This website and its original content are intended for TS TECHSOLUTIONL.
Unless otherwise stated, do not copy, redistribute, or reuse the website's original branding, graphics, written content, or proprietary project material without permission.
🔄 Recommended Workflow for Future Updates
For a normal website update:
1. Edit the required HTML/CSS file
        ↓
2. Test the website locally
        ↓
3. Upload/commit the changes to GitHub
        ↓
4. Wait for GitHub Pages deployment
        ↓
5. Open the live website
        ↓
6. Check desktop + mobile layout
        ↓
7. For new pages, update sitemap.xml
        ↓
8. Use Google Search Console for important new URLs
For a new blog post:
Create HTML file
      ↓
Place it inside /posts/
      ↓
Add blog card to blog.html
      ↓
Add URL to sitemap.xml
      ↓
Commit to GitHub
      ↓
Check live page
      ↓
Request indexing when appropriate
⚙️ Future Improvements
Possible future upgrades include:
Blog search
Blog categories
Blog tags
Featured images
Related articles
Pagination
RSS feed
Contact form
Project gallery
Case studies
Dark/light theme
Analytics
Automated sitemap generation
Headless CMS integration
© TS TECHSOLUTIONL
Mechanical Engineering • Manufacturing • Visualization • Digital Solutions
Built for the TS TECHSOLUTIONL web presence.