#DevOps Agile Geek Week

>Software & Infra do not scale. Software & Infra **teams** do not scale. 
>Architecture should be as much about enabling small teams to work on small components as the technical requirements of the software.

---

#What You'll Learn

* How to 'do' Agile
* How *not* to 'do' Agile
* Agile/DevOps related tools
* Container Basics
* IaaS and PaaS basics
* How to talk about this in the real world
* How EMC can help customers

---

#Themes

- Automation
- Text Configuration (JSON/YAML)
  - machine parseable, human readable
- Everything in Git
- Local Tools = Production Environments - Scale
- Free/Open Source Tools

---

#Agenda

- **Day 1**: Introduction, Agile, DevOps and Tools
- **Day 2**: Version Control, Git and 12Factor
  - *Lab for Git*
- **Day 3**: Containers and Cloud Foundry
  - *Lab for Docker*
  - *Lab for Cloud Foundry*
- **Day 4**: CI/CD, PCF Components and Value
  - *Unconference*
- **Day 5**: What can I sell? How do I sell it?
  - *Unconference*
  - *Retrospective (Retro)*

---

#Tools

[Git](https://help.github.com/articles/set-up-git/) 

[CloudFoundry CLI](http://docs.cloudfoundry.org/devguide/installcf/) 

[Docker for Mac](https://docs.docker.com/engine/installation/mac/#docker-for-mac) or [Docker for Windows](https://docs.docker.com/engine/installation/windows/#docker-for-windows) 

[Slack](http://slack.com)

[PCF Dev](https://docs.pivotal.io/pcf-dev/index.html)

---

#Git

A distributed version control system, where every user has a complete and full copy of the source code.  

If you can't check it in, you can't keep track of it, so you can't version it, so you can't automate it.

*Everything* belongs in source code control, and git is the standard in 3rd platform.

Other possible options: subversion (svn), mercurial (hg), Perforce (p4), ClearCase (cc).

---

#GitHub?

A freemium service to host Git repositories (repos). Public repos are free, private ones are still cheap.

Most open source projects are hosted and collaborated on here.

```
> If you're not on GitHub you don't exists.
-- Friendly developer
```
---

#CloudFoundry CLI

A command line tool for managing CloudFoundry applications and related services.  Again, all CLI so that it can be scripted and automated.

Simple commands to deploy, scale and monitor applications.

---

#PCF Dev

A portable and lightweight Pivotal Cloud Foundry (PCF) installation that runs as a single virtual machine (VM) on your workstation leveraging Virtualbox. 
PCF Dev is intended for application developers (or yourself!!) who want to develop and debug their applications locally on a PCF deployments avoiding a big/full PCF installation (that requires more hardware/effort).


PCF Dev includes Pivotal Elastic Runtime, Redis, RabbitMQ, and MySQL. It also supports all cf CLI functionality.

It is also possible to deploy Docker containers via PCF Dev.

Alternatives: use Pivotal Web Services (A PCF installation running in AWS)

---

#Slack

Think of it like IRC on 'roids'. Team chat with multiple channels, integrations with services like GitHub, Trello, etc.

Often used to significantly replace email within Agile teams.


![Alt text](/devops-geekweek/images/Slack.png "Slack")

---

#Trello

An online 'Kanban' board to track tasks and completion.

Very simple and user friendly, can be used for anything from sprint management to planning a birthday party.
