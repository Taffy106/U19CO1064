# COEN 554 Technical Report Notes

Use this as the starting structure for the required technical report.

## 1. Visual Design Rationale
Explain:
- Why the layout was selected.
- How visual hierarchy is created.
- How typography supports readability.
- How contrast and spacing are used.
- How the layout adapts to mobile devices.

## 2. JSON Data Structure
Explain that `data/data.json` separates structured content from page presentation.

Current entities include:
- person
- education
- skills
- projects

For each project, the schema includes:
- id
- title
- date
- category
- description
- technologies
- image_url

## 3. JSON-LD
Explain that JSON-LD is embedded in each page's `<head>` to describe page/person metadata using Schema.org vocabulary.

## 4. HTTP/HTTPS and MIME Types
Explain how a web server delivers:
- HTML/XHTML as `text/html`
- CSS as `text/css`
- JSON as `application/json`

Explain that HTTP/HTTPS provides the protocol through which browsers request and receive these static resources.

## 5. CMS Comparative Evaluation
The exam requires a 300–500 word technical evaluation comparing the manual XHTML/CSS/JSON architecture with a CMS such as WordPress or a web framework.

Discuss:
- Team size
- Content update frequency
- Non-technical editors
- Security and maintenance
- Hosting/deployment
- Performance
- Scalability

Do not submit these notes as the final report without expanding them into the required 300–500 word evaluation.
