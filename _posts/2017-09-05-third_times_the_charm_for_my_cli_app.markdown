---
layout: post
title:  "Third Times the Charm for my CLI App"
date:   2017-09-05 15:57:04 +0000
---


## Week 1
After finishing up the student scraper, I was very excited to start on my CLI App. I read through the instructions from start to finish, decided what I would scrape, looked over the code from the Student Scraper project and the World's Best Restaurant example and got started. 

Using the two examples as ways to structure my files and code, I got started fairly quickly and made some good progress. About 5 days in, I noticed another student on Slack comment about wishing they had watched the videos provided before starting their app. I also had not watched the videos (mostly because the lesson said they were a good thing to watch 'if you were having trouble getting started,' which I wasn't). I immediately started watching the videos and saw that all my files could be set-up by running bundler.

## Week 2
I decided to start over with my structure. I ran bundler, updated items to be specific to my app, then copied over my exisiting code. I was most uncomfortable with testing and debugging, but I just kept working through it.

I spent a week trying to finish up my project, but was really struggling with the scraping of my list (Rotten Tomatoes Top 100 Movies of All Time). I scheduled a one on one session with JJ Seymour and he helped me work through the scraping. We ended in a good place and investigations into pry appeared that the scraping would work. However, later that day, after debugging a few other items, I discovered that the scraping was only pulling 1 movie.

## Week 3

After trying several different scraping methods, nothing was working, so I set-up another session with JJ. After 30 minutes, we had gotten it to scrape 20 movies, instead of 1, but that was it. We ended that session with me looking to choose a different site to scrape. I reviewed several and chose a list on IMDB. I got to work scraping that list, while venting my frustrations to a classmate, Omar Donnadieu. 

Within 45 minutes, I had gotten the IMDB list scraping working and Omar told me he had the Rotten Tomatoes list working. So, I cloned my repo and tried out the code Omar had written. Sure enough, it was working. I couldn't decide whether to continue in the new direction or go back to the old direction. 

I decided to go back to the old direction. I started working on the detail scraping and was fairly confident it was working, based on results I was seeing in Pry. However, I couldn't fully test it within the full app experience because I couldn't get the app to load past the initial welcome message.

I had a check-in meeting with Ian Candy the next morning, so I explained my frustrations to him. He suggested moving the detail scraping to only scrap one movie at a time at the moment the user requests it. 

I gave it a shot, thinking that it would be harder than it ended up being and to my surprise, that was the last bug that needed fixing. It all worked!

Three repos, three weeks, and a whole lot of frustration later and it's done! And of course in hindsight none of it seems as hard as it did at the time.

![](https://imgur.com/a/wcP5A)
