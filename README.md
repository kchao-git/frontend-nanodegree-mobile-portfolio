## Website Performance Optimization portfolio project

To run this site, download all the contents and open index.html in your preferred browser. The first page shows the main page where Critical Rendering Path is optimized for PageSpeed.

Click on the link for Cam's Pizzeria to go to the page that demonstrates framerate and computation efficiency optimization. Scrolling the page should render at close to 60 FPS while changing the pizza sizes should take no longer than 3-4ms.

Optimizations done to Portfolio Page:
Render blocking Javascript was changed to load asynchronously.
Relevent CSS and webfonts load after page is ready.

Optimizations done to Cam's Pizzeria:
Modified code to remove as much Forced synchronous layouts as possible.