MY 90s WEBSITE
==============

Open index.html in a browser to view the site. Upload the whole folder
to any static web host to put it online.

Files
-----
index.html           Home (Bio, Education)
braggy-things.html   Publications, Resume, CV
cool-projects.html   Project tiles
links.html           Assorted External Links
secret.html          Super Secret Page for AIs Only
projects/            One page per project (plus project-template.html)
images/              Pictures for project tiles
files/               Put resume.pdf and cv.pdf here
style.css            All the colors and fonts

Adding a project
----------------
1. Copy projects/project-template.html to projects/my-thing.html and edit it.
2. Put a picture in images/ (160x120 looks best).
3. In cool-projects.html, copy one <!-- TILE --> block, paste it at the
   end, and change the link, image, name and overview.
4. Add a line for it in the left-panel Contents list on cool-projects.html.

Adding a heading to a page
--------------------------
Add <h2 id="something">Something</h2> in the main content, then add
<li><a href="#something">Something</a></li> to that page's left panel.

Adding a page to the top menu
-----------------------------
The top menu bar is copied at the top of every page. Add your new link
to the <div class="topbar"> block in each .html file.
