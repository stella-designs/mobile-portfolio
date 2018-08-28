## Website Performance Optimization portfolio project

In this project my goal is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques I've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

Link to my completed [mobile portfolio](https://websiteartist.github.io/mobile-portfolio/).

### Getting started

#### Part 1: Optimize PageSpeed Insights score for index.html

Some useful tips to help you get started:

1. Check out the repository
1. To inspect the site on your phone, you can run a local server

  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
  ```

1. Open a browser and visit localhost:8080
1. Download and install [ngrok](https://ngrok.com/) to the top-level of your project directory to make your local server accessible remotely.

  ``` bash
  $> cd /path/to/your-project-folder
  $> ./ngrok http 8080
  ```

1. Copy the public URL ngrok gives you and try running it through PageSpeed Insights! Optional: [More on integrating ngrok, Grunt and PageSpeed.](http://www.jamescryer.com/2014/06/12/grunt-pagespeed-and-ngrok-locally-testing/)

Profile, optimize, measure... and then lather, rinse, and repeat. Good luck!

#### Part 2: Optimize Frames per Second in pizza.html

To optimize views/pizza.html, you will need to modify views/js/main.js until your frames per second rate is 60 fps or higher. You will find instructive comments in main.js. 

You might find the FPS Counter/HUD Display useful in Chrome developer tools described here: [Chrome Dev Tools tips-and-tricks](https://developer.chrome.com/devtools/docs/tips-and-tricks).

### Optimization Tips and Tricks
* [Optimizing Performance](https://developers.google.com/web/fundamentals/performance/ "web performance")
* [Analyzing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/analyzing-crp.html "analyzing crp")
* [Optimizing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/optimizing-critical-rendering-path.html "optimize the crp!")
* [Avoiding Rendering Blocking CSS](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-blocking-css.html "render blocking css")
* [Optimizing JavaScript](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/adding-interactivity-with-javascript.html "javascript")
* [Measuring with Navigation Timing](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/measure-crp.html "nav timing api"). We didn't cover the Navigation Timing API in the first two lessons but it's an incredibly useful tool for automated page profiling. I highly recommend reading.
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/eliminate-downloads.html">The fewer the downloads, the better</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/optimize-encoding-and-transfer.html">Reduce the size of text</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization.html">Optimize images</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching.html">HTTP caching</a>

### Customization with Bootstrap
The portfolio was built on Twitter's <a href="http://getbootstrap.com/">Bootstrap</a> framework. All custom styles are in `dist/css/portfolio.css` in the portfolio repo.

* <a href="http://getbootstrap.com/css/">Bootstrap's CSS Classes</a>
* <a href="http://getbootstrap.com/components/">Bootstrap's Components</a>

### Resourses for Completing this project 

* <a href=https://classroom.udacity.com/nanodegrees/nd001>Udacity</a>
* <a href=https://www.w3schools.com/>w3schools</a>
* <a href=https://developers.google.com/web/tools/>Google Developers</a>
* My Udacity Mentor 

### My Learning Process & Commits 

* Wed Aug 22 10:04:25 2018, update resize bar
* Tue Aug 14 12:59:33 2018, removed metadata
* Tue Aug 14 12:46:24 2018, fixed img
* Tue Aug 14 12:44:35 2018,  fixed img size
* Tue Aug 14 12:40:32 2018, reduced img size
* Fri Aug 10 10:14:37 2018, minifed css
* Thu Aug 9 10:37:11 2018, add resources
* Wed Aug 8 15:39:20 2018, changed sizeSwitcher to percent
* Wed Aug 8 12:30:45 2018, changed .row margin from -15 to 1px
* Wed Aug 8 11:10:54 2018, comment out theme-color
* Wed Aug 8 11:07:45 2018, add alt to img
* Wed Aug 8 11:01:44 2018, add alt to img
* Wed Aug 8 10:50:13 2018, add theme color
* Wed Aug 8 10:47:43 2018, changed header color
* Wed Aug 8 10:18:15 2018, added link to profile photo
* Wed Aug 8 10:13:39 2018, alt added to img
* Wed Aug 8 10:01:26 2018, changed header name
* Fri Aug 3 16:13:45 2018, removed app.js n jsapi.js script
* Fri Aug 3 16:10:50 2018, removed service worker files
* Fri Aug 3 16:07:15 2018, increased font size
* Fri Aug 3 16:01:10 2018, add media to stylesheet
* Fri Aug 3 13:23:37 2018, add pizzaImage.alt
* Fri Aug 3 13:13:02 2018, added top padding to col
* Fri Aug 3 13:06:14 2018, changed background color
* Fri Aug 3 12:44:12 2018, add alt to img in mover class
* Fri Aug 3 12:17:32 2018, updated css media style
* Fri Aug 3 12:13:24 2018, add media to css
* Fri Aug 3 11:37:42 2018, added alt to img in tab
* Fri Aug 3 11:33:15 2018, added lang
* Fri Aug 3 11:31:51 2018, added alt to img
* Tue Jul 24 16:53:06 2018, Updated header
* Tue Jul 24 16:47:42 2018, set viewport
* Tue Jul 24 16:42:00 2018, added willchange to mover
* Tue Jul 24 13:57:06 2018, rmoved theme
* Tue Jul 24 13:48:20 2018, theme color
* Tue Jul 24 13:35:02 2018, install service worker
* Tue Jul 24 13:19:32 2018, add app.js
* Tue Jul 24 11:29:49 2018, fixed problems
* Tue Jul 24 11:22:52 2018, added app.js service worker
* Tue Jul 24 10:17:16 2018, async stylesheets
* Tue Jul 24 09:56:19 2018, updated background color and icon img
* Tue Jul 24 09:48:01 2018, header info update
* Tue Jul 24 09:31:50 2018, fixed typo
* Tue Jul 24 09:30:23 2018, updated fisrt paragraph
* Sat Jul 7 14:14:31 2018, alt added to imgs'
* Sat Jul 7 13:48:46 2018, moved google fonts to new file jsapi.js
* Fri Jul 6 11:18:05 2018, ggogle fonts moved to js
* Tue Jul 3 14:31:51 2018, created small size pizzaria img
* Tue Jul 3 14:19:51 2018, added mediam print to print.css
* Tue Jul 3 13:56:14 2018, changed photos back to original format
* Mon Jul 2 16:33:05 2018, edited imgs' to jpf
* Mon Jul 2 16:27:09 2018, changed pizzeria img file size
* Mon Jul 2 16:19:47 2018, reduced img size
* Mon Jul 2 15:59:59 2018, comment out analytics
* Mon Jul 2 15:54:41 2018, minified
* Mon Jul 2 15:51:47 2018, minified bootstrap
* Mon Jul 2 10:50:10 2018, google fonts changed back to stylesheet
* Mon Jul 2 10:26:43 2018, paragraph update
* Mon Jul 2 10:00:57 2018, remove email
* Fri Jun 29 08:31:00 2018, changed thumbnail size
* Fri Jun 29 08:23:04 2018, changed arcade thumbnail img
* Thu Jun 28 13:55:17 2018, Added async to html files
* Thu Jun 28 13:47:26 2018, Added personal info and img.
* Thu Jun 28 10:53:14 2018, Add pinkFrogger img
* Thu Jun 28 08:47:52 2018, Update link to project-arcade
* Thu Jun 28 08:18:50 2018, Deleted 2048 file
* Thu Jun 28 08:11:23 2018, Canged file name 4048
* Wed Jun 27 19:53:43 2018, Async analytics
* Wed Jun 27 19:06:46 2018, Updated img's
* Tue Jun 26 14:03:11 2018, Top of page personalized
* Mon Jun 25 11:54:30 2018, Initial commit