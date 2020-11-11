---
layout: post
title:      "What I learned from building my first Sinatra app"
date:       2020-11-11 04:51:20 +0000
permalink:  what_i_learned_from_building_my_first_sinatra_app
---

It is pretty satisfying to see myself writing an app, with a database! 

After building my app, I got a better understanding what Sinatra and ActiveRecord do.

All parts of the project are important, and without one, the app will not work. Before building the app, I didn't know that sessions has to have a session secret for it to save [:user_id]. It took me about 3 days, 3 different tutors from the Q&A session to find out that I missed the session secret in my lab right before the project. And one of the tutors helped me go through the steps on using pry with shotgun. All these really helped me with my project, and the app came together quite easily. 

I had to figure out how to connect my stylesheet with views, like this:
    <link href="<%= url('/stylesheets/styles.css') %>" rel="stylesheet" type="text/css" />

I still dont' quite know why it has to use <%= %>...will keep that in my next time I need to do it. I spent quite some time on the views styling...not the main focus of this project, but I just couldn't stop myself styling them. LOL


