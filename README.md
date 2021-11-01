# Install npm dependencies
```cmd
npm install
```

# Build documentation html
```cmd
npm run dev
```

# Builder documentation and watch for changes
```cmd
npm run watch
```

# Επειδή αυτόματα κάνει cache js/css, δεν ξαναφορτώνονται οι αλλαγές σε καινουριο compile
# Για να μην κανει cache θελει environment variable NOCACHE=1
# https://github.com/danielgtaylor/aglio/issues/148
