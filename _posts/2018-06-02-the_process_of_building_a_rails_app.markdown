---
layout: post
title:      "The Process of Building a Rails App"
date:       2018-06-02 04:27:23 +0000
permalink:  the_process_of_building_a_rails_app
---


I'm partway through my Rails Portfolio Project and even though I feel I have a decent grasp of Rails, I keep stalling out. Every time I sit down to work on my project, I spend more time trying to figure out my next steps than I do actually working on my project. So, today, I am going to attempt to define my own roadmap to follow. Buckle up.

**Leg 1: Ideation (Thinking and Talking)**
   1. What is the app?
   2. What are the main and secondary objectives of the app?
   3. What will you call the app?

**Leg 2: Definition (Writing and Mapping)**
   1. What models will you need?
   2. How are your [models associated](http://guides.rubyonrails.org/association_basics.html#the-types-of-associations)? Draw a diagram.
   3. What other data points will your models capture?
   4. Which data points will be required and which will require specific formats?
   5. Which [RESTful routes](http://guides.rubyonrails.org/routing.html#crud-verbs-and-actions) will you need?
   6. Will you have multiple user roles?
   7. What features do you want to include?
   8. Research [gems](https://github.com/markets/awesome-ruby) that you might use for testing, user roles, features, etc. to find out if there are any specifics to be mindful of as you set-up your models (i.e. using Devise to support user authentication will set-up your user migration, so you should to install it and then add any custom attributes rather than creating your own user migration)
   9. If there is anything you are uncomfortable with or not sure how to accomplish, write down your questions, do some research, and make notes of sites you find helpful.

**Leg 3: Set-up (Laying the Foundation)**
   1. [Generate](http://guides.rubyonrails.org/getting_started.html#creating-the-blog-application) your app `rails new [name of app]`
   2. [Create your GitHub repo and connect your app](https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/)
   3. Install any gems you will use (especially for testing) and run bundle install
   4. Don't forget to add, commit, and push your work to GitHub
   5. Generate a resource for each of your models to get a model file, a controller file, a migration file, and the resource added to your routes.rb
   6. Review, finalize, then run your migrations.

**Leg 4: Seeding/Writing Tests (Preparing to Build) **
   1. Stub out all of the tests you want to write
   2. Write tests for your models (tests should include that the model is valid, validations are happening, and associations are correct)
   3. Write tests for partials or helpers (like signing in, signing up, headers, footers, etc.)
   4. Write tests for features/controllers/views 

**Leg 5: Building (Writing Code)**
   1. Write model associations
   2. Write model validations
   3. Write any model specific methods
   4. Run model tests > debug > repeat
   5. Set-up controller actions and view pages
   6. Put in basic headers for each view page and make sure they are all working
   7. Begin building out controller actions and views starting with lesser associated models and working through to more core models
   8. Add any helper methods you need
   9. Run feature tests > debug > repeat
   10. Review controller actions against routes and make sure you are not allowing any routes that you don't have actions for in your controller

**Leg 6: Adding Features (Bells and Whistles)**
   1. Once the core of your app is completed and working, identify other features you wanted to incorporate (for me this might include image uploading, geolocation, having users confirm emails, etc.)
   2. Review any documentation you found in your initial research
   3. Install any gems you may need
   4. Write any additional feature tests you may need
   5. Generate migrations for any additional data types
   6. Write the code for your features
   7. Run feature tests > debug > repeat

**Leg 7: Design (Beautification)**
   1. Think about the look and feel for your app
   2. Sketch out the look
   3. Identify colors and fonts you will use
   4. Create your CSS file
   5. Define your font and global styles
   6. Style partials (headers, footers, forms, etc.)
   7. Style specific elements
   8. Add any responsive styling

**Leg 8: Finalizing (Dotting the i's)**
   1.  Look over your code, is it DRY?
   2.  Review routes, have you locked down any routes that you don't utilize?
   3.  Review files, are there any that you don't need? 
   4.  Rerun all tests  > debug > repeat 

**Leg 9: User Testing (Final Check)**
   1.  Walk through your app yourself on a couple different browsers
   2.  Do instructions and forms make sense?
   3.  Try entering in some incorrect info or leaving required fields blank
   4.  Are there appropriate error messages when needed?
   5.  Have a friend walk through your app. Watch them, see where they seem confused or stuck. Ask for their feedback.

**Leg 10: Requirements Specific to This Project (Passing)**
   1. Make sure you've recorded the 30 minute coding video
   2. Write a blog post on your project
   3. Record the 30 min walkthrough
   4.  Write the README.md
   5.  Add and check off the [spec.md file](https://github.com/learn-co-students/rails-assessment-v-000/blob/master/spec.md)
   6.  Fill out [this form](https://docs.google.com/forms/d/1QlU2-UQNSjlv2Tf2yP8oDsduMobK_1w0ZFXaTpywMCk/viewform?edit_requested=true)
   7.  Submit all your links




**Update**

I'm now nearly done with my project (fingers crossed!). I've now been working on this project for a month and a half!!! It is significantly scaled down. The fact that it has taken me so long and is no where near what I was hoping it would be makes me feel like I have failed. I started out wanting to build a small business directory that was fully searchable, had geolocation, images for all businesses and products, a full test suite, and some beautiful CSS. But, it's been a struggle. Trying to write tests first caused me significant delays. I was uncomfortable with them and would just stare at my screen every time I tried to write them. Scrapped. I decided to add the images, geolocation, and CSS last, but now that it's taken me so long, I just want to finish as soon as I can. Scrapped. Scrapped. Scrapped. The search is TBD. I am set on turning this project in within the next three days and the search is only partially working, so that may go too. I will be glad to move on. I may add more later, but probably not. It is so far from the vision that it doesn't feel worth it. I guess that is learning though. Sometimes you can't do it all and that has to be okay. Next time will be better.
