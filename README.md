# Project: Build a Portfolio Site

### About
This project uses concepts in Udacity's Intro to HTML and CSS, Responsive Web Design Fundamentals, and Responsive Images courses to build a mock portfolio page. The page has both responsive design and images. The page dynamically resizes using Bootstrap and downloads the appropriate images based on viewport width.

### Directory Contents
In addition to this README.md file you will find:
`css/` - Contains the default Boostrap CSS files as well as styles.css, which provides custom CSS formatting for the page.
`images/` - Contains the images used on the page. The resized images were created using Grunt.
`images_src/` - Contains the source images used on the page, which were then resized appropriately using Grunt.
`js/` - Contains the Bootstrap and jQuery JavaScript used on the page, including the modals on the portfolio images.
`config.json` - Contains Bootstrap JavaScript data.
`Gruntfile.js` - The JavaScript file used to resize the images saved in images/.
`index.html` - Contains the HTML for the portfolio site.
`package.json` - Contains package information used by Gruntfile.js to resize images.


### How to view the page
1. If your computer doesn't already have Python installed, install [it](https://www.python.org).
2. Download the directory and, if the directory is in a compressed file, extract it.
3. Open Terminal and navigate to the directory.
4. Launch SimpleHTTPServer by running `python -m SimpleHTTPServer`.
5. Open your browser and navigate to http://127.0.0.1:8000 to view the page.
6. Use Developer Tools to resize the page to different viewports. Reload the page and use Developer Tools to see different images loading based on different page widths.

### How to use Grunt to resize images
This directory may not include the `node_modules/` folder needed to resize pictures at scale. To create the folder, use Terminal to navigate to the directory and run npm install. This will then allow you to use Gruntfile.js to create resized images. For more information on how to start using Grunt, click [here](https://24ways.org/2013/grunt-is-not-weird-and-hard/).

### Creator
Jason Ally
https://github.com/jasonally/
jason[dot]ally[at]gmail.com