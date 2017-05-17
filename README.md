
![Netec Logo](https://raw.githubusercontent.com/Netec-edX/github-training/master/images/netec-logo.png "Netec Logo")
## Github Training Class

### Course Description
Welcome! The objective of this course is to provide the Open edX graphic design, admin and devops team members an opportunity to interact with Github in a team environment. During this course you will learn how to do the following
* install Git on your local computer
* create your own personal Github user account
* join the "Netec edX" Github organization
* edit and publish the sample web site in a team organizational structure

yadda yadda yadda

### Course Instructions
1. Review the materials below in the section "Resources"
2. Watch the video below, "Introducción práctica a Github" below
3. Create your personal Github account
4. Join the "Netec edX" Github organization (we'll do this together during the class workshop)
5. Install Git on your personal computer/laptop by following the instuctions below "How To Install Git on your computer"
6. Create a local git repository of this project on your computer by following the instructions below "Terminal / Cmd commands to clone this repository to your local computer"
7. Complete the "Team Assignment" as further described below.

### Your Team Assignment
You are part of the graphic design team for the [Hipster School online academy](https://netec-edx.github.io/github-training/). You and your team members have created a hip landing page for your online academy and have submitted the site to the digital division's director for approval. Unfortunately the director rejected two items on your landing page:
* She hates the text color of the site's title
* She doesn't believe that an image of Justin Beiber accurately portrays the identity of a modern hipster and so she has requested that you replace the Beiber image with this image of a [pair of vintage roller skates](https://raw.githubusercontent.com/Netec-edX/github-training/master/images/hipster-skates.jpg). You will work in a team environment to make these changes to the site, and then re-submit your completed changes; all using Github. The two changes are to be made as follows:
1. Edit the site's [main CSS style sheet](https://github.com/Netec-edX/github-training/blob/master/css/styles.css) on row 6.

```/*------------------------------------------------------------------
 FOR COURSE: Change the "color" attribute from green to #5F152C
 ------------------------------------------------------------------*/
#site-name {
  font-family: 'Lora', serif;
#  color: 	#5F152C;
  color: 	green;
  font-size: 2em;
  font-weight: 900;
  margin: auto;
}
/*------------------------------------------------------------------
 END: FOR COURSE
 ------------------------------------------------------------------*/
```

2. Change the image URL for the course "How to be Unique" by editing row 58 of [index.html](https://github.com/Netec-edX/github-training/blob/master/index.html)

```      <section id="section-unique">
        <div class="col-md-4 col-sm-6 col-xs-12">
          <div id="course-tile">
            <span><h3>How To Be Unique</h3></span>
            <!-- For course: change this image to images/hipster-skates.jpg ---->
            <img src="images/not-a-hipster.jpg">
            <!----------------------------------------------------------------------------->
            <p id="course-tile">DIY biodiesel small batch. Banh mi chicharrones lyft, retro you probably haven't heard of them lumbersexual la croix meh vaporware cardigan messenger bag. Tumeric butcher put a bird on it, subway tile gentrify austin pickled tousled. Health goth flannel organic, wolf yr viral chia iceland selvage salvia. Venmo tumblr jean shorts plaid literally gastropub, coloring book helvetica vice. Hashtag lomo forage direct trade VHS. Tumeric taxidermy single-origin coffee.</p>
          </div>
        </div><!-- end of middle -->
      </section>
```

### Resources
* [Web site for this course](https://netec-edx.github.io/github-training/ "Awesome Site!")
* [How To Install Git on your computer](https://www.atlassian.com/git/tutorials/install-git)
* [Introduction to Github for organizations](https://github.com/blog/674-introducing-organizations)
* [Managing Git in a team environment](https://www.sitepoint.com/getting-started-git-team-environment/)
* [Github Markdown Guide (to edit this page)](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet/)


But first, lets watch this excellent video: Introducción práctica a Github
---
<a href="http://www.youtube.com/watch?feature=player_embedded&v=Hd0B_AWv_Y4
" target="_blank"><img src="http://img.youtube.com/vi/Hd0B_AWv_Y4/0.jpg"
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

---
Terminal / Cmd commands to clone this repository to your local computer
```Bash
git clone https://github.com/Netec-edX/github-training.git
git branch [your-name-here]
git commit -m "comment"
git pull
git push
```
---
Terminal / Cmd commands to add your completed work to the Netec edX organization repository on Github
```Bash
cd / [path to your local repository]
git add .
git commit -m "add a comment explaining the nature of your changes"
git pull
git push
```
---
