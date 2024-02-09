---
layout: post
title: "A Better Approach to the 50-70 Rule for Takeoff Briefings"
date: 2024-02-08
tags: flying cfi 
---

#### Introduction

Have you ever heard of the [“50-70” rule](https://www.aopa.org/news-and-media/all-news/2023/june/pilot/flying-smart-reality-check) for planning your takeoff abort criteria? I find it to be an extremely common "rule of thumb" applied with the best intentions to pre-takeoff briefings. The goal is laudable: we always want to make sure we brief some kind of abort point and speed so that we are primed to take action in the event of anything out of the ordinary during our takeoff roll. 

For example, if you're burning up runway and are nowhere near the airspeed you need to take off, whether the problem is mechanical or otherwise, this should be treated as a "rejected takeoff" and the appropriate procedure should be followed to come to a stop on the remaining runway before damaging the aircraft or anything else in the airport environment (including the people onboard or nearby) should we overrun the runway. 

The rule is usually invoked in a typical pre-takeoff briefing as follows: “If I don’t have 70% of my rotation speed at 50% of the runway, I will abort the takeoff”. In other words, if you're taking off in a 172 with a rotation speed of around 60 knots, your abort speed would be 42 knots (or 70%), and your abort point would be (hopefully) some easily identifiable landmark along the length of the runway. But 50% of the runway and 70% of rotation speed? Where do we get these numbers?

The answer is physics! 

#### The Physics Behind the Rule

Recall the following basic kinematic relationship between distance traveled $$s$$ and time elapsed $$t$$, given the initial velocity $$v_{i}$$ and acceleration $$a$$ is

{% raw %}
 \begin{equation}
  s = v_{i}t + \frac{1}{2}at^{2}
 \end{equation}
{% endraw %}

where the acceleration is defined in the usual way as 

{% raw %}
 \begin{equation}
  a = \frac{v_{f}-v_{i}}{t}. 
 \end{equation}
{% endraw %}

Using the definition of acceleration to eliminate time from the first equation and solving for $$v_{f}$$ gives us the following relationship

{% raw %}
 \begin{equation}
  v_{f}^{2} = v_{i}^{2} + 2as.
 \end{equation}
{% endraw %}

If we now assume that we are starting our takeoff from a dead stop at the very beginning of the runway, then $$v_{i}=0$$ and we see that the square of the final velocity $$v_{f}$$ is proportional to the distance traveled down the runway

{% raw %}
 \begin{equation}
  v_{f}^{2} = 2as.
 \end{equation}
{% endraw %}

Thus, if $$s$$ is equal to the total ground roll required for takeoff, say $$s_{r}$$ where the subscript $$r$$ denotes "rotation", then $$v_{f}$$ would equal our rotation speed $$v_{r}$$. We can now take a look at what happens when $$v_{f} = 0.7 v_{r}$$, or 70% of $$v_{r}$$. In this case, plugging $$0.7 v_{r}$$ in for $$v_{f}$$ in the equation above, we find

{% raw %}
 \begin{equation}
  (0.7 v_{r})^{2} = 0.49 v_{r}^{2} = 0.49 \times 2as,
 \end{equation}
{% endraw %}

In other words, 70% of your rotation speed occurs at 50% of your ground roll because the square of 70% is 49%, or about 50%. 

#### So What's The Problem?

The problem is that if it really takes 50% of the available runway to reach your 70% abort speed you will theoretically reach your rotation speed exactly at the end of the runway, which an extremely risky way to fly. Now, its likely that most pilots out there don't realize this is the case, and I suspect if they did, they would immediately realize that the rule in question, blindly applied to the entire lenth of the runway, is not ideal. But there’s a better way.

#### The Better Way

Instead of using the halfway point of your runway as your de facto abort point, simply use 50% of the calculated ground roll from your preflight performance calculations. For example, in a 172, a ground roll might be predicted to be maybe 1000 feet on a particular day, given winds, density altitude, loading, etc, assuming we are using the takeoff procedure that corresponds to the relevant performance chart in the POH (typically a "maximum performance" or "short field" takeoff technique). 

In this case, with my 1000 foot predicted ground roll, [I'll add a 50% buffer](https://youtu.be/IMRafSuzkQ8?si=ufxqjHx6BQY4mrrD), bringing the grand total to 1500 feet. Then the 50-70 role suggests that I can expect to see my abort speed somewhere after 500 to 750 feet of ground roll. The trick here is that betting your life on adherence of your airplane on that particular day to the "book values" of takeoff performance is probably an unreasonable assumption, unless you're a test pilot taking off in a brand new 172 from the runway right off the Cessna factory assembly line. The point is that you have to know your airplane and your own skill level to make any truly reasonable selection of abort point and speed, but the 50-70 rule applied in this way is at least a decent starting point, and if the predicted 50% abort point with or without buffer gets you anywhere within 30-50% of the end of the runway, you would be wise to seriously reconsider proceeding with the takeoff. 

As they say, takeoffs are optional, but landings are mandatory!
