# Richard Tran · Portfolio

Professional portfolio of **Richard Tran**, AI / Machine Learning Engineer. A single-page site covering his profile, core competencies, domain alignment, experience, education and certifications, built to be hosted on GitHub Pages with no build step.

## Summary

Richard is an AI/ML engineer with experience across applied engineering, technology consulting and academic research. He currently designs, builds and deploys machine learning and generative AI software at **Probity Inc.**, following ML engineering roles at **Capital One** and **Booz Allen Hamilton** (Consultant, then Senior Consultant in the Technical Excellence – ML Data Scientist Program) and an ML internship at **Shield AI**, where he built simulation tooling for a deep reinforcement learning agent.

His research background is in bias mitigation for clinical NLP at **Virginia Tech**: a variational autoencoder approach to debiasing clinical notes, bias analysis of ClinicalBERT, PySpark and Spark NLP Healthcare pipelines, and SQL analytics on the MIMIC-III/IV datasets on BigQuery. He also spent two years as a graduate and undergraduate teaching assistant covering Python, Java, computer organization and computing ethics.

- **Education:** B.S. and M.Eng. in Computer Science, Virginia Tech; Doctor of Engineering in Artificial Intelligence, Penn State (in progress)
- **Certifications:** AWS Certified Machine Learning – Specialty · Google Cloud Professional Machine Learning Engineer · Microsoft Azure AI Fundamentals · Databricks Generative AI Fundamentals · Generative AI with Large Language Models
- **Core skills:** Machine Learning · Deep Learning · Generative AI & LLMs · Python · PySpark · SQL / BigQuery · AWS · GCP · Azure · Docker
- **Outside engineering:** an independent creative practice in 2D & 3D art (GIMP, Inkscape, Krita, Blender), with personal and commissioned work, plus hands-on experience in game development, video production and audio production

## What's on the page

| Section | Contents |
| --- | --- |
| Profile | Headline, summary and key facts |
| Core competencies | Six competency areas plus a skills list |
| Domain alignment | How his background maps to specialized technical domains, tiered as direct professional match, independent experience and adjacent experience |
| Experience | Probity Inc., Capital One, Booz Allen Hamilton, Shield AI, Virginia Tech |
| Education | Penn State and Virginia Tech degrees |
| Certifications & training | Cloud ML credentials, generative AI and consulting programs |

## Tech notes

- One file, `index.html`: HTML, CSS and JavaScript are inline. No framework, no dependencies to install.
- Typography loads from Google Fonts (Sora, IBM Plex Sans, IBM Plex Mono) and falls back to system fonts if offline.
- Follows the visitor's light or dark system theme automatically.
- Responsive layout: sticky identity rail beside the content on desktop, single column on phones. Includes a print stylesheet.

## Deploy to GitHub Pages

1. Create a repository, for example `portfolio`, or `<username>.github.io` for a user site served at the root domain.
2. Add `index.html` and this `README.md` to the repository root, commit and push to `main`.
3. In the repository go to **Settings → Pages**. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then save.
4. GitHub builds the site within a minute or two. It is served at `https://<username>.github.io/<repository>/` (or `https://<username>.github.io/` for a user site).
5. Optional: add a custom domain under the same Pages settings; GitHub creates the `CNAME` file for you.

## Run locally

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Updating content

All content lives in `index.html`. Each section has an id you can jump to in the editor: `#profile`, `#competencies`, `#domains`, `#experience`, `#education`, `#certifications`.

- To add a role, copy an existing `<li class="job">` block in the Experience section and edit the dates, employer, title and bullets.
- To add a certification, copy one `<li>` in the Certifications list and change the badge text, name and issuer.
- Contact details appear twice: in the side rail near the top and in the footer.

## Contact

- Email: richard.tran.csphd@outlook.com
- LinkedIn: [linkedin.com/in/richardtran8](https://linkedin.com/in/richardtran8)

*Last updated November 2026.*
