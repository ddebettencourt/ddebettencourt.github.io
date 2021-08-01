---
title: The Emotional Cost of COVID-19
tags: "World"
---

For vaccinated people, the COVID-19 pandemic has mostly ended in the US (concerns about the Delta variant, etc. aside), which means it's a good time to look back at how it's gone. Clearly, our response left things to be desired, and there are many things we could have done better, but when we look at how we did, it's often looked at through one of two lenses: either how many deaths we could have prevented, or how much economic loss we could have prevented. While these are valid and important ways to look at the situation, I want to look at it from a different perspective - from the perspective of the millions of people that reduced their social interactions, avoided large gatherings, and hurt their mental health over the past 16 months. What exactly have we lost from these emotional costs? How many lives need to be saved to make these emotional costs worth paying?

<h3>The Value of a Life</h3>

In order to properly make this comparison, we're going to need to have some idea of the value of a human life. Not the economic value, but a different sort of value - something that we can compare an emotional cost to. 

When thinking about how to make this comparison, one of the first ideas that I considered was to simply value every life equally. After all, we are all created equal, right? Well, this quickly runs into issues because I wouldn't value the life of an 85-year-old and a 25-year-old equally. I think most people would agree with this differentiation, including many 85-year-olds. Someone who is 85 has lived a full life, and has experienced more than a 25-year-old, who has much of their life ahead of them. So we should differentiate value by age. The way that I'm going to make this differentiation is by using the official [US actuarial life table](https://www.ssa.gov/oact/STATS/table4c6.html), which gives the expected number of years remaining for people at any age. Using this system, I can determine that a 30-year-old, for example, who has about 50 years remaining on average, should be valued at five times a 78-year-old, who has about 10 years remaining on average.

Is there anything else that should be considered? There are obviously some special cases, like the President, whose life is more valuable than almost anyone else in the US, and one could argue that doctors or leaders of charities or whoever should deserve to be placed above an average citizen as well. But overall, I think this makes things more complicated than they have to be, and while it might work better for small-scale scenarios where you have to decide who a self-driving car should crash into, this sort of weighting isn't necessary for large-scale problems like COVID. Averages should work just fine.

Instead of using a life as the base unit, I will use a year of life as the base unit, just to make calculations easier. Not all years have the same value (which is what has led to measurements such as the QALY),  but in order to make things simpler, we'll assume that all years lost have full value.

Here is a shortened version of the table of people at various ages, and the number of years they have remaining, on average, which I will use as general measures for the rest of this article.

| Age      | Years Remaining |
| ----------- | ----------- |
| 10      | 69.0       |
| 20   | 59.2        |
| 30   | 49.8 |
| 40  | 40.5 |
| 50 | 31.5 |
| 60 | 23.1 |
| 70 | 15.5 |
| 80 | 9.0 |
| 90 | 4.4 |
| 100 | 2.3 |




<h3>Establishing Bounds</h3>

The first thing that I think is important to do, before getting into the calculations, is to establish both that emotional cost is a real cost, and that sometimes that cost is worth it. I'll take two extreme scenarios in order to demonstrate these.

Firstly, imagine a new virus which kills 0.001% of people that it infects, or 1 in every 100,000. Assume it's not particularly deadly to any specific portion of the population. In America, this virus would kill 3,300 people if it were to infect everyone in the country. This virus would not be worth enforcing any restrictions for. The flu kills more than that in most years, and we don't have any restrictions for the flu. It is clear that the emotional cost of being locked down for a virus that 99.999% of people survive would not be worth it.

Secondly, imagine a new virus which kills 10% of everyone that it infects, or 1 in every 10. Assume it's fairly transmissible, so an outbreak wouldn't stop by itself. If this disease was allowed to spread uncontrolled in the US, it would kill 33 million people. This virus would absolutely be worth locking down for to avoid a catastrophic loss. 

So clearly, the number of people that you need to save for the emotional cost to be worth it is somewhere between 3,300 and 33 million. Using our years lost metric, we find our bounds are between 140,000 and 1.4 billion. It's a pretty wide range, but this eliminates two arguments: the "avoid all risk at all costs" argument, and the "open everything at all costs" argument. Next, what we need to do is quantify how much was saved from COVID, and how much was lost.

<h3>Do Lives Have Extra Worth?</h3>

The concept of this article is based on the idea that one person losing their life is roughly equivalent to many people having significant inconveniences in their life for some period of time. For example, if you have a choice between letting one person die and letting 100 people become paralyzed, the first choice seems preferable to me. But there is an argument that you should look from the perspective of saving as many lives as possible, regardless of how this impacts others' quality of life. If you view "being alive" as having infinite value, then it doesn't matter how bad your life gets, you aren't truly losing anything as long as your life isn't actually shortened.

However, societally, we make these tradeoffs all the time. Car crashes kill roughly [38,000 people](https://www.asirt.org/safe-travel/road-safety-facts/#:~:text=Annual%20United%20States%20Road%20Crash,enough%20to%20require%20medical%20attention) per year in the US, but you don't see massive protests to ban normal cars and only allow emergency vehicles on the road, or anything like that. This is because cars are useful - they improve our lives, allow us to travel places faster, and so we have decided that this tradeoff is worth it. Of course, we should still try to improve road safety, just not at the expense of the benefits we get from having cars.

If our society reoriented itself around saving the most number of lives possible, valuing a life, or extra year of life, infinitely, it would look very different than it does today. We would put more money into improving health, cars would probably be banned, as well as alcohol and extreme sports. (Even some regular sports, like football). People would live fairly boring lives, staying home most of the time, and avoiding anything that might possibly lower their chance of survival. If this sounds kind of like what the beginning of the pandemic was like, that's the point I'm trying to make. We can't give a life infinite value and ignore what makes life worth living. 

<h3>The COVID Worst-Case Scenario</h3>

In this scenario, I will look at how many years could be lost in the absolute worst-case scenario for COVID, where everyone in the US gets infected. This represents the maximum possible number of years that we could save by instituting lockdowns, if every single death was prevented.

[This article](https://www.cidrap.umn.edu/news-perspective/2021/02/covid-19-scan-feb-19-2021) suggests that the average COVID death takes away 16 years of life, which seems like a reasonable assumption, as this assumes that the average COVID death in the US is around 70 years old. Knowing that this virus disproportionately kills older people, this makes sense. 

The model at [covidestim](https://covidestim.org/) suggests that roughly one third of the US population has been infected with COVID. There have been roughly 600,000 confirmed deaths from COVID in the US, so if we assume this is roughly accurate, that leaves us with 600,000 * 3 = 1.8 million deaths in the US if COVID infected everyone. Assuming that in this scenario hospitals would be overloaded with patients, we'll add another million deaths, giving 2.8 million. Multiplying this by 16 gives us 44.8 million years lost to COVID, in the worst possible scenario. (As a comparison, everyone in the US combined has 13.9 billion years left to live.) So, if zero people died from COVID because of our lockdown, we would have saved 44.8 million years of life.

With 330 million people in the US, this means that everyone should expect to sacrifice 44.8 / 330 = 0.136 years, or 50 days of their life in exchange for preventing COVID, and this estimate is what I'll use to quantify the loss of life from the virus.

(I didn't include effects of Long COVID or hospitalization because they don't add up to very much compared to 50 days of life lost per person, and are hard to get good numbers on.)

<h3>Quantifying Emotional Cost</h3>

Of course, this question is more difficult than saying that everyone should shorten their lives by 50 days in order to prevent COVID, as that would be impossible. Instead, we have to come up with some form of measurement of how much is lost per day in lockdown. I'd rather be in lockdown for a day than have my life shortened by a day, so a day in lockdown is not exactly one lost day. I can still accomplish things, and have enjoyable moments while following strict COVID guidelines. Also, some guidelines are stricter than others, and have different impacts on the value of a day. For example, being required to wear a mask in the grocery store has a low impact on how valuable a day is, but being quarantined inside your home has a significant impact.

Also, the main idea of this part is to look at it from the perspective of somebody who understands that the various public health measures can have some impact, and isn't overly affected by them. If you think that having to wear a mask ever is an infringement on your freedom as an American, then your day is probably going to be significantly hurt by having to wear one. But this doesn't seem to me like a particularly reasonable belief, so I'm not going to include these people in my estimates. 

So how should "days lost per day of restriction" be calculated? One of my initial thoughts was to measure it in terms of a tradeoff, such as saying "you can either sacrifice X days of your life, or go into lockdown for a year". Then, you'd figure out what X would have to be to make it an even choice. But this doesn't work very well, because of [temporal discounting](https://www.behavioraleconomics.com/resources/mini-encyclopedia-of-be/time-temporal-discounting/). Essentially, we value things in the present more than the future, so the time lost to lockdown would be valued more than time taken off your life, and the question wouldn't work very well. 

A better way of looking at it is to attempt to quantify how much emotional value we get out of various aspects of our lives. Then, I can look at how much that aspect of life was restricted by a certain rule, and see what portion of the value of a day was lost. Throughout this, I will use numbers that I believe to be lower bounds for the amount of emotional loss, in order to err on the side of saving lives. 

By far, the biggest impact that COVID restrictions had on people was on relationships with people outside one's home. Personally, I often felt lonely during the first few months of the pandemic, when I couldn't really see anyone in person. Online socialization provided some of the same benefits, but some things can't be replicated online. These sorts of relationships are where most people get a lot of their happiness, so let's value them at 50% of the value of a day. In other words, if relationships like these are completely lost for a year, it's equivalent to losing half a year of life.

As I just mentioned, online and virtual replacements provided some value, but not all of the value that in-person socialization could provide. Let's say that they provided 50% of the value (which to me seems like an overestimate). Then, one day with in-person socialization completely restricted causes a loss of 0.25 days of life. 

Another major restriction to happiness comes in the form of the loss of in-person events that aren't strictly related to socialization, such as sporting events, marathons, concerts, and other similar events. While these events don't contribute too much to overall value of a day, COVID restrictions cause a near complete loss of them, as virtual equivalents can't really gain back much of the value that they provide. Let's say that these events provide 5% of overall value. (How did I come up with this number? If we spend two weeks per year at these events, and they provide 75% of that day's value while we're there, and 2% of every other day's value, for preparing, etc., that adds up to about 5% of a year.) So, every day where large in-person events are banned causes a loss of 0.05 days of life, on average.

Finally, travel being severely restricted also causes a small loss. Let's say the average American spends two weeks on vacation per year, and during those days, they get 75% of the day's value from the vacation. That's another loss of 0.03 days of life for every day that vacation is restricted.

So overall, the restriction on socialization is the most significant restriction that can be put into place, and a full lockdown, with no in-person socialization, costs 0.25 + 0.05 + 0.03 = 0.33 days of life per person, per day. This feels like a reasonable number to me, though of course it's just an estimate. So if we could really save 44.8 million years of life by going into a full lockdown for 50 / 0.33, or about 150 days, it would be worth it. Similarly, if we banned vacations and large, in-person events for 50*365 / 0.08 = 1.7 years, it would also be worth it. Of course, it's difficult to ban only those things and not have any impact on socialization as well, so really it might be somewhat less than 1.7 years that would be acceptable.

Once we start looking at policies that are not as restrictive as a stay-at-home order, the loss of life per day is less significant. For example, a policy which permits small outdoor gatherings doesn't cause a loss of 0.25 days per day. I would say this policy allows for around 75% of normal socialization levels, which is a loss of 0.12 days per day. In order to save an average of 50 days per person, this could be kept up (along with the travel and large event restrictions) for 250 days, or around eight months. And finally, a policy which allowed for normal social interaction, going to restaurants, etc, but requiring masks indoors would probably allow for an upper bound of 95% of normal socialization levels, a loss of only 0.025 days for each day the policy was in effect. 

However, this math is predicated on the idea that a lockdown could save 44.8 million years of life, which is likely an overestimate. In order to truly prevent nearly all of these years of life from being lost, a very strict lockdown would be needed for a very long time. Additionally, the marginal extra benefit to of having a stay-at-home order (0.33 days lost per day) vs. having a policy that (for example) bans large events, half of vacations, and requires masks indoors (0.05 + 0.025 + 0.015 = 0.09 days lost per day) is probably not enough to counteract the extra 0.24 days lost per day. Measures that have a low impact on social cost, but a high impact on preventing COVID spread, should be prioritized, like requiring masks. Overall, there are certainly restrictions that save more years of life than they take away. But not all restrictions fall under this category, and especially not the harshest ones like [banning outdoor exercise](https://apnews.com/article/california-coronavirus-pandemic-917ba20d0a2f81e1f33de373dc1bd85f). When considering whether to implement a restriction, it should be looked at in terms of not only how it might prevent COVID, but also how it will still allow for people to live meaningful, value-filled lives. 

<h3>What Should We Have Done?</h3>

I can't expect that the US government, or any state government, would independently come to the same conclusions that I've come to here, as much of the numbers I've arrived at are fairly malleable. However, I do think that it's worthwhile to look at what we should have done, if we were to look at it from this perspective.

At the beginning of the pandemic, back in March of 2020, it was a good idea to overreact. We knew very little about the virus, and it seemed possible either that it was far more dangerous than it ended up, or that it could mutate into a more dangerous version. It was a very reasonable decision to shut down everything and take those 0.33 days of life per day from each citizen, as we didn't know what was on the other end of the tradeoff. In the initial stages of the pandemic, some level of panic was a rational thing to have.

In the following months, once we learned more about the disease itself, I believe that a stay-at-home order was too high of a cost at most points during the pandemic. The various very strict regulations on socialization that certain states put into place after the first wave of the pandemic should have been avoided. That's not to say that no restrictions should have been in place. A smart policy would have been to as a baseline, ban large events and require masks, but not put strict regulations on socialization (such as restricting events to [six people or less](https://www.opb.org/article/2020/12/03/oregons-new-covid-19-rules-hit-today-heres-what-to-know/)). This would also have had the likely side effect of increasing mask use, as it's far easier to make sure people are wearing masks when they are meeting in a public area as opposed to a private gathering. 

I haven't discussed school much, but I believe that as it is a major source of the socialization that school-age children get, as well as the fact that children don't often get seriously sick from COVID (although they can spread it), schools should have been a much more important priority to reopen. They should open with masks required and testing measures, but in some places they weren't open at all until the spring, which seems far too late. Many children were deprived of a lot of socialization, which could have a significant, difficult-to-measure impact on their development.  

Once the vaccines were shown to be safe and effective, they should have been approved and administered as quickly as possible. This isn't really related to restrictions, but the US did do a solid job on this front. There were delays and issues along the way, but overall the US's vaccine rollout was pretty fast (to the people who wanted it). The prioritization of various groups was very confusingly done in many different ways by many different states, but mostly seemed to be reasonable, prioritizing doctors and healthcare workers, then older people, then other groups including teachers or essential workers, and finally opening it up to everyone.

Then, at a certain point when the vaccine had been offered to everyone over 65, things should have started to open up more significantly, and once it had been offered to everyone, some mask mandates should also be repealed. Some states did this [too early](https://gov.texas.gov/news/post/governor-abbott-lifts-mask-mandate-opens-texas-100-percent), and mostly as a "Democrats suck" measure instead of a "we trust the science" measure. Given that April 19th was the date where vaccines were available to everyone who wanted one in the US, setting a date such as May 15th to open up everything seems reasonable. The last thing to open up should be large indoor events, which is basically what happened. 

Of course, during all of this time, other factors must also be considered, such as the prevalence of COVID in an area at a certain time. It makes sense to tighten restrictions when there are more cases, perhaps lower the capacity of indoor dining, encourage outdoor socialization, or attempt to reduce travel for holidays. But it doesn't make sense to immediately go to the step of trying to eliminate most socialization (via closing all indoor dining, banning socialization between more than two households, etc.), as that has a high cost that isn't necessarily paid off by the benefits. 

<h3>Going Forward</h3>

I believe that in the US, nearly every pandemic-related restriction should be dropped, aside from requiring masks on airplanes, in hospitals, and some other indoor public places. At this point, everyone who wants a vaccine has gotten one (aside from young children, who are not particularly impacted by the virus). So, the potential to save years of life is limited to the 2% (probably an overestimate) of people who can't get vaccinated at all, and the roughly 10% (accounting for the Delta variant) of the population who are vaccinated, but will have a breakthrough case if they are exposed to the virus. In total, that's 12% of people at maximum.

If we assume that none of these 12% have had COVID, and that they will all get it if we drop all restrictions, that equates to 44.8 (our number with no vaccines) * 0.12 = 5.38 million years saved. (This doesn't count the people who refuse to get the vaccine, but if you choose not to get the vaccine, I don't believe it should be the burden of other Americans to protect you.) Across all 330 million Americans, that's an average of 5.9 days per person that we should be willing to trade. I can't think of any restriction aside from requiring masks in some indoor public places that would save more years of life than it costs, if the maximum possible to save is only 5.9 days per person.

Looking at real-world data as well, there are currently only a few vaccinated people that have died in the US ([1,263](https://www.cnn.com/2021/07/31/health/fully-vaccinated-people-breakthrough-hospitalization-death/index.html) according to the CDC's latest report).  This is under the threshold of an acceptable number of deaths to mostly fully reopen, and while we should expect this number to increase with the current Delta wave, unless it increases by a surprising amount, there's no reason we shouldn't open up. 

Essentially everywhere in the US has followed this, with my state of Oregon being one of the last to officially lift restrictions. So this isn't really aimed at convincing state governments that they should lift restrictions, but more so illustrating that we're at a stage where the positive impacts of socialization and in-person events outweigh the negative impact of the virus. COVID-19 and its variants will be with us for a while, but thanks to the vaccines, we can get back to a relatively normal life. 



