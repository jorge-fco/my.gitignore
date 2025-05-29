# My .gitignore
🛑 My .gitgnore for basic projects.


```
# = MAC FILES
# ----------------------------------------------------------------------
Icon
.DS_Store

# =GIT
# ----------------------------------------------------------------------
.git
*.git

# = ASSETS
# ----------------------------------------------------------------------
/assets/fonts/*
/assets/favicons/*
/assets/images/*
/assets/videos/*

# = CSS & JS
# ----------------------------------------------------------------------
*.scss
/assets/dist/*.map
/assets/dist/main.min.css
/assets/dist/*.map
/assets/dist/main.min.js
/assets/dist/plugins.min.js

# = KIRBY FOLDERS
# ----------------------------------------------------------------------
/media/*
/content/*
/kirby/*
/panel/*
/site/*

# = IMAGES
# ----------------------------------------------------------------------
/thumbs/*
!/thumbs/index.html

# = CACHE
# ----------------------------------------------------------------------
/site/cache/*
!/site/cache/index.html

# = ACCOUNTS
# ----------------------------------------------------------------------
/site/accounts/*
!/site/accounts/index.html

# = AVATARS
# ----------------------------------------------------------------------
/assets/avatars/*
!/assets/avatars/index.html

# = EDITORS TEXT
# ----------------------------------------------------------------------
prepros.config
prepros.cfg
prepros-6.config
prepros.cfg
config.codekit3

# = PAGES
# ----------------------------------------------------------------------
*.zip
*.log
*.php
*.html
*.htaccess
readme.html
README.html

# = HTML
# ----------------------------------------------------------------------
*.jade
*.pug

# = NPM & BOWER
# ----------------------------------------------------------------------
node_modules/*
bower_components/*
package.json
package-lock.json
gulpfile.js

```

