## Week Three - Journal

### Ruby topics you've mastered
*  This morning, I learned a specific bit of code to create an array and then to randomly select something
   from that array.  For example:
   *  %w(mark, leslie, heidi, john, devan, erik)[rand(6)]
   *  This will randomly pick one of the six names from the array. 
*  I have a decent understanding of high-level functioning of projects.
   *  i.e. for certain web server projects you need the following files (controller (ruby), templates(html files), 
     a database file.
   *  also for these types of project you need some sort of styling that can come in the form of a css file, or
      maybe even a ruby gem.
  

### Ruby topics you're struggling with
*  I am still struggling with writing functional ruby code.
*  I still need practice using most methods.
*  Ruby syntax


### GitHub and its shiny buttons
*  Last week's tutorial from Brian on how to use the command line for GitHub actions helped me tremendously.
*  I now feel more confident (but not totally confident) on using GitHub in this way.  

### Personal retrospective
*  After the weekend assignments I always seem to feel dejected because I am having difficulty arriving at
   the correct code on my own.
*  This week's weekend assignment felt a little beter to me bacause I was able to get some of the specs to function.
*  When I feel dejected I start to wonder if I am cut out for all of this.
  *  When I get to feeling this way, I have to rely on my maturity to step back and remember that I have to keep 
    perservering.  Just keep trying, to learn something new.  Just keep trying to learn something new.
    

### Things about the class that have surprised you
*  I am kind of surprised, but probably shouldn't be by how much I need to depend on my own ability to find
   answers on my own. 
   
### Rails - the good, the bad, the magic
*  Routes  
   *  On my own this weekend, I discovered that using 'resources' with the name of the controller
   will create your routes for you.  And that if you are using a second database, you just use 'resources' and
   the name of that controller nested inside of the first.  This will create all of your routes for those two
   the actions in those tow controllers.
   *  The good news about this is that it makes my life easier when it comes to creating routes.
   *  The bad news is that I do not have a good grasp of what is going on under the hood when it comes to routes.
     *  I need to learn that!
*  MVC
  *  Model - Ruby classes that talk to the database.  They store data.
  *  View - Templates -- These are the things that are displayed by the web browser
  *  Controller -- handles requests from the web browser and then performs actions on these requests
*  helper methods (form_for, link_to, _path, ...)
  * form-for -- ruby code that is inserted into an html.erb template that creates a form based on specified
    attributes.
  *  link_to -- creates a link tag using a certain url
  *  path -- a suffix telling where the path is going to.  The prefix is the actual route.
