---
title: "Default"

date: "{{ now.Format "2006-01-02" }}"

categories:
- category
- subcategory

tags:
- tag1
- tag2

# Define keywords for search engines. you can also define global keywords in Hugo configuration file.
keywords:
- keyword1
- keyword2

# Hide sidebar on all article page to let article take full width to improve reading, and enjoy wide images and cover 
# images. Useless if params.sidebarBehavior is equal to 3 or 4. (true: enable, false: disable). Default behavior: 
# params.clearReading value in theme configuration file.
clearReading: true  

# Image displayed in index view.
thumbnailImage: "" 	

# Display thumbnail image at the right of title in index pages (right, left or bottom). thumbnailImagePosition overwrite
# the setting thumbnailImagePosition in the theme configuration file 
thumbnailImagePosition: left

# Meta (title, date and categories) alignment (right, left or center).
metaAlignment: left

# Image displayed in full size at the top of your post in post view. If thumbnail image is not configured, cover image
# is also used as thumbnail image.
coverImage: ""

# partial: cover image take a part of the screen height (60%), full: cover image take the entire screen height.
coverSize: full 	

# Add a caption under the cover image
coverCaption: ""
# in: display post meta (title, date and categories) on cover image, out: display meta (title, date and categories) 
# under cover image as usual
coverMeta: in

# Images displayed in an image gallery (with fancybox) at the end of the post. If thumbnail image is not configured and 
# cover image too, the first photo is used as thumbnail image. format: original url [thumbnail url] [caption]
gallery: 

comments: false         # Show the comment of the post.
showDate: true          # Show the date when true (default)
showTags: true          # Show tags of this page.
showPagination: false   # Show pagination.
showSocial: true        # Show social button such as share on Twitter, Facebook...
showMeta: true          # Show post meta (date, categories).
showActions: true       # Show post actions (navigation, share links).
     
# Custom excerpt text to show on the homepage.
summary: ""
---

Template for new posts 

<!--more-->