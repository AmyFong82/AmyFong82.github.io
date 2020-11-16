---
layout: post
title:      "Test Driven Development"
date:       2020-11-16 04:52:25 +0000
permalink:  test_driven_development
---


I was following along in this lab: ActiveRecord Models and Rails, and had started to run the rspec tests as instructed in the lab. However, after getting: "No Examples Found" for 3 times in a row in the first 3 consecutive steps, I started to wonder what went wrong with my steps...I was following along, and had read the steps pretty carefully...so I re-read the steps again, still couldn't figure out what was wrong, but I thought it must be something related to some config files or gems... these parts are the scariest parts...So I asked for help in "Ask a Question". 

Kai at "Ask a Question" asked me to copy my error message for him, so I did. And before he could respond, I saw that my terminal's location was in the app/models directory, not the root directory of the lab. So, I went to the root directory and ran the test again, and this time it worked! I faintly remember that somewhere in the beginning of the course, when testing were introduced, we were reminded that we have to be in the root directory of the lab to run the test, and I had been doing that all along with no problem.

But, tonight, I tried to create new files with my terminal, which I haven't done in a long time, and forgot to go back to the root directory before running the tests...Lucky for me that it didn't take a long time, and I learned a lesson. Hopefully I will remember it after this embarrassment. 😅
