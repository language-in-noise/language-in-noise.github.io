---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: MSUCampus1.jpg
  caption: "East Campus bike path"
widget1:
  title: "About the CSLN REU site"
  url: "/about"
  image: "GLEEFUL2019-2.jpg"
  text: 'Learn about the main goals of the project.'
widget2:
  title: "Projects"
  url: "/projects"
  text: 'This will point to the projects'
  image: "GLEEFUL3.jpg"
widget3:
  title: "People"
  url: "/people"
  image: "GLEEFUL2016-1.jpg"
  text: "Meet our faculty mentors"
#
permalink: /index.html
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
# callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Inform me about new updates and features ›
#  style: alert

#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#

homepage: true
---
