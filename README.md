# hari-santanam.io
#Test Hugo repository for profile page

#
# This file contains configuration flags to customize your site
#
# Name of website
title: Hari Santanam's web page on Github

# Name of your site (displayed in the header)
name: Hari Santanam

# Short bio or description (displayed in the header)
description: Interested in Data Science/Machine Learning/Artificial Intelligence. 

# URL of your avatar or profile pic (you could use your GitHub profile pic)
avatar: https://github.com/HariSan1/harisan1.github.io/includes/hs-1.png

#
# Flags below are optional
#

# Includes an icon in the footer for each username you enter
footer-links:
  dribbble:
  email: hari.santanam@gmail.com
  facebook:
  flickr:
  github: harisan1
  instagram:
  linkedin: harisantanam  
  pinterest:
  rss: # just type anything here for a working RSS icon
  twitter: 
  stackoverflow: users/6317849/h-san
  googleplus: # anything in your profile username that comes after plus.google.com/
  


# Enter your Disqus shortname (not your username) to enable commenting on posts
# You can find your shortname on the Settings page of your Disqus account
disqus:

# Enter your Google Analytics web tracking code (e.g. UA-2110908-2) to activate tracking
#google_analytics:UA-77177035-1

# Your website URL (e.g. http://barryclark.github.io or http://www.barryclark.co)
# Used for Sitemap.xml and your RSS feed
#url:https://harisan1.github.io

# If you're hosting your site at a Project repository on GitHub pages
# (http://yourusername.github.io/repository-name)
# and NOT your User repository (http://yourusername.github.io)
# then add in the baseurl here, like this: "/repository-name"
baseurl: ""

#
# !! You don't need to change any of the configuration flags below !!
#

permalink: /:title/

# The release of Jekyll Now that you're using
version: v1.2.0

# Jekyll 3 now only supports Kramdown for Markdown
kramdown:
  # Use GitHub flavored markdown, including triple backtick fenced code blocks
  input: GFM
  # Jekyll 3 and GitHub Pages now only support rouge for syntax highlighting
  syntax_highlighter: rouge
  syntax_highlighter_opts:
    # Use existing pygments syntax highlighting css
    css_class: 'highlight'

# Set the Sass partials directory, as we're using @imports
sass:
  style: :expanded # You might prefer to minify using :compressed

# Use the following plug-ins
gems:
  - jekyll-sitemap # Create a sitemap using the official Jekyll sitemap gem
  - jekyll-feed # Create an Atom feed using the official Jekyll feed gem

# Exclude these files from your production _site
exclude:
  - Gemfile
  - Gemfile.lock
  - LICENSE
  - README.md
  - CNAME
