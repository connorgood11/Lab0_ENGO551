Requirements Checklist
1. Your website must contain at least four different .html pages, and it should be possible to get from any page on your website to any other page by following one or more hyperlinks.
    Has main page and three links, they were originally hyperlinks but i changed them to button on the main page, the other pages they remain as hyper links.
2. Your website must include at least one list (ordered or unordered), at least one table, and at least one image.
    Page with images, page with table, page with list
3. Your website must have at least one stylesheet file.
    Has a stylesheet file
4. Your stylesheet(s) must use at least five different CSS properties, and at least five different types of CSS selectors. You must use the #id selector at least once, and the .class selector at least once.
    Uses many properties and selectors, uses id once and classes many times
5. Your stylesheet(s) must include at least one mobile-responsive @media query, such that something about the styling changes for smaller screens.
    Changes the background to dark for smaller screens
6. You must use Bootstrap 4 on your website, taking advantage of at least one Bootstrap component, and using at least two Bootstrap columns for layout purposes using Bootstrap’s grid model.
    Using bootstrap flexbox for the links on the index page using three columns that will wrap if the window size is too small
    Using button components for the links to other pages
7. Your stylesheets must use at least one SCSS variable, at least one example of SCSS nesting, and at least one use of SCSS inheritance.
    Using variables for colors, complexity scores easy, medium, and hard inherit properties from complexityScore, within our media queries we have nested css to change some of our body h1 and div properties if the screen is smaller
8. In README.md, include a short writeup describing your project, what’s contained in each file, and (optionally) any other additional information the staff should know about your project.
    this

Short writeup:
    The website consists of four html pages. The index.html page has a window title of My Dog Leia, a header that describes the website, and Bootstrap columns that feature buttons that link the user to other html pages and an image.

    The stylesheet.css is converted from the sccs version that features various requirements for the website such as css property and selector utilization as well as classes, id, media queries. There is a complexityScore scss class that is extended by the various scores easy, medium, and hard. There is scss variables for colours and nesting within the media queries.

    The images.html page is a simple page that features images of Leia. The details.html page is a demonstration of css unordered lists. The tricks.html page shows the implementation of a table and the scss nested classes using the parent complexityScore.