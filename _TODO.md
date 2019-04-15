# basic steps

 1. convert this to jekyll properly
 1?. GET RID OF REVOLUTION SLIDER
 2.? optimise 
  

 3?. convert to netlify - https://www.netlifycms.org/docs/jekyll/ <--
    also use https://www.netlifycms.org/docs/add-to-your-site/
 3?. use jekyll-admin/ jekyll-manager, and authenticate using raven 
        - https://github.com/cambridgeuniversity/mod_ucam_webauth/blob/master/README.Config
        - use `Require user ar899 mhXXX`

 4. get it hosted on the srcf - maybe just use netlify from now on? - https://github.com/Skeith918/self-hosted-netlifycms
 5. add new admins

notes
 - use file collections (netlify cms) for static content
 - use datafiles to do committee members, etc.? - https://jekyllrb.com/docs/datafiles/
 - maybe use datafiles for most content since all content is static and nothing new is added (e.g. blog), just changed - 


optimisations

 - use responsive-image-jekyll
     - https://github.com/wildlyinaccurate/jekyll-responsive-image
 - lazy-loading, use responsive image to generate low quality image
     - use lazysizes as here: https://www.ratanparai.com/jekyll/Responsive-image-on-jekyll/
     - use smaller lazyloading script, as here:
     - requires slightly modifying template in _includes: https://jekyllcodex.org/without-plugin/lazy-loading/
 - image resizing: https://www.kevan.tv/articles/automatic-image-resizing-with-jekyll-and-imagemagick/