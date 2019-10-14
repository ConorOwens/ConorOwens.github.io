---
layout: post
title:      "Sinatra Project Blog Post"
date:       2019-10-14 03:03:45 +0000
permalink:  sinatra_project_blog_post
---


This one was a doozy. I learned a lot about Sinatra and ActiveRecord and the power of associations. Not least of all I learned a lot about the value a second set of eyes has on a coding project.

A lot of the struggles I faced when doing this project centered around some of the 'magic' that happens behind the scenes. We've jumped into another layer of abstraction with this project, and I found a lot of the time I spent researching I was searching for answers to question about what things REALLY did. Activerecord and associations are POWERFUL tools, but if you don't have a firm grasp of them, it can be a real bear trying to figure out what exactly is happening in your code. More importantly, it can become very difficult to parse what is going WRONG in your code.

I fought for a while with sessions. My sessions hash code as I understood it looked fine. I fought for almost two hours tweaking and retweaking things to make sure I was pulling only the information I wanted and making it persist, but nothing in what I researched or tweaked fixed my problem. My sessions hash simply wasn't pulling and populating information, and that made it almost impossible for me to seperate data between users who were logged in and who weren't. Sure, it was doable, but I knew the sessions hash worked much neater and nicer than any of the monkeying around I was resorting to. At about the two hour mark, someone from the cohort reached out to me.

They'd seen me in class talking and answering questions, and had reached out to me to try to help them solve an issue they were having with passwords. At that point I really started to understand the value of a coding community, and how being seen and active in that community could really help me personally. It was a simple fix and after soem trail and error we parsed what was going wrong and snipped the offending code, and then I turned to THEM for help with my sessions issue. Having that second set of eyes helped me quickly, but it was frustrating at first.

You have to be really vulnerable in those situations. Someone else is poring over your work and judging what works and what doesn't. We fiddled with a lot of the fixes I'd tried before, and it was reqarding to see someone else as frustrted as I was. At least I wasn't crazy. But eventually the problem was discovered in my configure method. I hadn't actually ENABLED sessions. It was like putting coffee in the grinder, grinding it, putting in a filter and water, and then being frustrated coffee wasn't being made when all the while the maker was unplugged. I felt really stupid in that moment, but it helped me see we all need help sometimes and having a comunity at your back to bounce off of can be an incredible asset.

There were one or two more major hiccups but I was much quicker to ask for help, and as a result those problems were much easier to solve. It was hard for any one student to ENTIRELY grasp the intracacies of what was happening with these methods behind the scenes. When we worked together, we covered each other's gaps and as a team it was easy to figure out solutions.
