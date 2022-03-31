# Corporate1
 An HTML, SCSS, and JS landing page template

 
Thank You! :)


Thanks for downloading this template. "Corporate 1" is my first all-purpose business landing web template. Responsive, clean, with a professional look, and with a sleek design that'll satisfy all your needs, whether if you are looking for a basis design, or just a simple and static web. All parts are nested in "divs", and is section-separated with html comments in between.

You will need basic HTML, SASS/SCSS, and BOOTSTRAP CSS skills to edit "Corporate 1". I will try to help you out with this documentation. But If I fail here, you can always contact me on ​i​nfo@bryanquiroz.com and try to solve your issue.


----------------------------------------------------------------------------------------------------------------------------------------


HTML Structure


	Corporate 1 consists on one major HTML file: index.html where are several sections, including links to the blog.html file, which is a minor HTML section if you ever need to construct blog-based web.

	•	index.html - Big front page
	•	blog.html - Blogging-space page

The big front page (index.html) consist of several sections (Home, Services, Portfolio, News, Pricing, Team, and Contact). Each section is comment-separated and starts with code like this:

<!-- Contact Info -->
<div class="container-fluid bg-dark" style="--bs-columns: 2; row-gap: 0;" id="contact"> ... <div>

<!-- Portfolio -->
<div class="container-fluid bg-dark" style="--bs-columns: 2; row-gap: 0;" id="portfolio"> ... <div>


----------------------------------------------------------------------------------------------------------------------------------------


SCSS Design


	Corporate 1 was styled on Bootstrap, and customized on SCSS in the page: main.scss where are several personalized classes, and Bootstrap customized variables. Make sure to install SASS on your project before making any code changes. (It is recommended to install SASS with the DART VM, so you'll also need to previously install DART on your PC, click here to see more about DART installation). 

You can install SASS on your project running commands in your text editor's terminal, and find all documentation about this process in the SASS Team's web portal (click here). 

Once you've installed SASS, you can now customize Corporate 1 to your heart's content on main.scss, but make sure that every time you deliver a change, you'll need to run this command on your project's terminal: 

sass source/main.scss css/main.css

This is because those changes first need to be transpiled into Bootstrap before they can be visualized in a browser. I strongly recommend not trying to customize Bootstrap directly inside it's core file (main.css) or in the Bootstrap files in the node_modules folder, because is pretty easy to mess up Bootstrap like that. 

Make sure to check out Bootstrap documentation in order to know the best practices in customizing your code, I highly recommend giving this page a good read.



----------------------------------------------------------------------------------------------------------------------------------------



Page sections


	As it was written at the HTML structure, every section of Corporate 1 is divided by a comment by the given name of the section. If you need to change the configuration or order of elements, remember that everything was written in Bootstrap (except for some personalized classes that are at the end of the main.scss page), and it includes all the source files to make you build faster your project .
	
	I recommend you to use images with the same dimensions as written in the image source labels that are all over the code, they will look like this:

<img src="https://fakeimg.pl/150x150/?text=150x150" class="team-img" alt="">

	Where "150x150" is the respective dimension of that image. But if you need to adapt an image with other dimensions, just make sure to check out the respective classes of it, in order to  adapt it to your needs. In this example, the class is "team-img" and it is not a Bootstrap class, so you'll have to check out main.scss and look for it to change it (if you need to).



----------------------------------------------------------------------------------------------------------------------------------------



Mail configuration


Note: Do not remove any quote or double quote signs while doing this.

One notice: this will be functional only on your server, php file can not be executed on your local computer.

Just add your own email address here in your config.php file.

//SITE GLOBAL CONFIGURATION
$email = "your@email.here"; //<-- Your email



----------------------------------------------------------------------------------------------------------------------------------------



Source and Credits


Special thanks to creators and contributors of these awesome
libraries (photos, vectors, js, etc…), I couldn’t done this without them (I am sorry if I forgot to mention someone).

 Images used just in DEMO theme
www.fakeimg.pl.

Google web fonts
www.fonts.google.com
www.github.com/googlefonts/nunito

Bootstrap
www.getbootstrap.com
www.getbootstrap.com/docs/5.1/getting-started/introduction/


Popper JS
popper.js.org


----------------------------------------------------------------------------------------------------------------------------------------
