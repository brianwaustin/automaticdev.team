# AutomaticDEV.Team #

**Automatic DEV Team** - **_Building high performance, autonomous software development teams_**

## About ##

Automatic DEV Team is a website I created as a collection of articles I've written
related to building high performance, autonomous software development teams that
live, breath and function almost automatically.

## Why Did I Build It This Way? ##

By automating static site generation and hosting via Amazon, I'm able to build, host and update
this site at a lower cost. Typical Wordpress installations either require a paid account on Wordpress.com, or a dedicated EC2 instance to run 24/7. This is overkill because most of the content on this site
*NEVER* changes.  

## How I Built the Site ##

I built the Automatic DEV Team site [automaticdev.team](https://automaticdev.team/) using the following tools:

* HTML/CSS/JavaScript - Based on a popular Wordpress theme
* Hugo - An open-source static site generator
* Github - Version control
* TravisCI - Continuous integration & deployment
* Amazon Web Services
  * S3 - Static file hosting
  * Route 53 - DNS Management
  * AWS Certificate Manager - SSL certificates
  * CloudFront - SSL assignment and web hosting
  * IAM - Identity management & deployment keys
* Color scheme
  * [Winter Forest Color Scheme](https://www.schemecolor.com/winter-forest.php)
  * [Uneasy Calm Color Scheme](https://www.schemecolor.com/uneasy-calm.php)
  
## Demo ##

Working demo can be found here https://automaticdev.team

## Run Locally ##

Install Hugo and from the command line:  hugo server -D

## Create a New Page ##

hugo new posts/my-first-post.md

## Road map - What's Next?? ##

My near term road map for this project includes

* Adding additional cloud centric content (the original purpose of the site)
* Adding analytics, probably via Google
