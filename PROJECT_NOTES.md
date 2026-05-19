# Disha Patel Portfolio Website - Project Notes

Last updated: May 18, 2026

This file captures the context, decisions, content changes, and current structure of Disha Patel's portfolio website so the work can be picked up later without rereading the full chat.

## Project Goal

Build a visually distinctive portfolio website for Disha Patel that positions her as a Technical Project Manager with strong cross-functional delivery experience. The site should feel more memorable than a standard project manager portfolio while staying professional, recruiter-friendly, and easy to update.

The website is a static HTML/CSS site located at:

`/Users/disha/Documents/Codex/2026-05-14/help-me-make-a-portfolio-website`

## Current Main Files

- `index.html` - homepage
- `projects.html` - project listing page
- `project-perforce-gitlab.html` - Perforce to GitLab Migration detail page
- `project-pantry-pal.html` - Pantry Pal detail page
- `project-pay-equity.html` - Pay Equity Process Development detail page
- `project-keys-to-me.html` - Keys to Me detail page
- `project-ad-lib.html` - AD-LIB detail page
- `resume.html` - resume page
- `styles.css` - shared styling
- `assets/disha-patel.jpg` - homepage photo
- `assets/project-images/` - project-page images extracted from user documents and screenshots
- `PROJECT_NOTES.md` - this file

## Original Direction

The user asked for a portfolio website with:

- Home screen
- Projects page
- View Resume button at the top
- Currently studying section
- A recommendation on whether skills should be separate

Recommendation chosen:

- Keep skills as a distinct section, but not as the main story.
- Use the homepage to lead with positioning, experience, selected projects, working style, skills, continued learning, and education.

## Source Portfolio

The user's previous portfolio was:

`https://dishapatelresume.framer.website`

It was used to populate the first version of the site with Disha's name, role, background, resume link, and professional content.

Important profile details:

- Name: Disha Patel
- Role: Technical Project Manager
- Location: San Francisco Bay Area, CA
- Email: `pateldi1024@gmail.com`
- LinkedIn: `https://www.linkedin.com/in/disha-patel2411`
- Resume link: `https://drive.google.com/file/d/1k5mMur9gWTyX9e15lNpU_miYwQ8PfGhx/view?usp=sharing`
- PDF resume source: `https://framerusercontent.com/assets/G0d6H1LbzyU5X1JMoCKbcLfIR4.pdf`

## Visual Direction

The first version used a polished portfolio style, but the user wanted something more out of the box and less generic for a project manager portfolio.

The homepage was then redesigned around:

- A more personal opening: "Hey there, I'm Disha."
- A prominent photo-based hero
- Animated homepage details
- A stronger project manager story
- A colorful, personal visual identity

## Brand Colors

The user first shared a "Dreamscape Harmony" palette, then replaced it with a brighter attached palette. The current palette is based on:

- Cream
- Vanilla
- Lime
- Lemon
- Pink Grapefruit
- Raspberry

Current CSS color direction:

- Cream: `#fbf7ef`
- Vanilla: `#eee3c7`
- Lime: `#b9b43f`
- Lemon: `#f2a923`
- Pink Grapefruit: `#cf6579`
- Raspberry: `#bd2454`
- Deep sage/ink accents: `#2d3429`, `#455341`

The palette was intentionally made brighter after the user said the colors were not popping enough.

## Typography Notes

The user disliked the first "Disha Patel" font. The homepage name was changed to a more editorial serif direction:

`"Cormorant Garamond", "Playfair Display", Georgia, "Times New Roman", serif`

The goal was to make the name feel more elegant, warm, and distinctive.

## Image Notes

The user provided:

`/Users/disha/Downloads/IMG_4652.jpg`

This became the primary homepage photo. There was an issue where the photo appeared as a black circle, which was fixed by updating the image handling and using the correct asset.

Current main photo asset:

`assets/disha-patel.jpg`

Older generated/processed versions remain in the assets folder:

- `assets/disha-patel-web.jpg`
- `assets/disha-patel-portrait.jpg`
- `assets/disha-patel-center.jpg`

The site currently references `assets/disha-patel.jpg`.

## Current Homepage Structure

The user requested the homepage sections in this order:

1. About me
2. Experience
3. Projects
4. How I work
5. Skills
6. Continue Learning
7. Education

There is still an opening hero above the About Me section.

## Homepage Hero

The hero was changed from a more standard portfolio intro to a more personal and visual opening.

Current hero direction:

- "Hey there, I'm"
- "Disha Patel"
- "Technical Project Manager"
- Short positioning copy
- Photo treatment with decorative/animated labels
- More visual personality than a standard resume homepage

The user liked the earlier animated/homepage concept but asked to move that style lower and start with a direct personal intro.

## About Me Section

The About Me section went through several revisions:

- It was first placed in a boxed layout.
- The user asked to remove the box.
- It became a two-column layout.
- The user then asked for subtitle/body format instead of columns.
- The left column alignment was changed to left aligned.
- Body text was justified.
- The closing line was styled in bright pink on a beige background.

Current About Me content:

Subtitle:

> When projects get complicated, competing priorities, unclear ownership, teams pulling in different directions that's exactly where I do my best work.

Body paragraph 1:

> I’m a Technical Project Manager with 4+ years of experience working at the intersection of engineering and business. I help teams reduce ambiguity early, build realistic plans, and maintain momentum as priorities shift.

Body paragraph 2:

> I care deeply about the human side of project management. The best delivery process is one the team will actually follow, and the best status update gives leadership clear visibility without unnecessary detail. Getting that balance right takes judgment as much as process knowledge.

Closing note:

> If any of this resonates and you're building out your PM team, I would love to connect.

Styling notes:

- No surrounding box
- Subtitle matches the section-heading style
- Body copy uses a readable paragraph format
- Closing note has bright pink text and beige background

## Experience Section

The user provided updated experience wording. The existing work experience structure was kept, but the copy was updated.

Current entries:

### Technical Project Manager

Broadridge Financial Solutions  
Mar 2024 - Oct 2025

> Led multiple cloud, DevOps, Database and security initiatives driving migrations, cross-functional alignment, and compliance efforts to improve delivery speed, reliability, and operational efficiency.

### Project Coordinator

Broadridge Financial Solutions  
Sep 2021 - Feb 2024

> Improved platform delivery and operations by reducing turnaround time, eliminating manual effort, and driving process, testing, and onboarding enhancements for scalable adoption.

### Administrative Assistant

Rajesh G. Kaapdia & Associates  
Jan 2019 - Jun 2019

> Supported office operations by managing communications, documentation, and records while ensuring confidentiality and tracking key actions and decisions.

### Administrative Assistant

Basosn Machines  
May 2018 - Dec 2018

> Managed office operations and customer interactions by handling communications, scheduling, records, and administrative processes to ensure smooth and efficient workflows.

## Homepage Featured Projects

The homepage currently features:

1. Perforce to GitLab Migration
2. Pantry Pal
3. Pay Equity Process Development

The earlier "Repo Intake Process" card was removed and replaced with Pay Equity Process Development.

## How I Work Section

The first version had a more visual "Migration Program" / process dashboard treatment. The user disliked it and asked for something different.

It became a four-part operating rhythm:

1. Read the room
   - I listen for the real blockers: unclear ownership, hidden dependencies, mismatched expectations, and the decisions nobody has named yet.
2. Map the work
   - I turn moving parts into a plan people trust, with scope, timelines, owners, risks, and handoffs visible enough to act on.
3. Keep alignment
   - I keep technical and business teams aligned, surface open questions early, and make sure decisions keep moving instead of stalling in the background.
4. Protect momentum
   - I build delivery rhythms that teams will actually follow, so progress stays steady even when priorities shift.

The user specifically updated item 03 to "Keep alignment" with the current wording above.

## Skills Section

Skills were kept as a separate homepage section, but the top navigation link to Skills was removed later at the user's request.

The current top navigation does not include a Skills link.

## Continue Learning Section

The original "Currently studying" section evolved into "Continue Learning."

The user later provided new wording. Current section:

Eyebrow:

> Expanding My Toolkit

Heading:

> Sharpening the systems behind better delivery

Cards:

1. AI-assisted workflows
   - Exploring how AI can support project planning, stakeholder communication, lightweight automation, and operational efficiency.
2. Technical foundations
   - Learning Python and building small AI-driven projects to strengthen technical fluency and better collaborate with engineering teams.
3. Service management & delivery
   - Preparing for ITIL certification while deepening knowledge of incident management, operational processes, and enterprise service delivery.
4. Technical delivery leadership
   - Deepening cloud, DevOps, database, security, and compliance fluency for complex cross-functional programs.

## Education Section

Current education entries:

- Postgraduate Diploma, Business Analysis & Process Management - Sheridan College
- Postgraduate Diploma, Project Management - Fleming College
- Bachelor of Technology, Mechatronics Engineering - NMIMS University

## Footer / Contact Area

The user requested:

- Change "Based in San Jose, CA" to "Based in San Francisco Bay Area, CA"
- Remove "Designed and built for Disha Patel."
- Remove repeated `pateldi1024@gmail.com` from the page bottom

Current contact area includes:

- Based in San Francisco Bay Area, CA
- Let's connect about technical delivery work.
- Email link in the contact band

## Navigation

The top navigation currently includes:

- Home
- Projects
- LinkedIn
- View Resume

The Skills link was removed from the top bar.

## Projects Page Direction

The user asked to update the Projects page to show cards similar to the homepage and organize work into three main categories:

- Work Project
- Personal Project
- Course Project

Each card should be clickable and open a separate page for the project.

The user also asked to remove these category descriptions from the Projects page:

- Technical delivery in enterprise environments
- Product thinking built from everyday friction
- Applied project work across business and engineering

Current project order:

1. Perforce to GitLab Migration
2. Pantry Pal
3. Pay Equity Process Development
4. Keys to Me Student Workshop Series
5. AD-LIB Automated Library Management System

Keys to Me was moved above AD-LIB.

## Project Links

External project links were added:

- Pantry Pal:
  `https://pantry-pal-48809fe8.base44.app`
- Pay Equity:
  `https://drive.google.com/drive/folders/1Sl-2hkLrLFH-8QArd_9c5hAjAoF6SHhZ?usp=share_link`
- Keys to Me:
  `https://drive.google.com/drive/folders/1JJ6oV6yRhFuGpoSryuAxUyOcWDQWGwJJ?usp=share_link`
- AD-LIB:
  `https://drive.google.com/drive/folders/157PLTvr2VPmZtzAsL1ViVcQD3YNhRI86?usp=share_link`

The user originally phrased each button as "Open Pantry Pal," but the intent was to wire each project's "open" link to the correct destination.

External links had trouble from `file://`, so the note is to preview via a local server:

`http://localhost:8080/projects.html`

## Project Detail Page Direction

The user wanted each project detail page to:

- Use content from the attached Word/Google documents
- Keep the words and format as-is from the documents
- Avoid rewriting or summarizing document content
- Keep "Skills Demonstrated" on the right side
- Show metrics at the top in three boxes
- Place images in the same flowing sequence as the source document
- Use one content box per major section

Shared page structure:

- Hero/title
- "See project documents" or project link button
- Three metric boxes at the top
- Main content column with document-based content boxes
- Right-side skills panel

The title, button, and top metric font sizes were reduced because the user said they looked too large.

## Project Metrics Style

The user shared a reference image showing metrics like:

- `50+` depots migrated
- `$104K` budget managed
- `10h+` weekly overhead eliminated

The project pages now use a three-box metric format near the top.

Relevant CSS direction:

- `.project-detail-hero h1` uses reduced responsive sizing
- `.project-detail-hero .button` was made smaller
- `.metric-showcase strong` was reduced
- `.metric-showcase span` was reduced

## Perforce to GitLab Migration Page

File:

`project-perforce-gitlab.html`

Category:

Work Project

Current top metrics:

- `50+` depots migrated
- `$104K` budget managed
- `10h+` weekly overhead eliminated

The user asked to keep all wording and format from the document, not rewrite or summarize it. The page was then split into boxes:

1. Overview
2. The Challenge
3. My Role
4. Execution Approach
5. Outcomes
6. What this project strengthened

This page currently has no document images.

## Pantry Pal Page

File:

`project-pantry-pal.html`

Category:

Personal Project

Source Google Doc:

`https://docs.google.com/document/d/1hPwLkN0KSCNSQWzGwi0ZEY88K3uTywXrsu59UOY57mc/edit?usp=sharing`

The user asked to update the Pantry Pal page from this Google Doc and use one box for each:

1. Overview
2. The Challenge
3. My Role
4. Product Evolution
5. Outcomes
6. What this project strengthened

The user also noticed the images were wrong and asked to update them to match the Google Doc. The images were extracted and replaced.

Current Pantry Pal image assets:

- `assets/project-images/pantry-pal-overview.png`
- `assets/project-images/pantry-pal-discovery-1.png`
- `assets/project-images/pantry-pal-discovery-2.png`
- `assets/project-images/pantry-pal-shopping.png`
- `assets/project-images/pantry-pal-recipes.png`

Verified state:

- 6 content boxes
- 5 images

## Pay Equity Process Development Page

File:

`project-pay-equity.html`

Category:

Course Project

Original source:

- User-provided screenshot

Updated Google Doc source:

`https://docs.google.com/document/d/1qTc4aAimzMr_c8OxZAhlrAduVFL_jXkbVLY7m2OR4Hs/edit?usp=sharing`

The user asked to keep the top metrics as they already were:

- `10-week` business analysis project
- `4` team members
- `LDAHH` nonprofit client

The page was split into:

1. Overview
2. The Challenge
3. My Role
4. Project Approach
5. Outcomes
6. What this project strengthened

The user asked to remove "Recommended Portfolio Visuals" from the page.

The user also asked to reduce the font size for the metric boxes:

- 10-week
- business analysis project
- 4
- team members
- LDAHH
- nonprofit client

Current Pay Equity image assets:

- `assets/project-images/pay-equity-hr-workflow.png`
- `assets/project-images/pay-equity-hiring-workflow.png`
- `assets/project-images/pay-equity-performance-workflow.png`
- `assets/project-images/pay-equity-framework.png`
- `assets/project-images/pay-equity-timeline.png`
- `assets/project-images/pay-equity-point-method.png`
- `assets/project-images/pay-equity-regression.png`

Verified state:

- 6 content boxes
- 7 images
- 3 metric boxes

## Keys to Me Page

File:

`project-keys-to-me.html`

Category:

Course Project

Original source:

- User-provided screenshot

Updated Google Doc source:

`https://docs.google.com/document/d/17P2Vks37aJjjtgQeveElQzoQVccyMY4ZK__scNgJ2XQ/edit?usp=sharing`

The user asked to keep the top metrics as they currently were:

- `100+` students reached
- `1` workshop conducted
- `Positive` participant feedback

The page was split into:

1. Overview
2. The Challenge
3. My Role
4. Project Approach
5. Outcomes
6. What this project strengthened

Current image asset:

- `assets/project-images/keys-to-me-timeline.png`

Verified state:

- 6 content boxes
- 1 image
- 3 metric boxes

## AD-LIB Page

File:

`project-ad-lib.html`

Category:

Course Project

Original source:

- User-provided screenshot and text

Updated Google Doc source:

`https://docs.google.com/document/d/1mHPOAv8qjYExxU27uFOf_FCf4DiSo_HFRLfgy0PDozA/edit?usp=sharing`

The user asked to keep the top metrics as they currently were:

- `Team of 3` Mechatronics engineering
- `70%` reduction in manual processing time
- `e-Yantra` Ideas Competition selection

The page was split into:

1. Overview
2. The Challenge
3. My Role
4. Project Approach
5. Outcomes
6. What this project strengthened

Images were extracted from the Google Doc in document order and placed into the page flow.

Document image order:

1. Overall Concept of AD-LIB
2. GUI Algorithm Flowchart
3. Completely Assembled Conveyor Belt
4. Testing AD-LIB
5. Initialized GUI Screen in LabVIEW Environment

Current AD-LIB image assets:

- `assets/project-images/ad-lib-concept.png`
- `assets/project-images/ad-lib-gui-flowchart.png`
- `assets/project-images/ad-lib-conveyor.png`
- `assets/project-images/ad-lib-testing.png`
- `assets/project-images/ad-lib-labview-gui.png`

Verified state:

- 6 content boxes
- 5 images
- 3 metric boxes

## Resume Page

File:

`resume.html`

Current sections:

- Summary
- Experience
- Projects
- Education
- Skills
- Download PDF button
- Print button

Possible future task:

- Sync resume-page wording with the final homepage experience copy if needed.

## Figma Work

The user asked to push the portfolio to Figma and create a new Figma file in Disha Patel's team.

Figma file:

`https://www.figma.com/design/BOdFipGwfRscri7Mu0PHTZ`

Notes:

- The homepage was captured to Figma as editable frames.
- The Figma HTML-to-design capture flow was used.
- A Figma capture script may have been temporarily added to `index.html`.

Before deployment, check whether this capture script remains and remove it if present:

`<script src="https://mcp.figma.com/mcp/html-to-design/capture.js" async></script>`

## Local Preview

For reliable preview and external links, use a local server instead of opening files directly with `file://`.

Recommended preview command:

```bash
python3 -m http.server 8080
```

Then open:

```text
http://localhost:8080/index.html
http://localhost:8080/projects.html
http://localhost:8080/resume.html
```

Important note:

- `file://` works for basic viewing.
- External links can behave oddly from `file://`.
- `localhost:8080` is better for testing buttons and project links.

## Assets Added For Project Pages

Current project image assets:

- `assets/project-images/ad-lib-concept.png`
- `assets/project-images/ad-lib-conveyor.png`
- `assets/project-images/ad-lib-gui-flowchart.png`
- `assets/project-images/ad-lib-labview-gui.png`
- `assets/project-images/ad-lib-testing.png`
- `assets/project-images/keys-to-me-timeline.png`
- `assets/project-images/pantry-pal-discovery-1.png`
- `assets/project-images/pantry-pal-discovery-2.png`
- `assets/project-images/pantry-pal-overview.png`
- `assets/project-images/pantry-pal-recipes.png`
- `assets/project-images/pantry-pal-shopping.png`
- `assets/project-images/pay-equity-framework.png`
- `assets/project-images/pay-equity-hiring-workflow.png`
- `assets/project-images/pay-equity-hr-workflow.png`
- `assets/project-images/pay-equity-performance-workflow.png`
- `assets/project-images/pay-equity-point-method.png`
- `assets/project-images/pay-equity-regression.png`
- `assets/project-images/pay-equity-timeline.png`

## User Preferences Learned

- Avoid generic project manager portfolio design.
- Make the homepage visually attractive and personal.
- Use Disha's photo prominently.
- Use brighter brand colors.
- Keep About Me readable and less crowded.
- Avoid boxed About Me layout.
- Keep project detail wording from source documents as-is.
- Do not rewrite or summarize project document content unless asked.
- Preserve image order from documents.
- Keep metrics at the top of project pages.
- Keep "Skills Demonstrated" on the right side of project pages.
- Prefer cards similar to homepage cards on the Projects page.

## Suggested Follow-Ups

- Review `resume.html` for consistency with the final homepage experience wording.
- Remove the Figma capture script from `index.html` before publishing, if it remains.
- Test all project cards and external buttons through `http://localhost:8080`.
- Consider capturing Projects and Resume pages into Figma too, if the Figma file should include the full site.
- Clean up unused image versions in `assets/` once the final photo direction is confirmed.
- Prepare the site for deployment when the content and design are final.
