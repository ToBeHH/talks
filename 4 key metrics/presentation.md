title: 4 key metrics framework
class: animation-fade
layout: true

---
class: center, middle, fullscreen_gift

# Gift

.footnote[Image from https://www.maxpixel.net/Substances-Pack-Loop-Gift-Give-Fashion-Jeans-1420830]

???

Today I brought you a gift. 

The gift of knowledge.

The gift to know, how good you and your team actually are.

---
class: center, middle, fullscreen_tracking

# Who is tracking yourself?

.footnote[Image from https://www.maxpixel.net/Race-Athlete-Run-Athletic-Sprint-Running-Sports-1245640]

???

Who of you is tracking your fitness? Or your steps? Hands up.

And who is tracking your performance in your professional live? 

Why don't you do that in your professional live? Why don't you track your progress there?

---

class: fullscreen_hard

# Tracking is hard

.footnote[Image from https://www.maxpixel.net/Work-Man-Industry-Worker-Construction-Worker-569126]

???

I know why. Because it is hard. There is hardly any metric out there, which is good. 

Why?
Usually, if you measure something, you look at the inventory. In manufacturing you look at what is going in and what is going out.

This cannot be applied to software development. The invenotry there is invisible and it does not make sense to count it.

---


.center[![Book cover‚ Accelerate](book_cover_accelerate.jpg)]

???

Until now. 

Nicole Forsgren, Jez Humble and Gene Kim conducted a study over 4 years. They collected about 23.000 responses from developers from over 2.000 different companies and they had been working on the data. The study is called [State of DevOps report](https://devops-research.com/research.html) and the results are available in that book "Accelerate".

The have found 4 key metrics, which actually are a good way to measure the team performance and those metrics support each other.

---

class: with-hexagon

# The 4 key metrics

???

Let me go over those metrics.
--
## Deployment Frequency

???

The deployment freuqency is the number, how often you deploy over time. 

But why is it a good metric? What are we actually measuring?

You can only deploy often, 
* if you have good developers to produce features to deploy
* if you have good testing in place, so that you are confident that you don't ship crap
* if you have good team communication in place, so that not someone accidently commits bad code

Therefore deployment frequency is also a good indirect measure for your team.

--
## Lead Time

???

Lead time is the time how long it takes between writing the last line of code to bring the code actually to production.

Again this is a good indirect measurement about the effectiveness of your deployment process.

--
## Change Fail Percentage

???

The change fail rate is the number of times, you deploy an error to production vs. the total number of deployments. 

This is a good indication of the quality of the overall development process. 

And it closely related to the next one.

--
## Mean Time To Recover (MTTR)

???

The mean time to recover is the time it takes to recover from such a bad deployment to production.

This is an indirect measure for the code complexity.

---
class: empty-slide
background-image: url(Cycle_1.png)

???

Another good thing about all those 4 metrics is, that they support each other.

So starting off with the lead time...

---
class: empty-slide
background-image: url(Cycle_2.png)

???

In order to improve your lead time, you need to write cleaner code and focus more on the work that you actually need to do.

When you have accomplished this, you automatically will deploy more often, because you can.

---
class: empty-slide
background-image: url(Cycle_3.png)

???

If you deploy more often, you might want to improve your automation. That means, having automated tests, having an automated deployment pipeline, etc.

If you do that, you automatically will have a shorter mean time to recover.

---
class: empty-slide
background-image: url(Cycle_4.png)

???

In order to improve your mean time to recover, you might want to improve your monitoring, so that you detect defects earlier.

Maybe you can spot then errors already in a preview environment, so you end up with a reduced change failure percentage.

---

class: empty-slide
background-image: url(Cycle_5.png)

???

And in order to further improve your change failure percentage, you need to improve your practices in your team, for example enhance the communication within the team.

And this then leads to a reduced lead time.

---

# Additional benefits

- You can do better at _all_ of these measures at the same time.

- In order to improve on those metrics, people have to work together.

???
There is that old belief, that there is a tradeoff between improving performance and achieving higher levels of stability and quality. This study has profen that wrong. Actually, you can do better at _all_ of these measures.

---
class: fullscreen_traveller

# Experiences

.footnote[Image from https://www.maxpixel.net/Backpacking-Walking-Hiker-Travelling-Backpacker-1149877]

???

First, it was easy for me to gather those metrics from the tools we have in place.

Second: In my team, we use the 4 key metrics framework to track our progress. We did not change you processes. But now we can see, what effects the changes have, we discuss in our retros. 

Additionally I am about to use the data to get rid of estimations and use the metrics instead to predict the future. The keyword here is noestimations.

---
class: thankyou

# Thank you
## for your attention!

Tobias Schulz-Hess

[<i class="fas fa-envelope"></i> tobias.schulz-hess@xing.com](mailto:tobias.schulz-hess@xing.com)

[<i class="fab fa-twitter"></i> ToBe_HH](https://twitter.com/ToBe_HH)

???

I am Tobias, I work at XING. Contact me, if you want to know more. Thank you very much for your attention.
