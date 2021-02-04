---

title: Docker Prune
permalink: docker-prune
excerpt_separator: "<!--more-->"
categories: 
tags: 

---
I started working through Josh Duffney's [become Ansible](https://becomeansible.com/) again, and I ran into some issues with the existing containers I created when I started. There is probably a better way to do this, but I found that you can clean up everything with one docker command.

```docker system prune -a```