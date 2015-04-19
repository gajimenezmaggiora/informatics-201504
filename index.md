---
title       : Informatics Core Update
subtitle    : Washington, DC
author      : Gustavo Jimenez-Maggiora, MBA
job         : Director, Informatics Core
framework   : revealjs        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft, selfcontained}
knit        : slidify::knit2slides
---

# Informatics Core

Gustavo Jimenez-Maggiora, MBA

Washington, DC

April 19th, 2015

---

# Updates

---

## New Data Portals

<table class="table-condensed center-table">
<thead>
<tr>
<th>Portal</th>
<th>Status</th>
</tr>
</thead><tbody>
<tr>
<td>FYN</td>
<td><span class="text-success">Launched!!!</span></td>
</tr>
<tr>
<td>ADNID</td>
<td><span class="text-success">Launched!!!</span></td>
</tr>
<tr>
<td>CCF-RAS</td>
<td><span class="text-success">Launched!!!</span></td>
</tr>
<tr>
<td>LEARN</td>
<td><span class="text-warning">May, 2015</span></td>
</tr>
<tr>
<td>TCAD Extension</td>
<td><span class="text-warning">May, 2015</span></td>
</tr>
<tr>
<td>EX</td>
<td>In progress...</td>
</tr>
<tr>
<td>CSF 1</td>
<td>In progress...</td>
</tr>
</tbody></table>

---

## Amazon Web Services (AWS)

* We have migrated the <span class="text-success underline">majority</span> of our Data Portals to AWS
* Remaining Data Portals:
    * A4
    * TCAD

---

## Application Improvements

* Based on user feedback, we have made improvements to the following apps:
    * Images
    * IP Tracking
    * MedDRA
    * Queries

---

# Images

---

## Improvements

* Multiple modalities
* Study-specific, multi-user collaborative workflows
* Traceability and transparency
* Tagging capabilities allow users to flexibly organize and search for images
* Manage processed or derived images
    * Link derived images to source images to establish provenance across modalities
    * Visualize and navigate using inheritance trees
    * Multi-file upload, linking and tagging
* Improved reporting and tracking of workflow inventory and performance metrics

--- &vertical

Images - Menu

![images-menu](./images/images-menu.png)

***

Images - Seach

![images-search](./images/images-search.png)

***

Images - Batch Upload, Linking and Tagging

![images-batch-upload](./images/images-batch-upload.png)

***

Images - Amyloid Pet Workflow

![fyn-amypet-flow](./images/fyn-amypet-flow.jpg)

***

Images - Hierarchy

![images-tree](./images/images-tree.png)

***

Images - Metrics

![images-metrics](./images/images-metrics.png)

---

## Release Schedule

* <span class="text-success">Launched on FYN</span>
* Plan to upgrade in the next 6 months:
    * A4 / LEARN
    * INI
    * TCAD

---

# IP Tracking

---

## Improvements
* Cleaner, more intuitive interface
    * Configurable data per menu
    * Smart action links
    * Additional details…
* Advanced filters
* Color statuses
* New “Cart” interface
* Automated drug ordering
* Additional new features based on user feedback
    * Download CSV
    * Status report (interactive chart report)

--- &vertical

IPT - Menu

![ipt-menu](./images/ipt-menu.png)

***

IPT - Cart

![ipt-cart](./images/ipt-cart.png)

***

IPT - Status Report

![ipt-status-report](./images/ipt-status-report.png)

---

## Release Schedule
* <span class="text-success">Launched on FYN</span>
* TCAD - May, 2015
* INI - ?

---

# MedDRA

---

## Improvements
* Support for MedDRA updates
* Text-based search and filtering
* Improved batch actions (coding and confirmation)

--- &vertical

MedDRA - Menu

![meddra-menu](./images/meddra-menu.png)

***

MedDRA - Batch Coding
![meddra-coding](./images/meddra-coding.png)

---

## Release Schedule
* <span class="text-success">Launched on all active ADCS data portals!!!</span>

---

# Queries

---

## Improvements
* Usability and Layout
    * All query related-information is visible
    * Modal vs drawer
* More filters
  * Created-by
  * Touched-by
  * Query Age
  * Tags
* Saved searches
* Tagging
* Starring - follow a query

--- &vertical

Queries - Menu

![queries-menu](./images/queries-menu.png)

***

Queries - Search

![queries-search](./images/queries-search.png)

---

## Release Schedule
* <span class="text-success">Launched on FYN and CCF-RAS</span>
* Plan to upgrade in the next 6 months:
    * A4 / LEARN
    * INI
    * TCAD

---

How do we ensure that these changes are validated?

---

# Validation

---

<blockquote>
<p>When any change (even a small change) is made to the software, the validation status of the software needs to be re-established.</p>
<small>General Principles of Software validation; Final Guidance for Industry and FDA Staff</small>
</blockquote>

---

## Initial Validation

* Completed in December 2012
* Focused on Core Modules and Functionality:
    * Electronic Data Capture (EDC)
    * Queries
    * Audit Trail
    * Data Export
    * Document Repository
    * Authentication and Authorization
    * Meta-data Management

---

## Initial Validation

* Initial timeline: 3 months
* Actual time to completion: 9 months
* Traditional approach
    * Manual test execution
    * Paper-based
* Required 50k+ person hours

---

## Initial Validation

* Observations:
    * Traditional approach is resource intensive and difficult to replicate
    * Our user community demands constant innovation
    * Our business requirements are evolving and study-specific
    * By design, we have a key dependency on web browsers, which are rapidly changing

---

![browser-timeline](./images/Timeline_of_web_browsers.svg)

["Timeline of web browsers" by I, ADeveria. Licensed under CC BY-SA 3.0 via Wikimedia Commons](http://commons.wikimedia.org/wiki/File:Timeline_of_web_browsers.svg#/media/File:Timeline_of_web_browsers.svg)

---
## Rapid Change in Browsers

* Firefox and Chrome release a new version every 6 weeks
* Microsoft recently deprecated support for Internet Explorer
    * [Phaseout of Internet Explorer Stirs No Grief](http://ww2.cfo.com/mobile/2015/04/phaseout-internet-explorer-stirs-no-grief/)
* Microsoft is launching Spartan

---

Browser Share on Data Portals (Q1 2015)

![browser-share](./images/browser-share.png)

---

Browser Usage on Data Portals (6 months to 3/31/2015)

![Browser Usage](./images/browser-usage.png)

---

## Initial Validation

* Conclusions:
    * Develop a new approach that effectively combines processes, standards and technology to maintain a continuous, documented, reproducible, and structured quality review of our clinical trials data management system
    * Furthermore, this new approach should allow us to rapidly validate new functionality and browser versions

---

# Automated Validation

---

## Software Development Life Cycle

* Request
* Approval
* Design
* Specification
* Requirements
* Development
* Testing
* UAT
* Release
* Configuration
* Deployment

---

## Software Development Life Cycle

* <span class="text-success">Request</span>
* Approval
* Design
* <span class="text-success">Specification</span>
* <span class="text-success">Requirements</span>
* <span class="text-success">Development</span>
* <span class="text-success">Testing</span>
* UAT
* Release
* <span class="text-success">Configuration</span>
* <span class="text-success">Deployment</span>

---

## Tools

* Git (Version Control)
* Github (Cloud-based Version Control Service)
* Jenkins (Task Queue)
* Amazon Web Services (Platform as a Service)
* Robot (Automated Functional Testing)
* Foreman + Puppet (Provisioning and Configuration Management)
* Spacewalk (Package Management)

---

## Benefits
* Manage and test all software and system deliverables on a ongoing basis
    * Reproducibility
    * Flexibility
    * Scalability
    * Visibility
    * Metrics
* Testing becomes central to the overall development process

---

## Status
* We completed development of this automated validation framework in July 2014
* We completed the first round of automated validation activities in December 2014
* We achieved full coverage of <span class="text-success underline">all</span> Data Portal apps in March 2015

---

## Status
* The following tests are running <span class="undeline">nightly</span>:
    * 1k+ Functional Tests
    * 8k+ Unit Tests
* We plan to continue to expand our test coverage

--- &vertical

Request Management

![issues](./images/issues.png)

***

Testing Command Center

![test-menu](./images/test-menu.png)

---

Robot in Action

[test-video](https://youtu.be/D7zqlG8OlZM)

<section>
  <iframe data-src="https://youtu.be/D7zqlG8OlZM"></iframe>
</section>

---

# Roadmap

* Improvements to the Help app
* Developing new approaches to integration of external data
* Working on with LONI to add ADCS data to GAAIN
* Preparing for A5 and future studies
* Working with Safety Stats on RBM
* Working with Stats on Reporting
* Working with Biomarker on LIMS

---

# Thanks

---

