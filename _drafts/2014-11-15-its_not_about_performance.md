---
permalink: its_not_about_performance
title: It's not about performance
tags: [performance, ]
layout: post
---
Performance is not only about pure performance. It's a way to achieve goals, not necessarily a goal itself.

**TL;DR : blah blah blah**

A few weeks ago, I was speaking with my associate about a specific approach to a technical problem. While giving him arguments for a way to handle the problem, I told him that one benefit is that this approach is performant. His first reaction was : "I don't care. It's not like we are going to have performance problem for this project".

And he was right. Application is a small business web app, with low traffic and small expected database. Due to context, we can precisely estimate capacity planning for this project, and we won't have growth on the service. And the uses-cases don't require sub-100ms interactions. But he was also wrong (in a way).

**Performance**

I guess everyone knows about Donald Knuth's "Premature optimization is the root of all evil". I agree with this statement, especially with it's full context :

"We should forget about small efficiencies, say about 97% of the time: premature optimization is the root of all evil. Yet we should not pass up our opportunities in that critical 3%".

You should not try to optimize anything unless :

1. You did mesure that it's a critical/important performance bottleneck
2. You will benefit from this performance optimisation, it will fix something that would have been a problem

But performance can also lead to some interesting side effects.

**Customer comfort**

**Customer retention and convertion**

Amazon

**Have a wider customer base**

youtube
Africa, Asia, ...

**Lower operations costs**

More co-location
Docker
Less servers, less costs (especially ops)

**Robustness**

fast to restart
less costly to mesure
