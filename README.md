<p align="center">
  <img src="docs/images/Palks_Studio.png" alt="Palks Studio">
</p>

> 🇬🇧 English | [🇫🇷 Français](./README_FR.md)

![License](https://img.shields.io/badge/License-LICENSE.md-lightgreen.svg)

# Palks Studio — Professional Static Website Foundation

A complete static website base designed to serve as a clear, autonomous, and durable foundation  
for professional, technical, or editorial projects.

This foundation is intended for developers, integrators, or technical teams  
who want to retain full control over their code,  
without relying on heavy frameworks, CMSs, or third-party services.

### Public demos

English version:  

https://demo-en.palks-studio.com

French version:  

https://demo.palks-studio.com

---

## Project structure

```
/static_site_en/
│
├── index.html                        → Main homepage (project overview)
├── about.html                        → About page: philosophy and project vision
├── approach.html                     → Design approach and technical principles
├── resources.html                    → Resources, references and best practices
├── links.html                        → External links and complementary resources
├── contact.html                      → Contact page and communication details
├── terms-of-use.html                 → Terms of use and usage framework
├── legal-notice.html                 → Legal notice (mandatory information)
├── privacy-policy.html               → Privacy policy and data handling
│
├── assets/
│   ├── css/
│   │   └── style.css                 → Global stylesheet (editable or embeddable)
│   └── img/                          → Images, icons and visual assets
│
├── site.webmanifest                  → PWA manifest (optional, customizable)
│
├── robots.txt                        → Search engine crawling rules
├── sitemap.xml                       → Website sitemap for SEO indexing
│
├── README.md                         → Usage and customization documentation
└── LICENSE.md                        → Terms of use and legal framework
```


---

## Project purpose

This project provides a clean, readable, and maintainable HTML / CSS structure  
to quickly start a serious, well-structured, and scalable website.

It is not a fixed graphical theme,  
but a deliberately minimal technical base,
designed to be:  

- easy to understand  
- easy to customize  
- extensible without unnecessary complexity  
- maintainable over the long term

---

## Foundation content

The project includes, among other things:  

- Multiple complete and structured HTML pages  
- A clear and consistent file architecture  
- Organized, commented, and modular CSS  
- A responsive layout adapted to desktop, tablet, and mobile screens  
- A heading hierarchy following SEO best practices  
- ARIA attributes and an accessible structure  
- A ready-to-use `robots.txt`  
- A functional `sitemap.xml`  
- Code comments serving as customization markers  
- Usage documentation  
- A clear usage license

No external dependencies are required.

---

## Included pages

The foundation notably includes the following pages:  

- Home  
- About  
- Approach  
- Resources  
- Links  
- Contact  
- Terms of use  
- Legal notice  
- Privacy policy

Each page includes:  

- dedicated SEO tags  
- a consistent structure  
- generic content ready to be adapted

---

## Accessibility

Special attention has been paid to accessibility:  

- Proper semantic hierarchy (`h1` → `h2` → `h3`)  
- HTML structure readable by screen readers  
- Visually hidden text (`visually-hidden`) when relevant  
- ARIA attributes used sparingly and appropriately

This foundation provides a solid base for projects  
that aim to integrate accessibility from the design stage.

---

## SEO

The project is optimized for search engine visibility:  

- `title` and `meta description` tags per page  
- Open Graph and Twitter Cards  
- Canonical URLs  
- Sitemap  
- Robots.txt

The provided content is intentionally generic  
and must be customized before any production deployment.

---

## Quick customization

To adapt the site to your project:  

Replace the logo in `assets/img/`  
Edit the text content in the HTML files  
Adjust colors in `:root`  
Extend or adapt the existing CSS  
Add JavaScript if needed

The CSS can be:  

embedded directly into the pages  
or kept in `assets/css/style.css`

The comments included in the code act as markers  
and make onboarding easier.

---

© Palks Studio — see LICENSE.md  
https://palks-studio.com
