Hi,

I'm Lukas (he/him), developer 💻 and scout ⚜️ from Germany.

I've studied electrical engineering at the DHBW in Stuttgart while working for automation and SCADA teams at [Siemens](Siemens.com) and worked as an Industrial IOT Engineer for  [KUKA](kuka.com).

Currently, I am 
- finishing my computer science masters degree in Heidelberg
- coordinating programs for scouts between 16 and 21 years old
- organizing a big scout camp planned for easter 2022 with, hopefully, 1500 participants

I enjoy creating tools that solve daily real-world problems and automate work away.

At the moment I am using mostly [**Python 3**](python.org) and [**PostgreSQL**](postgresql.com) to solve problems and bring them to production with [**Ansible**](ansible.com) and/or [**Docker**](docker.com). 
This toolset has served me well for the challenges I've faced until now.

Nevertheless, I would like to get some experience with tools like:
- AWS, especially the serverless parts like Lambda and DynamoDB
- Kubernetes 
- Go
- Typescript
but had no problem that would require learning these technologies. Until now...

Given the proper challenge, I am very self-driven and able to pick up new things easily. Nevertheless, I am looking for a culture centered more around guidance and mentorship to cultivate my abilities and learn from others for my next steps.

These are some of my projects you might want to look at:

## [HÜB](github.com/iued-heidelberg/hueb)
The "Heidelberger Übersetzungs Bibliographie" is a project I've worked on between 02.2020 and 08.2021 for a student job at the University of Heidelberg.
Its purpose is to create a comprehensive collection of non-fictionary texts written in English, Dutch, Latin, and Romanesque languages and their translations into German.

As the only developer, it was my responsibility to create an application that enables the team as fast as possible. 

I delivered an initial data model, and user interface quickly so that my colleagues could start entering data as fast as possible. This initial implementation evolved based on the user's feedback and changing requirements; for example, entry versioning and a review system were added later by me.

I've set up a CI/CD pipeline based upon [**Github Actions**](https://github.com/features/actions), [**Docker**, **Docker-Compose**](docker.com) and **[Ansible](ansible.com)** with a staging and production environment to get a reproducible deployment process for myself and following developers. Visibility into the system was ensured by using [Honeycomb.io](honeycomb.io) and [Sentry](sentry.io).

I've cleaned up data dumps from previous projects and provided them to the team for reference and integration into the primary dataset later on.

The technology used for the application is [**Django**](djangoproject.com), [**Postgres**](postgresql.com),  [**TailwindCSS**](tailwindcss.com) and [**Alpine.js**](alpinejs.com).

## [rosscorona](github.com/bockstaller/rosscorona)
The "Rosskur" is an annual scouting event, where ~300 scouts participate in a 24-hour orientation hike. We had to change the event mode due to Covid-19 and created the "Rosskur in a box". Teams would receive a box with materials and a personalized route around their home. I set up a **Jupyter** notebook to create the maps handed out.

It uses the [openrouteservice.org](openrouteservice.org) API to create a hiking trip, selects appropriate POIs along the way to be designated as destinations, verifies that the direct route between the destinations results in a distance within the desired range, and uses an online service to create the PDF maps.

Using this tool saved a lot of our volunteer time and paid off even the initial time investment, as we were forced to organize this event twice.

## [europarl-crawler](github.com/bockstaller/europarl-crawler)
This crawler scapes the session protocols published by the European Parliament, post-processes them, and stores their content in [Elasticsearch](elastic.co).
I've developed it for a practical at my University, and I used this opportunity to experiment with pythons multiprocessing and software architecture in general. It is a bit overbuilt for the job at hand, but I learned a lot from it. 

I've followed up with [european-protocols](github.com/bockstaller/european-protocols). A heavily slimmed-down version inspired by Simon Willison's [git scraping approach](https://simonwillison.net/2020/Oct/9/git-scraping/).
This project consists of two [**Github Actions**](https://github.com/features/actions) scraping the protocols and committing them directly into the repository.

## [Fixed date sepa payments for pretix](https://github.com/pretix/pretix-sepadebit/pull/19)
I operate a [pretix](pretix.eu) instance for my scouting association. We needed to execute SEPA debit payments only after a given date and not x-days after the payment.
I drafted a [PR](https://github.com/pretix/pretix-sepadebit/pull/19) to the respective plug-in and implemented the functionality together with the project's maintainer. 

## [ISE 2019](github.com/bockstaller/ise_2019_deployment)
Another university project. Here I was responsible for setting up a developer, staging, and production environment for a team of 6 people across Windows, macOS, and Linux. 
I made heavy use of [**Docker**, **Docker-Compose**](docker.com) and [Atlassian Bamboo](https://www.atlassian.com/de/software/bamboo) to provide a **CI/CD** pipeline for the team and local, easy to set up development environments.


