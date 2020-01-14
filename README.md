# GenerateHTMLPublicationsPage

<i>This little script was written by <a href="https://www.github.com/drkenreid">Ken Reid</a> for the <a href="www.msuqg.github.io">MSU Quantitative Genetics website</a>. Please give it a star if you use it.</i>

This works in 3 steps.

<ol>
    <li> Set up author names for parameters</li>
    <li> Run the scrape, keep only useful information. Removed non-unique entries.</li>
    <li> Write the HTML page (this is customised for <a href = "https://www.msuqg.github.io">www.msuqg.github.io</a> but can be easily modified for your own usage). </li>
</ol>

If you would rather skip most of step 3 and simply copy-paste the scraped and HTML-ized data, that's fine too, see the end of step 3.

<i>PS: The CSS folder is for a prettier experience viewing publications.html - not necessary for this project whatsoever.</i>

<h1> Complete Beginner? </h2>

Hi. If you are a complete beginner to Python, HTML, Jupyter Notebooks, Anaconda, I can hopefully guide you.

This script requires a couple of installations on your computer. You will need:

<ol>
    <li> <a href = "https://www.anaconda.com/">Anaconda</a>. This should work fine on most operating systems (Windows, Mac OSX, Linux)</li>
    <li> Jupyter Notebooks. Once you've installed anaconda, this is opened by opening cmd (windows) or terminal (Mac / Linux) and typing "jupyter notebook". It should automatically launch.</li>
    <li> Python. Don't worry, this is installed with anaconda. </li>
    <li> Packages. There are some required packages in this script, but if you inspect the notebook you'll see how to install what you need.</li>
</ol>
