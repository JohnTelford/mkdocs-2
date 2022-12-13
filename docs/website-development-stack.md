---
slug: webdevstack
title: Website Development Stack
---

!!! Abstract 

	The *Iterative Website Development Stack* illustrates how websites are developed and deployed to the Internet. It is web browser agnostic. What works for big screens, works for small screens.


--



``` mermaid
flowchart TB
	
	crepo --- cdn

	cdn --- net

	dev --- vsc 

	github --- crepo

	github --- cdn

	github --- net
	
	vsc --- lrepo
	
	net --- prevweb

	net --- proweb

	vsc --- net

	vsc --- mkd

	dev([Developers])

	cdn([CDN - Deploy Website to Web])

	crepo([Central Repository])

	github([GitHub]) 

	lrepo([Local Repository])

	mkd([Mkdocs Material - Static Site Generator])

	net([Internet]) 
	
	prevweb([Preview - Web Sites])

	proweb([Production - Web Site])

	vsc([VScode - Command and Control]) 

```

### Website Development Stack

!!! Overview

	The key *Iterative Development* technologies are [VScode](https://code.visualstudio.com/) for command and control, [MkDocs Marteral](https://squidfunk.github.io/mkdocs-material/) static site generator, [GitHub](git-github#github), [git](git-github#git), and a [Content Delivery Network (CDN)](https://en.wikipedia.org/wiki/Content_delivery_network) like [Cloudflare](https://www.cloudflare.com)

	- **Developers:**  
	
    	- **Local Repository**:  
			Each developer has their own "Local Repository" that is derived from the GitHub "Central Repository". It can be updated with the approved changes in the "Remote Repository."

		- **VScode**  
  
        	- Developers us VSCode as their Web Development Stack Command and Control center, and project editor

		- **MkDocs Material**  
  
    		- Is "Static Site Generator" that uses the "Local Repository" code to create a local website that may deployed as a "Preview"
  
  		-  **GitHub**
	
          	- The core technologies of Iterative Development are Git, GitHub central project repository controlled by the project gatekeeper, and a content delivery network, like Cloudflare, deploying private [Preview](preview.md) Internet websites, production websites, and individual team members private [Preview](preview.md) websites.
      		
      		- GitHub is a Distributed Version Control Systems enabling multiple teams to work separately on the same project without having an impact on the work of others. GitHub manages an online web hosted central project repository containing all project files. It is a unified source of truth. It helps teams collaborate and maintain the entire history of project file changes.

      		- The "Central Repository" is managed my a team member

				>It helps answer the questions for the lifetime of the project who changed what, where, when, and why?

  
  - Website" for stake holders. The same "MkDocs Static Site Generator" tools are used to create the "Production Website" by the "CDN - Deploy Website to Web"


- GitHub  
    - Central Repository.  
	
    	- The core technologies of Iterative Development are Git, GitHub central project repository controlled by the project gatekeeper, and a content delivery network, like Cloudflare, deploying private Preview Internet websites, production websites, and individual team members private Preview websites.
		
		- GitHub is a Distributed Version Control Systems enabling multiple teams to work separately on the same project without having an impact on the work of others. GitHub manages an online web hosted central project repository containing all project files. It is a unified source of truth. It helps teams collaborate and maintain the entire history of project file changes.

		- The "Central Repository" is managed my a team member

		>It helps answer the questions for the lifetime of the project who changed what, where, when, and why?



---



Team members use the Website Development Stack to develop and deploy websites to the Internet. 

There would be confusion and possible defects created if Team members were to directly make changes to the central project repository.  

A solution to this problem is to have one central repository controlled by a team member gatekeeper. Each team member [forks](git-github#fork) a copy of central project repository to their GetHub account and makes a [clone](glossary#clone) of it on their workstation.

---


- Each developer makes changes to their repository [clone](glossary#clone). They cannot directly make changes to the central repository.

	- Team members commit changes to their local repository clone

	- They may deploy their local repository to a private [Preview](preview.md) Internet website for stakeholders to see and give feedback. 

- The process is managed using [GitHub for Teams](https://github.com/team). When stakeholders determine developers changes, defect fixes, or new features are ready, a GitHub [Pull Request](git-github#pull-request) is made by developers to the central project repository. 

	- Project team members and the gatekeeper are notified by GitHub of the [Pull Request](git-github#pull-request) request. They may examine, comment on, suggest possible changes, and test the code. 

	- When the team agrees on committed developers changes, they are committed to the central project repository by the gatekeeper. This process is repeated for all developer committed changes. 

	- Iterations of the central project repository may be deployed by the gatekeeper to a private [Preview](preview.md)  for stakeholders viewing. 

- The next step is each developer [Pulls](git-github#pull) the central repository changes and commits them to their local repository copy of the central project. This process keeps team members up to date on changes.

- The central project repository may be deployed to the public Internet by the gatekeeper after stakeholders agree there have been sufficient development and testing iterations.

---

