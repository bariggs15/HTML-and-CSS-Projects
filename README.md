# HTML-and-CSS-Projects
# LiveProject


## Introduction
The final two weeks of the Tech Academy were spent as a team with fellow peers, utilizing skills learned to  develop a fully functional MVC Web Application using C#, HTML, JavaScript, CSS, etc languages. It was a great opportunity to see how Scrum-style coding works and how important it is to be responsible when working in a team setting where everyone is dependent on each other. I worked with both [back end stories](#back-end-stories) and [front end stories](#front-end-stories) with varying degrees of difficulty. It was an opportunity to work on planning and developing code, fixing bugs, and utilizing resources available to progress the project. 

Below are code snippets and descriptions of code that I worked on with full files availabe in repo. 

## Back End Stories
* [Creating a Comments Section](#Creating-a-Comments-Section)
* [Like Dislike Features](#Like-Dislike-Features)

### Creating a Comments Section
This website required a comments section in which the users could write a review of the shows/performances. Some of the features involved were required to put in a shared cshtml partial view to be used by other team members. This section allowed me to get my bearings on the project and the MVC style involved. 

    @model IEnumerable<TheatreCMS3.Areas.Blog.Models.Comment>

    @{
      ViewBag.Title = "Index";
    }

    <h2>Index</h2>

    <p>
      @Html.ActionLink("Create New", "Create")

    

