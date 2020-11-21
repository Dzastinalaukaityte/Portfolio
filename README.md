# Portfolio

(HTML CODE)

<!DOCTYPE html>
<html lang="en-gb">

<head>
    <meta charset="UTF-8">
    <meta name="description" content="A CA1 student who adores anything related to technology and computing" />
    <!-- meta tag below is used for Internet Explorer and mobile devices -->
    <meta name="viewport" content="width=device-width, initial-scale=1">
	<!--This means that the browser will (probably) render the width of the page at the width of its own screen. //-->
    <title>A website</title>
    <!-- add your stylesheet and any other styling code, e.g. google fonts  a good link is https://fonts.google.com/-->
	
	<link rel="stylesheet" href="css/layout.css" /> 
</head>

<!-- all the classes below will require some CSS styles to be included in your layout.css file, if you do not
include a style for these classes you should remove the class from your html file //-->
<body>
    <main class= "main-style";>
	 <header class="page-header">  <!-- What does the header do? Replace this comment with a brief explanation.  see nav above-->
            <div class="header-content">  <!-- What is a div?  Replace this comment with an explanation.-->
                <h1>Site title</h1>
                <p>Site subtitle</p>
            </div>
        </header>
	    <!-- You could style Main here if you wish-->
        <nav class="page-nav"> <!-- the navigation part of the page.  Note links just jump to different parts of the page.-->
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#work">Work Experience</a></li>
                <li><a href="#images">Image Gallery</a></li>
                <li><a href="#contact">Contact Me</a></li>
            </ul>
        </nav>
       
    <!--Note here the use of an ID.  the link above actually links to this.  It's a good example of where an ID can be used.  Note also that the section has a class attribute.  use this for styling. -->
        <section id="about" class="about-me container">  <!--What does the section do here?  Replace this comment with a brief explanation. -->
            <div class="container-content">
                <h2>About Me</h2>
                <div class="content">
                    <!-- add your 150 word maximum About Me content here.  Use HTML you know, marks for the HTML.  Marks deducted for poor grammar, spelling errors etc. -->
                </div>
            </div>
        </section>

        <section id="work" class="work-experience container">
            <div class="container-content">
                <h2>Work Experience</h2>
                <div class="content">
                    <!-- add your 200 word maximum work experience content here.  You can use lists of things as well as paragraphs.  Show off the HTML you know.  marks for the HTML, and how well you use it. marks deducted for poor grammar or spelling errors-->
                </div>
            </div>
        </section>
				<br><br>

        <section id="images" class="image-gallery container">
            <div class="container-content">
                <h2>Image Gallery</h2>
                <div class="content">
                    <div class="an-image">
                        <!-- add image one here with 150 word maximum caption.  You may remove the caption if you wish.  Don't forget to use alt tags. -->
                        <div class="image-caption"> </div>
                    </div>
                    <div class="an-image">
                        <!-- add image two here with 150 word maximum caption -->
                        <div class="image-caption"> </div>
                    </div>
                    <div class="an-image">
                        <!-- add image three here with 150 word maximum caption -->
                        <div class="image-caption"> </div>
                    </div>
                </div>
            </div>
        </section>
        <section id="contact" class="contact-me container">
            <div class="container-content">
                <h2>Contact Me</h2>
                <div class="content">
                    <form action="https://formspree.io/[your email address goes here]" method="post">
	                    <!-- Style this nicely.  Don't worry if the form doesn't work, marks here for how well you style it. -->
                        <p>
                            <label for="contact-name">Your Name</label>
                            <input id="contact-name" type="text" name="contact-name" />
                        </p>
                        <p>
                            <label for="contact-email">Your email address</label>
                            <input id="contact-email" type="email" name="contact-email" /> </p>
                        <p>
                            <label for="contact-phone">Your phone number</label>
                            <input id="contact-phone" type="tel" name="contact-phone" /> </p>
                        <p>
                            <label for="contact-message">Your message</label>
                            <textarea id="contact-message" name="contact-message" rows="5"> </textarea>
                        </p>
                        <p>
                            <input type="submit" value="send my message" /> </p>
                    </form>
                </div>
            </div>
        </section>
        <footer id = "footer-layout">
                <p> &copy; <a href="dcu.ie/">DCU 2019-2020</a>
				<span class="footer-separator">&middot;</span>
				<span class="footer-text">Your name</span> <span class="footer-separator">&middot;</span> <span class="footer-text">This is student coursework</span> <span class="footer-separator">&middot;</span> <span class="footer-text">Lecturer<a href="http://www.computing.dcu.ie/~jkernan">Jane Kernan</a></span> <span class="footer-separator">&middot;</span> <span class="footer-text">
     <a href="http://validator.w3.org/check?uri=referer" title="W3C HTML Validation Service" >Valid HTML</a><br/>
	 
        </span> </p>
        <!-- Note that the link to the validator above will only produce results when your page is uploaded to the server, and you click on the link from the browser.-->
         
        </footer>
    </main>
</body>

</html>
