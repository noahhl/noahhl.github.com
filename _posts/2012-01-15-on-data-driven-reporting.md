---
layout: post
title: On "data driven" journalism
---

# On "data driven" journalism

In today's <a href="http://nytimes.com">New York Times</a>, there's a front-section article entitled <a href='http://www.nytimes.com/2012/01/15/business/the-1-percent-paint-a-more-nuanced-portrait-of-the-rich.html?_r=1&hp'>One Percent, Many Variations</a> that takes a look at some statistics relating to the vaunted 1% of households by income in the United States, and features some interviews with 1-percenters.

I'm a regular reader of the Times, and a major fan of the relatively long-form journalism that it supports with articles like this. I am also a fan of <a href="http://en.wikipedia.org/wiki/Data_driven_journalism">"data driven" journalism</a>, which attempts to use statistics to tell a news story. Finally, I used to do this sort of demographic analysis for a living, so it's nice to see something similar in print.

There are however, a few criticisms of the article I'd like to raise.

### "Just add a 'Source' line with something in it"?

Each of the charts and maps that are included in the piece (some of which I found to be excellently done) is sourced as "New York Times analysis of University of Minnesota Population Center data" (some of the web-only charts seem also to be sourced as 'IPUMS'). A curious reader might wonder how the data was gathered, whether there's a political slant to it (it's far too easy to <a href="http://en.wikipedia.org/wiki/Push_poll">skew statistics with how you ask a question</a>), etc.

Let's take a gander to the website of the <a href="http://www.pop.umn.edu/">Minnesota Population Center</a>. Once there, you'll see a nice link to "get data" from the <a href="http://ipums.org">Integrated Public Use Microdata Series (IPUMS)</a>.

IPUMS is an infrastructure service that the MPC puts together that provides an easier to use interface to US Census Bureau and other primary data sources -- they don't primarily gather any data themselves. The data that the Times article draws from could be from multiple different survey instruments, and a curious reader is now stuck. Was this drawn from the (nominally 100% sample) <a href="http://2010.census.gov/2010census">decennial census</a>? From the <a href="http://www.census.gov/acs/www/">American Community Survey</a>, which is a 1-2% annual sample of households? Or from the <a href="http://www.census.gov/cps/">Current Population Survey</a>, which is an even smaller monthly survey from which things like unemployment rate are derived? Or is it in fact from some research that the MPC actually did do, but on which I can't find an y information about methodology?

This is not a critique of the MPC or IPUMS - IPUMS is in fact a fanstastic tool that I've used dozens and dozens of times. Rather, this is shoddy sourcing. I don't know what editorial standards for sourcing are, but not providing the specific instrument and year doesn't pass muster if you're experienced with these data source.

I will give some credit to the Times here -- later in the article they cite a Gallup poll which they at least link to <a href="http://www.gallup.com/poll/151310/U.S.-Republican-Not-Conservative.aspx">Gallup's press release</a>, which does include sampling information (including that their "1%" sample is a grand total of 400 people).

### "Sample Size - one is all I need"?

In an online feature that accompanied the article, there's <a href="http://www.nytimes.com/packages/html/newsgraphics/2012/0115-one-percent-occupations/index.html?ref=business">a chart</a> that shows by industry and occupation, the number of households that fall in the top 1% and have a member with that industry/occupation, and the portion of people that have that industry/occupation combination who fall into a household that is in the 1%.

There are two problems that I have with this chart:

1. If you look around, you'll find some cells of the chart that represent astonishingly small numbers of people -- for example, water/waitress + "other industries" has '954 people with this job live in households in the top 1 percent'. We're a little hampered by not knowing the actual data source, but assuming it's the American Community Survey (which, based on the data they used throughout the piece, I believe it to be), these 954 people likely represent a handful of responses, or perhaps even a single response to the survey (since the survey is intended to be a representative sampling of the population, it's heavily weighted). This doesn't pass the 'sniff' test at the precision they present.

2. This chart glosses over some definitional differences that are actually quite important:

    a. "Income" is typically considered at a household level -- you, your spouse, and any other wage earners who live in your household -- and includes both wages and non-wage (investment, etc.) income alike.

    b. "Employment" is typically considered at an individual level -- you -- and the income associated with it is just wage income.

    Here, the Times has conflated the two by drawing a chart in which one metric is "percent of households in 1% that have at least one member who works in a given industry" and another which is "percent of the people in an industry who live in a household that falls in the 1%". 

    Furthermore, they draw this is a manner that implies that they are showing the entire population of the United States, split up into mutually exclusive and collectively exhaustive groups. Nothing could be further from the case -- there is overlap between the households represented by these groups (because a household can have both a 'manager' and a 'lawyer' in it), and there are households that are wholly excluded (because they don't work in any identifiable industry, perhaps). 

    The legend doesn't help this situation at all either -- "Rectangles are sized according to the number of people in the top 1 percent" implies a per-person measurement, when it's in fact almost certainly a per-household measurement.

### "If you can't find data to support it, find a quote"?

Towards the end of the article, the Times quotes <a href="http://en.wikipedia.org/wiki/Dave_Mejias">David Mejias</a>, a politician and attorney:

> Still, David Mejias, a divorce and personal injury lawyer who once served as a Democratic legislator for Nassau County, said that the system everywhere was skewed in favor of the self-employed and business owners who could deduct part of the cost of their cars, trips, dinners and even collectibles like art.
>“Not only do we make more money, but if you do a lifestyle analysis, we make a lot more money,” he said. “Before we even get paid, most of our life has been paid for already.”

This is a nice angle, but there's no data to support it. I know that this isn't that unusual for journalism -- we're not talking about peer-reviewed scientific publications -- but in a piece that is otherwise rich with facts and figures, there's nothing to support this. There's no measure of the portion of living expenses that are counted as business expenses, or of greater effective income as a result of being a small business owner or self-employed. There's also no mention of the countervailing impact of alternate taxation, etc. that small business owners and the self-employed face.

<hr/>

I could go on, and on, and on, but I'll stop  with these three main points, which I hope I've illustrated above:
1. Source matters.
2. Sample size matters.
3. A politician's quote is not fact.

Don't get me wrong -- on balance I enjoyed the piece, and I vastly prefer fact-based articles with some flaws to fact-less articles. However, if the future of journalism is at least in part about bringing greater rigor to reporting (and I hope that it is), there's still a long ways to go.

<hr/>