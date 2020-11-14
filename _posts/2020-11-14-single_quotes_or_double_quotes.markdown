---
layout: post
title:      "Single Quotes or Double Quotes"
date:       2020-11-14 05:28:01 +0000
permalink:  single_quotes_or_double_quotes
---


I didn't know that only double quotes allow string interpolation before I did google search for the difference between single quotes and double quotes. In one of my early Sinatra labs, I thought single quotes and double quotes work the same in ruby, so I didn't pay much attention to which one I use.

But then when doing routing, when interpolation is present in the route, single quote won't get me where I want to go.
For example:
redirect 'owners/#{@owner.id}'

It only works when I use double quote, like this:
redirect "owners/#{@owner.id}"

I didn't know the reason why in the beginning, I just use double quote for all the rendering and redirecting. I thought it was how the language was written. :P

Now I know. Thank you for asking that question Dougui, and thank you for answering his question, stackoverflow users.
Here's the link to the question:
https://stackoverflow.com/questions/11760690/why-everyone-use-double-quotes-instead-of-simple-quote/11760836#11760836
