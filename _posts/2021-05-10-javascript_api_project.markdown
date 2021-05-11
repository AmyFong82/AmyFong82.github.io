---
layout: post
title:      "Javascript API Project"
date:       2021-05-10 14:41:46 -0400
permalink:  javascript_api_project
---


I'm finally done with my first Javascript API Project!!!

It's a long process, and I learned a lot, and got lots of practice with Javascript controlling the DOM, and got familiar with the fetch function.

In the planning of the project, I wasn't sure what an API is...it could be some info or some app, I spent about 10 days trying to make an app that would need secure user login, which the rails API framework is not designed to do, even though people can still do it, but not in my current ability because I couldn't figure out how to send cookies through fetch...I had to give up after 10 days of research.

Then I started with my second try: a Sight Word Practice Game for Toddlers. I want the users to be able to track their progress if they don't want to finish the whole game in one try, so user info storage is still necessary. I decide to go with the local storage. Since it's just a game, and nothing really personal or important is being stored, I feel comfortable with exposing the user info in the local storage.

But the "preventDefault()" also threw me off, and I took about 2 days to figure out what is wrong with the user login when they submit the form. I used the HTML5 default form validations, so when I use preventDefault() in my js, it disabled the HTML5 default form validation from working. I didn't know it was a problem, but finally figured out I can check if there's anything entered by a user before running the preventDefault().

I'm very happy to have learned so much from doing this project, and am excited to learn more in the coming sections.
