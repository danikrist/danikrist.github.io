---
layout: post
title:      "Tackling the Sinatra Portfolio Project"
date:       2017-11-15 06:33:48 +0000
permalink:  tackling_the_sinatra_portfolio_project
---


Day 1 - Getting Started - October 23

Spent the weekend thinking about what I wanted to do. Decided to continue the theme of my CLI project by creating a Sinatra app to track movies I want to watch. To get started I talked through the user experience with my husband, created a diagram of my classes and their relationships and attributes, opened my Github Repo, and created my project to do list. Next, I am going to write out the user experience and file structure, write some some basic test notes, and build the file structure. The project requirements do not include writing tests or CSS, but I want to practice and try out using CSS grid.

Day 2 - Getting Organized - October 24

My husband is a web designer, so he talked through his company's process with me. I was curious about how they handle pass-offs from each team and what type of documentation gets created. I am thinking about adding some user stories to this project, but am following the recommendation of one of the Flatiron instructors to get the base done before adding all these extras. So, I created a user flow diagram definig the pages/routes I will need. Next, I created my file structure and started populating some of the ancillary files like the gemfile, rakefile, environment.rb, and config.ru. I also defined the classes in my models. Tomorrow I should be ready to write the migrations and start the controllers and views. 

Day 3 - Preparing RESTful routes - October 25

Today was a long day with not much time for coding, but I did want to get some stuff in, so I started with my migrations. I created my migrations and then set-up the associations in my models. After that I put dummy content in all of my views. Next, I set-up my controllers with all the RESTful routes I had defined in my diagram. I ran shotgun and testing that all of the routes were correctly displaying the dummy content. They were! Yay! Now that my data structure is in place and my route framework is set-up, I'm ready to start coding out my views and controller actions.

Day 4 - Form Best Practices and Flash Messages - October 26

I decided to start with my Users Controller. I looked into some [best practices](https://www.sitepoint.com/html5-forms-markup/) of HTML5 forms. I learned how to make fields required and that adding label elements for your inputs it helps screenreaders. Yay for accessibility! I coded out my sign-up and login form views and added controller actions for signing up, logging in, and logging out. I decided to add in the flash message element that was introduced in the Playlister lab to my '/login' post action, so that users will know when they have entered incorrect log-in information. After some shotgun testing and minor debugging, my User Controller is in fairly good shape. I have not been committing changes as ofter as I should, so been focusing on that as well. Next up is the main event--creating, showing, editing, and deleting movies!

Day 5 - Getting to the Meat - October 27

Started coding the new and edit forms today, along with their corresponding controller actions. This has really made me think about the User Experience. In previous labs, I was trying to fulfill all the test requirements. Now, I'm thinking of what does and doesn't make sense for the user. So, I've added a note to the '/movies' index when there are no movies with a link to add a movie. I've also added 'edit,' 'delete,' and 'back' buttons to the '/movies/:slug' page. I was exploring some of the HTML5 button attributes and am trying to use the 'button' button attribute, but that is currently not working, so will need to do some more research there. I also added functionaity to prevent a user from adding the same movie twice, with a flash message that the movie exists. I have also been experiementing with the order of controller actions since order matters! 

Day 6 - Taking a Day Off (Kind Of) - October 28

Today is the Saturday before Halloween, so there were a lot of social activites to attend and errands to run. I did make a little time to code though. I figured out my cancel button issue. I also had my husband try out the app to watch someone else work with it. Next, I'm going to try to implement some functionality to let users only view their watched or unwatched movies.

Day 7 - Taking a Day Off (For Real) - October 29

Day 8 - Figuring Out Next Steps - October 30

Did not do too much today. I reached out to Ian Candy, an instructor I meet with regularly. He encouraged me to take next steps in the things I am most interested in, which is everything, because I think it is all important. I don't have the UI design figured out yet, so I think I'll start with tests. I'm a little nervous about some of the features I want to add, like sorting by genre or adding movies based on a scraped list.

Day 9 - Writing Tests - October 31

Halloween has really got me distracted! Although, I did make some time to write some tests today. I did not write them from scratch, but copied them from a previous lab and edited them. Although they are not entirely my own, editing them did give me a sense of how they are written and how to understand them. I will need to wrap up a little work on them tomorrow. I am getting a lot of errors about finding buttons, so going to look into that.

Day 10 - Prepping for CSS - November 1

Did some research on adding CSS to Sinatra. Worked on getting my files ready to go and testing them by adding a global sans-serif font-family. Got that working so I am ready for design.

Day 11 - Thinking about Functionality - November 2

Two of the features I've thought about adding are using scraped data to give users a list of movies to add to their list from and creating a dropdown list that a user can filter their index page by. I'm a little unsure about how to go about these. I've done some research on the dropdown list, but all the examples I've found are more Rails focused. So, trying to think of other ways to do that. For the scraped data list, I've spent some time reviewing my CLI project to determine which methods I would need. As I've reviewed that I've become a bit confused on how I'm going to structure this data in this project. So, I'm taking a break from thinking about it and created a new branch so I don't mess up my existing project. Also spent some time researching how to fix the test issues, but no luck there yet either.

Days 12-15 - Stuck - November 3-6

Thinking about where to go next and feeling intimidated by trying things that I'm not too sure of has had me stuck for the last few days. I'm rethinking how much extra work I am going to do.

Day 16 - Getting Unstuck - November 7

I feel guilty about dragging my feet on this project for so long. I want to be able to dive in a figure anything and everything out that I want to create. However, realizing that I want to actually finish this project at some point soon and that some of my ambitions were hindering my progress, I decided to start small. So, I jumped back into my tests and worked through each one individually until they all passed. Then I started in on the CSS. I picked a font to use from Google Fonts and added it in, along with some sizing. The CSS changes were not showing up. I wasn't sure if it was just a lag or a caching issue, because I tested the CSS when I set-up the file to make sure it was connected right. So, I tried it out in a different browser and it worked! I'm going to think about it a bit more, but I may try to wrap up the CSS tomorrow and skip the additional features I was thinking of.

Day 17 - Fiddling with Design - November 8

After deciding to scale back a bit, I worked on some CSS today. I have no idea how to design. I've added some basic colors, margins, and cool button hover states, but it's still really boring. It's in a place where I could turn it in, but I'm disappointed that I fell so short of the goals I had set for myself. I wanted something where I felt like I understood tests and CSS better and had a little more functionality than the base requirements.

Day 18 - Getting Professional Help - November 9

My husband is a great web designer. So, I asked him to help me with the design of my app. He cranked out a beautiful interface in 45 minutes. It took the look of my app from a 2 to a 10. I started on some of the CSS coding and am going to jump in more tomorrow. Definitely the hardest part was getting the background image linked in right. I still struggle with relative and absolute paths sometimes.

Day 19 - Movin' on Up - November 10

After getting a schmancy new design, I decided my CSS could use some reorg. It was a combo of what I had done previously and what I started writing yesterday. So, I listed out all the elements on each page and started from scratch. I'm sure it's no where near as clean as it could be, but it's much better than it was. I've implemented most of the base CSS and now it just needs some finessing. I don't want to spend more than 3 weeks on this project. I originally only wanted to spend 2. So, tomorrow my focus will be building the filter function. Then Sunday, will be any final CSS work. I am officially giving up the idea of connecting it to the scraped data from my CLI. Also, I started looking up RESTful routes for filters and it looks like query strings may be the way to go, so I'll be looking into that. And bonus! I actually ended up using CSS Grid on a few of my pages, like I wanted to. It really is great.

Day 20 - Getting Stuck Again - November 11

Got some good coding time in today. I started to try my filter feature. I was able to get dropdown menus up and have them get passed into a query string, but I am stuck now on getting those query string values to actually show filtered data. Google was not much help, so I've reached out to an instructor, set-up a help time, and joined a study group in hopes that I can get this wrapped soon. Since I could not make much more progress on that front, I reviewed the CSS with my husband and he gave me some tweaks. It is looking really good with the exception of the log-in and sign-in pages having a scroll without needing one, so hopefully can figure that out, but so far, none of my troubleshooting has worked. As soon as the filter feature is working, I can tweak CSS on the Movies Index page and then write my README and record my video. If I can't get the filter feature working by Wednesday, I am taking it out. I was really hoping to be able to get this done tomorrow.

Day 21 - Slow Going - November 12

After quite a bit of troubleshooting, I couldn't figure out my filtering issues, so I did a little more CSS tweaking. I was also embarassed by my code formatting, so I installed 'Beautify' on Atom and ran that on all my views. I hate being stuck.

Day 22 - Back on Track - November 13

I head back from Ian, my instructor, today. He passed along a RailsCast that helped change how I was thinking about it. I moved all the logic from my view to a class method in my Movie model. After some tweaking to that and my view and controller it worked! Yay! You can filter by genre. Now I need to figure out how to also add in filtering by status, fix some CSS issues, get rid of the 'submit button' (so it filters after you make your dropdown choice), and get the dropdown menu to stay on the option that was selected instead of reverting back to 'all.' I have a really busy day tomorrow, but have a 1:1 at 6:30 pm, so hopefully if I can't figure it out before then, the instructor can help me along.

Day 23 - Finishing Up - November 14

I had a couple epiphanies last night in the middle of the night about how to fix my issues, so I wrote them down. I implemented to them, and realized that my status filtering wasn't working due to my logic comparing an integer to a string. I was able to get the dropdown menu to stay on the selected option, however I can't figure out how to submit the dropdown value without having a submit button. I am going to call it good on this project, since I've done most of what I wanted to and it's looking good. I just need to wrap up some test tweaks, my README, record my video, etc. So, I'll try to do that tonight.


