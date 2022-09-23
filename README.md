# Personal Blog Website Project

This project requires you to use your HTML and CSS skills to build a personal blog website.

---

## Running the Live Server

The live server is a tool that will auto update every time you make a change to a file.

To start the live server, enter the following code into your terminal application or the terminal workspace pane:

```
npm start
```

Once you have entered this code, the live server will continue to run. If you would like to stop the server, type **[control] [c]**. You will see the terminal window exit the live server.

---

## Project Instructions

1. **Set up the file structure of your project**.  
You'll need separate HTML files and related CSS files for the home page and the blog post. These files should be organized into subdirectories. <br><br>
If you use any image files rather than links to image urls for your avatars and any other images, you'll also need to add folders for those.<br><br>
You should end up with a structure that looks similar to this:
```js
├── index.html
├── assets
│   ├── css
│   │   ├── style.css
│   │   ├── home.css
│   │   └── post.css
│   └── images // if needed
│       ├── ?
│       └── ?
└── blog-posts
        └── post1.html
```
2. **Draw mock pages for the website**.  
Make a quick sketch of the different headers, boxes, etc. to help you think through how you want to organize the page layout.

3. **Build out the HTML for the home page**.   
Build out each section of the page focusing on the elements you need to use for each section.  Don't worry about styling yet! 

4. **Build the HTML for your example blog post**.  
You can use the HTML you built for the home page as a starter, and then change the parts that need to be different on the blog post page.

5. **Style your pages with CSS**.   
You should have one primary CSS file that is linked to from each of the HTML pages, and then [import separate CSS files](https://developer.mozilla.org/en-US/docs/Web/CSS/@import) for each page into the primary CSS file. Remember that you need to both Flexbox and Grid!

6. **Add links between pages**.  
If your project structure is set up correctly and you add the appropriate links within your HTML, a user should be able to click on those links to go between the main page and the blog post(s) you have created. Note that it is fine to have some fake links for items you haven't built out.

7. **Test and iterate!**    
Make sure that everything on each page is working and looks the way you want it to look. 
    1. Validate your [HTML](https://validator.w3.org/nu/#textarea) and [CSS](https://jigsaw.w3.org/css-validator/#validate_by_input). 
    2. Check for responsivness using the [Chrome Dev Tools](https://developer.chrome.com/docs/devtools/device-mode/) device simulator.
    3. Review the [project rubric](https://review.udacity.com/#!/rubrics/4943/view) to confirm that you have met all of the requirements.
 
 
8. **[OPTIONAL] Add extra features**.   
If you have extra time you can add features or functionality to make your project standout! Here are some suggestions:
   - Deploy your project to [Github Pages](https://pages.github.com/) so you can share it with friends and others.
   - Write one or more real blog posts to replace the placeholder text.
   - Replace the placeholder images with custom images.
   - Add more pages to the site -- maybe a
