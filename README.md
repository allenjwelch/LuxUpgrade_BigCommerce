# LuxUpgrade_BigCommerce


## Modification Notes:
- Changed "New" to "Featured" products (could not locate how to add featured products)
- Many SCSS features from home.html changed within cards.scss (could not locate where specific divs were styled)
- Several pre-set CSS properties have been changed within their corresponding scss file and not in the config.json file. 
- Used media queries instead of @include as I was more familiar with media q's
- Time spent was roughly 10-12 hours, most of which was spent learning the file structure and code base. 


## Issues: 
- Responsiveness of added or modified features. 
  - Attempted to adjust settings within breackpoints (ex. _heroCarousel.scss), but I assume changes were being overwritten in another file. 
- Could not remove underline from hero carousel content
- Sizing and placing SVG images
- Many of the images I uploaded while in Stencil CLI were not visible after uploading theme to bigCommerce. I have added images below of the modifications as seen on localhost

## Localhost Images
### Header_Desktop
![title image](/assets/img/localhost/header_desktop.PNG)

### Header_Mobile
![title image](/assets/img/localhost/header_mobile.PNG)

### Sub Categories_Desktop
![title image](/assets/img/localhost/subCat-featured_desktop.PNG)

### Sub Categories_Mobile
![title image](/assets/img/localhost/subCat_mobile.PNG)

### New Tech_Desktop
![title image](/assets/img/localhost/newTech-research_desktop.PNG)

### New Tech_Mobile
![title image](/assets/img/localhost/newTech_mobile.PNG)

### Research & Footer_Desktop
![title image](/assets/img/localhost/research-footer_desktop.PNG)

### Research_Mobile
![title image](/assets/img/localhost/research_mobile.PNG)


### Footer_Mobile
![title image](/assets/img/localhost/footer_mobile.PNG)
