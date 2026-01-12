---
layout: lesson
root: .  # Is the only page that doesn't follow the pattern /:path/index.html
permalink: index.html  # Is the only page that doesn't follow the pattern /:path/index.html
venue: "LHC Physics Center, Fermi National Accelerator Laboratory"        # brief name of the institution that hosts the workshop without address (e.g., "Euphoric State University")
address: "In Person"      # full street address of workshop (e.g., "Room A, 123 Forth Street, Blimingen, Euphoria"), videoconferencing URL, or 'online'
country: "us"      # lowercase two-letter ISO country code such as "fr" (see https://en.wikipedia.org/wiki/ISO_3166-1#Current_codes) for the institution that hosts the workshop
language: "en"     # lowercase two-letter ISO language code such as "fr" (see https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) for the
latitude: "41.842258"        # decimal latitude of workshop venue (use https://www.latlong.net/)
longitude: "-88.245781"       # decimal longitude of the workshop venue (use https://www.latlong.net)
humandate: "Synchronously January, 2023"    # human-readable dates for the workshop (e.g., "Feb 17-18, 2020")
humantime: "24/7"    # human-readable times for the workshop (e.g., "9:00 am - 4:30 pm")
startdate: 2026-01-12 # machine-readable start date for the workshop in YYYY-MM-DD format like 2015-01-01
enddate: 2026-01-16   # machine-readable end date for the workshop in YYYY-MM-DD format like 2015-01-02
email: ["emery.nibigira@cern.ch"]
---

![CMS Detector Slice](https://cmsexperiment.web.cern.ch/sites/cmsexperiment.web.cern.ch/files/detectoroverview.gif){:width="50%"}

## Welcome to the CMS Data Analysis School 2026 Tracking and Vertexing Short Exercise!

We will present an introduction to using tracks for analyses in the era of **large pile-up** (many primary vertices). Our exercises will all use real data and will familiarize you with the following techniques:

> ## Exercise Goals
> - Extracting **basic track parameters** and reconstructing invariant masses from tracks in CMSSW. Tracks are the detector entities that are closest to the four-vectors of particles: the momentum of a track is nearly the momentum of the charged particle itself.
> - Cleaning **sets of tracks for analysis**. We will use filters to eliminate bad tracks and discuss sources of tracking uncertainties. These filters are provided by the tracking POG (Physics Object Group)
> - Extracting **basic parameters of primary vertices**. In this high-luminosity era, it is not uncommon for a single event to contain as many as thirty to fifty independent collisions. For most analyses, only one is relevant, and it can usually be identified by its tracks.
> - Using tracks to measure from data and Monte Carlo (MC) samples the **tracking efficiency** by using tag and probe method via dimuon resonances. It can be extended to measure the efficiency of any selection of muons (trigger, isolation, identification) and derive scale factors from MC.
{: .checklist}

> ## Prerequisites
> **Before going any further, please complete the [CMS DAS Pre-Exercises](https://fnallpc.github.io/cms-das-pre-exercises/) and then follow the instructions on the [setup page](setup.md).**
{: .prereq}


> ## Facilitators
> #### Lead Contact
> * [Yanxi Gu](#facilitators), University of California, San Diego ([yag002@ucsd.edi](mailto:yag002@ucsd.edu))
>  
> #### All Facilitators

> * [Isik Gokcen Karslioglu](#facilitators), Purdue University, West Lafayette (ikarslio@purdue.edu)
> * [Richa Sharma](#facilitators), University of Puerto Rico, Mayaguez ([richa.sharma@cern.ch](mailto:richa.sharma@cern.ch)) 

{: .testimonial}


> ## Mattermost Chat
> **The [Tracking and Vertexing Short Exercise](https://mattermost.web.cern.ch/cmsdaslpc2025/channels/shortextrackingvertexing) channel will be available once you join the [CMSDAS@LPC2025](https://mattermost.web.cern.ch/cmsdaslpc2025/channels/town-square) team. Direction for how to join this Mattermost chat team can be found on the <a href="setup.html">setup</a> page.**
{: .discussion}

> ## Introduction Slides
> **At the beginning of this short exercise an introduction will be done based on <a href="files/CMSDASCERN2023_TrackingVertexingExercise_Introduction.pdf">these slides</a>.**
{: .callout}
{% comment %} This is a comment in Liquid {% endcomment %}

{% include links.md %}
