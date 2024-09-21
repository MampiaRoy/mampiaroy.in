# Mampia Roy - Portfolio
## Welcome to the portfolio source code. This portfolio is designed in Canva and courses are designed in Articulate Storyline. You can navigate through the folder structure to see the raw files

# Hosting
Currently the hosting is managed by Amazon AWS S3 bucket. The website is static so it can be easily served from file/object storage endpoints.

# Steps to host Canva files
- Remove first html tage related to base URL
- Update all the URLs with your site domain
- Comment the script related to below promise
```
Promise.all([fetch('_footer?lang=' + encodeURIComponent(lang)), loaded]).then( ([response]) => {
```

