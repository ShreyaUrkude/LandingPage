# LandingPage

## Approach

I created the landing page using only HTML and CSS, focusing on a clean layout and proper folder organization for assets such as images and styles. The project is structured in a simple and readable way, with all static files grouped logically. For deployment, I used Vercel’s static hosting and configured the output directory correctly so that the landing page loads from the intended folder.

---

## Challenges Faced

The main challenge was deploying the project on Vercel while keeping the landing page files inside a subfolder. Initially, this caused a 404 error because Vercel could not locate the `index.html` file. I resolved this by setting the correct output directory in the Vercel project settings. Ensuring that all CSS and image paths were relative was also important to avoid broken assets after deployment.

---

## Known Issues

There are no major functional issues in the project. As this is a static HTML and CSS site, it does not include dynamic behavior or form validation. Minor layout differences may appear on very small screen sizes depending on the browser.
