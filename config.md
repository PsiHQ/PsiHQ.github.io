<!--
Add here global page variables to use throughout your website.
-->
@def website_title = "Shihabul Haque"
# @def website_descr = "My site"
# @def website_url   = "https://psihq.github.io/Site/"

@def author = "shihabulhaque"
@def mintoclevel = 2

# uncomment and adjust the following line if the expected base URL of your website is something like [www.thebase.com/yourproject/]
# please do read the docs on deployment to avoid common issues: https://franklinjl.org/workflow/deploy/#deploying_your_website
@def prepath = "Site"

# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.

@def ignore = ["node_modules/", "franklin", "franklin.pub"]

keep_path = ["google38ae4f3003f81085.html"]
<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}
