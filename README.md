# samseaver.github.io

Personal academic website of **Samuel M. D. Seaver, PhD** — computational biologist.
Finding signals in noisy systems, and connecting data and tools across networks of every
scale: molecular, metabolic, regulatory, social.

🌐 **Live site:** https://samseaver.github.io

## About

Builder and first/senior author of the open-source metabolic-modeling resources the plant-
and microbial-systems-biology community relies on — the **ModelSEED Biochemistry Database**
and **PlantSEED** — and a core member of the DOE **KBase** plants team. Current work adopts
machine learning as a tool to make genome-scale metabolic models predictive from multi-omics
data (a flexible neural-mechanistic hybrid approach).

- **Google Scholar:** https://scholar.google.com/citations?user=DMaSBiAAAAAJ
- **ORCID:** https://orcid.org/0000-0002-7674-5194
- **GitHub:** https://github.com/samseaver
- **LinkedIn:** https://www.linkedin.com/in/sam-seaver/

## Tech

Built with [al-folio](https://github.com/alshedivat/al-folio) (a Jekyll theme for academics),
deployed to GitHub Pages via the repository's GitHub Actions workflow (`.github/workflows/deploy.yml`),
which builds the site and publishes it to the `gh-pages` branch.

## Local development

```bash
bundle install
bundle exec jekyll serve
# open http://localhost:4000
```

## Content

| Area          | Source                                      |
| ------------- | ------------------------------------------- |
| Homepage/bio  | `_pages/about.md`                           |
| Publications  | `_bibliography/papers.bib`                  |
| Projects      | `_projects/*.md`                            |
| CV            | `_pages/cv.md` → `assets/pdf/Seaver_CV.pdf` |
| News          | `_news/*.md`                                |
| Profile photo | `assets/img/prof_pic.jpg`                   |
| Social links  | `_data/socials.yml`                         |

---

Theme: [al-folio](https://github.com/alshedivat/al-folio) · Hosted on
[GitHub Pages](https://pages.github.com/).
