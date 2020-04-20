{% assign sortedposts = site.posts | sort: 'date' %}
{% assign newestpost = sortedposts | last  %}

## Coronavirus Daily Update

This site is on pause until further notice. I have become convinced that
the disease is not a big deal if you are not retiree-aged, and in light of
this, the lockdown measures are harder to accept. Meanwhile, I am
becoming increasingly distraught at the zeal with which everyone I know
are eagerly begging for stricter and ever more arbitrary measures.
Finally, the mixed messaging, the cutesy corporate-saccharine slogans,
the weird obsession with arbitrary constraints like "6 feet distance",
is feelingly more dystopian to me every day.

I need to take a break on this. Until further notice, I will not be
updating this site. In the mean time, these are the only updates you
need:

* This disease will probably kill your elderly relatives
* This disease will kill a very, very small fraction of your non-elderly
  relatives
* There are no viable treatments to this disease. A vaccine will not be
  available for years, and if one is available earlier I strongly
  recommend not taking it. One way or another, everyone, or almost
  everyone, are getting infected
* Most of the public health measures being taken shouldn't be. Most of
  the public health measures that should be taken aren't. This will not
  change
* Most of the people with authority care more about lockdown and related
  rights infringements for their own sake than they do about any public
  health goals

### Read First

[About This Site](about/about.md)

[About The Pandemic](about/ncov.md)

[RSS Feed](/feed.xml)

----

### Good Sources

I have no affiliation with any of these links. They are my personal
recommendations

[Dr John Campbell, NHS medical
instructor](https://www.youtube.com/user/Campbellteaching)

[Practical tips to protect yourself in an
epidemic](http://beatthecoronavirus.com/)

[In-Depth Prepping Guide](https://theprepared.com/wuhan-coronavirus/)

[Report of the WHO-China Joint Mission on Coronavirus Disease 2019](https://www.who.int/docs/default-source/coronaviruse/who-china-joint-mission-on-covid-19-final-report.pdf). This should be considered the most official source of truth about this crisis at this time.

[Johns Hopkins Crisis
Dashboard](https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6)

[Worldometer Coronavirus Page](https://www.worldometers.info/coronavirus/). At-a-glance numbers and summaries

[BNO Newsroom
Twitter](https://twitter.com/BNODesk?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor)
possibly the single best journalistic source to follow

[Broadcastify](https://www.broadcastify.com/). Listen in to police, fire, and EMS radios. Might be useful for primary-source information

[Singapore Government Coronavirus
Dashboard](https://co.vid19.sg/dashboard). Singapore has had seemingly
the best response to this crisis so far, and has kept the disease
numbers low as a result. I consider this the gold standard in terms of
reliability. I trust this data even more than I trust the WHO data, even
though the WHO data is more "official"

----

### Previous Updates

{% for post in sortedposts %}{% unless forloop.first %} / {% endunless %}[{{ post.date | date:"%Y.%m.%d" }}]({{ post.url }}){% endfor %}


Updated 2020.04.20 16:58 CDT
