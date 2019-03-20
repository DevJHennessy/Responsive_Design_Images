<h1>Responsive Web Design: Images and Sliders</h1>

<p>In this repository there are several examples of how to use responsive images on websites. These are from the PluralSight Course: <a href="https://www.pluralsight.com/courses/responsive-web-design-images-sliders">Hands-on Responsive Web Design 2: Responsive Images and Sliders</a>. For each page, you can play around with expanding and shrinking the screen size to watch the responsiveness between small, medium, and large screen sizes and see how the images change.</p>

<p><strong>Note:</strong> The best way to view these examples is to either clone the repository or download the files and open the files on your local machine. The GitHub Previewer is not fully functioning and you may come across a few errors. Also, to better view the changes in the images, FireFox is the best browser because it will rapidly switch between different-sized images, where Chrome will take the largest image and only display that image until you empty your cache and do a hard reload.</p>

<p>The <a href="https://htmlpreview.github.io/?https://github.com/DevJHennessy/Responsive_Design_Images/blob/master/Art_Direction/index.html">first example</a> shows how to use Art Direction. You can see how this works with the first image. When viewed on a small screen, you see mostly the person in the ruins, then on medium screen you can see more of the ruins, and finally on large screens you can see all of the ruins. The next two images of the Temple Mount show to properly employ Art Direction with the Picture element versus the Figure element. You can see the second image does not properly respond when setup in a figure tag, as it will not take into account pixel density for a device, whereas if you use the picture tag, it will properly go through the srcset of images, and you can also set it up to use media queries to ensure the image you want displayed at a certain size will be displayed. You may not see this in the previewer, but if you serve this on your local machine you will see how the third image has a 2x on the image when viewed in a small window and the second image has a 1x, showing the difference in pixel density.</p>

<p>The <a href="https://htmlpreview.github.io/?https://github.com/DevJHennessy/Responsive_Design_Images/blob/master/Background_Scaling_Images/index.html">second example</a> shows the usage of scaling background images in the header, with a different-sized images for small, medium, and large screens. It also displays a logo over part of the background header image with three different sizes displayed depending on device pixel density shown with a 1x, 2x, and 3x.</p>

<p>The <a href="https://htmlpreview.github.io/?https://github.com/DevJHennessy/Responsive_Design_Images/blob/master/Different_Sized_Responsive_Images/index.html">third exmaple</a> demonstrates how to employ different different-sized images depending on the browser window width. The first image ranges from 400 pixels wide to 1200px wide, and you can watch the numbers change as the breakpoint is hit. The second image shows how to use min-width to change the view width (vw) of the image while also changing the size of the image from 700 pixels to 1300px depending on the browser window width. On large screens, the vw is 50, on medium 75, and on small screens 100vw.</p>

<p>The fourth example uses <a href="http://kenwheeler.github.io/slick/">Slick Slider by Ken Wheeler</a> and shows how to use responsive images inside the slider, switch between large and small images depending on the device width by using a media break. The GitHub previewer does not display this at all, so to see this you will have to clone or download the repository. It also shows how to display the image at a certain width of the available screen space.</p>

<p>The <a href="https://htmlpreview.github.io/?https://github.com/DevJHennessy/Responsive_Design_Images/blob/master/Lazy_Load_Images/gallery1.html">fifth example</a> uses a <a href="https://www.andreaverlicchi.eu/lazyload/">Lazy Loading Script</a> designed by Andrea Verlicchi. It presents a gallery of images that only loads the first two images and then the next image as the user scrolls down. This maximizes page download speeds because the user does not have to download all of the page's content before they begin viewing the site. you can see how the images are loaded one a time by using the developer tools and navigating to the Network pane and record, then just slowly scroll down and watch as each new image shows up under name. You can also see the memory transferred and the number of requests. If you emulate an iPhone 6/7/8 the requests should start at 15 and end at 24 when scrolled to the bottom of the page.</p>

<p>The sixth and final <a href="https://htmlpreview.github.io/?https://github.com/DevJHennessy/Responsive_Design_Images/blob/master/Similar_Sized_Responsive_Images/index.html">example</a> demonstrates how to use similar-sized images and how to changed the image depending on the device's pixel density.</p>
