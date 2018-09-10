## VOLUME COPY README V1.0


### Description
---
This project was an attempt at utilising HTML, CSS and Twitter Bootstrap to emulate the front page site for the Volume Network. (<https://volumenetwork.com/>). 

### Tech used
---
#####Languages
This project utilised basic HTML5 and CSS3, as well as the Twitter Bootstrap API. Git was used to traverse file structures and connect with GitHub
#####Environments
The majority of the programming was done inside the Atom text editor. MacDown was used in the creation of this ReadMe. GitHub was used to establish development branches and version control. The terminal was also used 

###Challenges
---
The main challenge in replicating the website front page was the section containing a multi image carousel. Ovveriding the default Bootstrap stylings in order to better fit the required images within the carousel was quite difficult, and I found it hard to locate the cause of the problem. Eventually however, this issue was located and corrections were later made.

###Takeaways
---
This project allowed me to get further practicing the use of the Bootstrap API. On top of this, I was finally able to get a hold on overriding bootstrap to allow for an extra level of styling. Whilst I encountered a few issue points, mainly based around the carousel, I was able to build upon my knowledge base and solve them. As such, I gained a greater understanding for the languages used.

###GitHub links
GitHub Repo: <https://github.com/samGilbert95/sparta-bootstrap-page-copy/>

Github Pages: <https://samgilbert95.github.io/sparta-bootstrap-page-copy/>

###Codeblocks
---
#####HTML Example Code
######Carosel  Code
```html
</section>
  <!-- Carosel -->
  <section class="caro">
    <div class="container-fluid">
    <div id="carousel-example-generic" class="carousel slide" data-ride="carousel">
      <!-- Wrapper for slides -->
      <div class="carousel-inner" role="listbox">
        <div class="item active">
          <div class="row">
            <div class="col-md-3">
              <img src="https://www.placecage.com/300/300" alt="...">
            </div>
            <div class="col-md-3">
              <img src="https://www.placecage.com/300/300" alt="...">
            </div>
            <div class="col-md-3">
              <img src="https://www.placecage.com/300/300" alt="...">
            </div>
            <div class="col-md-3">
              <img src="https://www.placecage.com/300/300" alt="...">
            </div>
          </div>
        </div>
      </div>

      <!-- Controls -->
      <a class="left carousel-control" href="#carousel-example-generic" role="button" data-slide="prev">
        <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="right carousel-control" href="#carousel-example-generic" role="button" data-slide="next">
        <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
    </div>
  </section>   
```
#####CSS Example Code
######Carosel CSS Stylings
```css
.caro{
  padding: 20px;
  border-top: 2px solid black;
  border-bottom: 2px solid black;
}
.carousel-inner{
  background-color: #fff;
}
.carousel-indicators li{
  background-color: black;
}
.carousel-indicators li.active{
  background-color: black;
}
```

###Download Instructions
----
These instructions assume that the user has a GitHub Account and Git installed on their terminal. In case these assumptions are incorrect, resoruces for installation are provided below.

Git Installation:<https://gist.github.com/derhuerst/1b15ff4652a867391f03>

GitHub Signup: <https://services.github.com/on-demand/intro-to-github/create-github-account>

##### Step 1: Clone Repo
-
Go to <https://github.com/samGilbert95/sparta-bootstrap-page-copy> and
##### Step 2:	CD into terminal
-
Copy the project into the chosen directory using the Git Clone Command

---
###### Author:	Sam Gilbert



