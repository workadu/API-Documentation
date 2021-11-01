# Install npm dependencies

npm install

# Εντολή για compile του .apib 

aglio --theme-template templates/index.jade -i rengine.apib -o index.html
aglio --theme-template templates/triple.jade -i rengine.apib -o index.html 

# Επειδή αυτόματα κάνει cache js/css, δεν ξαναφορτώνονται οι αλλαγές σε καινουριο compile
# Για να μην κανει cache θελει enviroment variable NOCACHE=1
# https://github.com/danielgtaylor/aglio/issues/148
