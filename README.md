# Overview
This project is built with the static site engine Hugo (https://gohugo.io/). 
Using Hugo allows us to have templates/partials for commons parts of the website, like the navigation,
that are written in one file and included across the site - making maintence far easier than a purely
static site. It also can make blogging/galleries easier through the template/content system.

# Getting Started

**Clone this Project**
```
git clone https://github.com/andremleblanc/bruiser-static.git
```

**Download Hugo** 
https://gohugo.io/overview/installing/

**Run Hugo Server Locally (for development)**
```
hugo server
```

**Make Changes and Commit**

# Deploying 

Run `hugo` to build static files.
Commit and push changes.
Travis CI will automatically push changes to Amazon S3.
