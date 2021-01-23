---
layout: post
title:      "Rails App with OmniAuth"
date:       2021-01-23 05:03:59 +0000
permalink:  rails_app_with_omniauth
---


This blog is about my process doing the Rails Project for Flatiron School Online Engineering course.

It's a long process...I was hoping it could finish it in a week, maybe 2 weeks...but it actually took me more than 3 weeks to finish it!!!

Lots of obsticles along the way, and I learned a lot from doing the project. But still, some problems I cannot figure it out, and just had to copy from other projects, got it working and move on with it.

Here are the big problems that I ran into:

1. I didn't quite fully understand the activerecord associations, and what join tables are in real life. I spent too much time thinking for the idea for the project, trying to think of something interesting, and also fulfill the activerecord requirements...but in the middle of doing the project, I realized that I'd got the models relationships wrong/missing...so I had to redo my models after working on them for probably a week. But at least, I think I've figured out how the activerecord associations works now.

2. I couldn't get the OmniAuth to work with my app. I did everything the lab that teaches us how to get OmniAuth to work with GitHub, try to match all the gems that I thought were related to the topic, did it multiple times, copy and paste...worked at it for 2-3 nights, didn't work. So, at the end, I had to copy my codes into the OmniAuth lab folder, and it worked...so I still don't know which part of the code is missing in my original app.

3. And then, since I moved my working app to another folder, I had to figure out how to push my new folder to GitHub where I saved my original work...it took me a while too...and also, because of that, or whatever, my files in the Git Repo is ahead of my files in my computer. So, I had to figure out how to solve this problem, because they won't let me push if the Repo is ahead of me...I didn't know that! I solved these 2 problems! Yeah!!

4. Oh, and also the DateTime, Date and Time in Ruby also confused me too. So, they are all objects!! I didn't know time can also be an object! It's good to know, and good to find out about it. I found out about it because my form couldn't store and reuse the string of time that I put in there when error happens during validation. The date_field and time_field will clear my date and time if I store them as string.

OK. At last, I finished the project! I hope it will pass the review. I am excited to move on to the next Module, and hope I can move faster and finish my study before my time is up!

