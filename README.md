# JupyterHub 2016 workshop

[![Join the chat at https://gitter.im/jupyterhub/jupyterhub-2016-workshop](https://badges.gitter.im/jupyterhub/jupyterhub-2016-workshop.svg)](https://gitter.im/jupyter/jupyterhub-2016-workshop?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Materials for an online workshop around JupyterHub use cases, held July 22nd, 2016.

- [Agenda with links to slides](#agenda)
- Video of the meeting: [Part I](https://www.youtube.com/watch?v=VnMSjR5IoS8) and [Part II](https://www.youtube.com/watch?v=6p1xhi0P5dg)
- [Meeting notes](https://jupyter.hackpad.com/JupyterHub-Mini-Workshop-Notes-QquOAlaWsVs)
- [Cheat sheet for JupyterHub](jhubcheatsheet.md)
- [Call Logistics](#call-logistics)

The purpose of the workshop is to provide a collection of short talks highlighting various deployment use cases and tools for JupyterHub, coming both from regulars of the project and the broader community.  JupyterHub is a very flexible tool and there are multiple, different, valid use cases that require a [variety of supporting tools and configurations](jhubcheatsheet.md), ranging from a local, single-machine deployment to complex scenarios in the cloud or HPC environments that orchestrate assemblies of servers.

Given this flexibility and variety, we thought we should find a way to help both:

- users who may want to figure out how to assemble the available tools to solve their own problems,

- the development team, who needs to understand what are the common and recurring pain points to drive the system forward.

It seemed that a very informal, lightweight collection of talks by both members of the Jupyter team and community participants who have already built tools or deployed the system for their needs, could provide this kind of "gallery" overview.

## Agenda

This is our current agenda of lightning talks (only the first is a longer one by @minrk outlining the overall system design, so that all other speakers can skip that). All times Pacific:

|  #  | Time slot | Speaker | Topic |
| --- | --- | --- | --- |
|1. |  9:00 - 9:30am | Min Ragan-Kelley (Simula & Jupyter Team). | [JupyterHub: Deploying Jupyter Notebooks for Students and Researchers](minrk-jupyterhub.pdf) - System architecture, options, main plugins, etc. |
|2. |  9:30 - 9:45. | Brian Granger (CalPoly and Jupyter Team). | [Installation and deployment using ansible. Focus: small/medium groups of mostly trusted users for non-dev ops folks](GrangerJupyterHubDeployment.pdf) |
|3. |  9:45 - 10:00. | Jess Hamrick (UC Berkeley and Jupyter Team). | [JupyterHub in Education: scaling with Docker and integrating with nbgrader](jhamrick-scaling-and-services.pdf) |
|4. | 10:00 - 10:10. | Ryan Lovett (UC Berkeley). | [UC Berkeley Data8](ryanlovett-ucb-data8.pdf) |
|5. | 10:10 - 10:20. | Shreyas Cholia (LBNL/NERSC). | [Driving Supercomputers with Jupyterhub - NERSC experiences on Cori.](Shreyas-JupyterhubWorkshopNERSC.pdf) |
|6. | 10:20 - 10:30. | Open slot - schedule slack |  |
|7. | **10:30 - 10:40.** | **Break**  |  |
|8. | 10:40 - 10:50. | Michael Milligan (Minnesota Supercomputing Institute) | [JupyterHub at MSI: Building an Interactive HPC Gateway](milligan-umn-hpcgateway.pdf) |
|9. | 10:50 - 11:00. | Ian Allison, James Colliander and Michael Lamoureux (PIMS). | [JupyterHub using docker and flocker on an Openstack cluster via ansible + vagrant.](IanAllison-JupyterHubPIMS.pdf) |
|10. | 11 - 11:10. | Mike Polino & Alec Aivazis (DataScience, Inc). | [Lessons in transitioning a data science team to JupyterHub](https://github.com/mplno/jupyterhub-2016-workshop/blob/master/mike_polino-transitioning_to_jupyterhub.pdf). |
|11. | 11:10 - 11:20. | Jonathon Anderson (CU Boulder). | [JupyterHub deployment at CU (workshop notes)](https://github.com/jupyterhub/jupyterhub-2016-workshop/blob/cu/cu-deployment.mdwn) [JupyterHub deployment at CU (XSEDE16)](https://github.com/jupyterhub/jupyterhub-2016-workshop/blob/cu/cu-deployment-xsede.pdf) |
|12. | 11:20 - 11:30. | Cory Gwin (Berkeley Applied Analytics) | [Building a Custom Jupyterhub OAuthenticator.](baa_jupyter_oauth.pdf) |
|13. | 11:30-12. | **Open Q&A** for questions from the audience. | |


## Call logistics

We'll hold the meeting using [Zoom.us](http://zoom.us), we recommend running a test on your system if you're going to be speaking before the presentation.

The meeting link [is here](https://lbnl.zoom.us/j/162513876), full details  below for easy copy/pasting:

```
Join from PC, Mac, Linux, iOS or Android: https://lbnl.zoom.us/j/162513876

Or iPhone one-tap (US Toll):  +1 408 638 0968, 162513876# or +1 646 558 8656, 162513876#

Or Telephone:
    Dial: +1 408 638 0968 (US Toll) or +1 646 558 8656 (US Toll)
    +1 855 880 1246 (US Toll Free)
    +1 877 369 0926 (US Toll Free)
    Meeting ID: 162 513 876
    International numbers available: https://lbnl.zoom.us/zoomconference?m=yR9NpqFr_Gbt3NYLqB3mYDaypdVGepOG


Or a H.323/SIP room system:
    H.323: 162.255.37.11 (US West) or 162.255.36.11 (US East)
    Meeting ID: 162 513 876

    SIP: 162513876@zoomcrc.com
```


