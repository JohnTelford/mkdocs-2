---
title: Overview
---

!!! Abstract

	This website discusses optimizing website project life time costs. It describes using a static site generator for developing websites. It is based on *Iterative Development* and *Web Component Technologies*.

	The basic idea of *Iterative Development* is to develop websites through repeated cycles (iterative) and in smaller portions at a time (incremental), enabling iterative development teams to take advantage of what was learned during development of earlier features or versions of the system. 

	Iterative web development teams working together help optimizing website costs and lowering the difficulties creating websites.

	This is done by developers working on website features, fixes, or testing, and deploying [Private](deploy#preview) Internet websites with their changes, without disturbing other developers work or the website production version. This enables the stakeholders to monitor progress and quickly give feedback, speeding up the development process.

---


## Steps

- Teams Prerequisites
	- Define
	- Design
	- Develop
	- Maintain



---

The core of Iterative Development is the [GitHub](git-github#gitHub) project central repository controlled by a team member gatekeeper.

[GitHub](git-github#gitHub) is a Distributed Version Control Systems  enabling multiple team members to work separately and deploy their work to a private Internet websites for review, without having an impact on the work of others. [GitHub](git-github#gitHub) manages a central online web hosted project repository containing all project files. It is a unified source of truth. It helps teams collaborate and maintain the entire history of project file changes and team members comments.

> During the lifetime of the project, it helps answer the questions *who changed what, where, when, and why?* 

---

Deploy working iterations of a software development solutions involving stakeholders at all phases of the development process

Each team member make changes to their local copy of the project repository, they deploy a private [Preview](deploy#preview)  Internet website for stakeholders to view and give feedback.

Producing website functional iterations, it can tested, examined, and adjusted on an ongoing basis.

The repository guardian and other team members evaluate and approve team members change requests to the central repository. Added change requests are deployed to a private preview Internet website for stakeholders to preview and give feedback. This process continues until stakeholders agree the website is ready for a public deployment.

This process is more efficient than creating a website and hoping it meets the needs of stakeholders, and finding out the website needs to be redesign from the ground up because one or more critical requirements were overlooked.

---

## Difficulties

Creating and maintaining websites that meet users needs are difficult, complex, and time consuming.

When website development defects are mitigated early in development, life time website costs are lower.

### Slow

The Google [PageSpeed Insights](https://pagespeed.web.dev/) website reports on the performance of websites for both mobile and desktop devices, and provides suggestions on how pages may be improved.

Google reports mobile website pages load within 22 seconds on average. However, 53 percent of mobile users will leave a page that takes longer than 3 seconds to load.

### Content

People visit websites for content. They have little interest in how the content is created or how it gets to their screen. Everyone wants websites pages to load quickly and conforming to their screen size. The website look and feel, users experience, functionality, needs to be consistent and complement the content.

---

## Iterative Development Teams


Website development teams working together deliver their work to other teams during the website life time.

The slightest errors or security issues will require remediations sometime during the life time of the website.

![iterativedev](/img/iterativedev.png)

**Iterative website development Teams**

Iterative website development enables the *Define, Design, Develop, Deploy and Maintain* team members to be operational at the same time creating, testing, and remediating defects.

---

## Defect Remediation Costs

The highest cost over the life time of website projects is remediating defects.

Content and software defects cost less when found early, as this chart shows:

![bugFixChart](/img/bugFixChart.jpg)

**Defect Remediation Costs**

The early defect detection mechanisms built into iterative development and a static site generator are:

- [VScode](developmenttools#vscode) editor tool extensions continually check for syntax and other errors

- Fast refresh live-editing quickly showing changes and any runtime errors while typing

- Team members deploy their copy of the project repository with their changes, to private websites where stakeholders can see them and give feedback.  See [Preview Deployments](glossary#preview-deployments)

---

## Minimum Viable Product

The first goal of website development projects is a *Minimum Viable Product*. 

It is a way to understand whether the website project idea will work or not. It is a stage in website development where the *must* features are implemented and ready to test with end-users. It gives feedback about the positive aspects and shortcomings.

The next steps are adding the *want* features, until stakeholders agree the website is production quality and ready to be deployment.

---

