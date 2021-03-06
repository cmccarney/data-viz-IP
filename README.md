# data-viz-IP
Individual Project on Gun Violence for MSIS 2629
see vox article: https://www.vox.com/policy-and-politics/2017/10/2/16399418/us-gun-violence-statistics-maps-charts

Gun violence in the United States is unique among developed nations, and the primary reason seems to be that the US has a lot of guns and very loose or non-existent regulations relating to who may access firearms.

However, since the Second Amendment to the US Constitution has been interpreted as an individual right to own firearms, as opposed to a collective right of states to man their own National Guards, there is a lot of debating about infringement of this right.

This data product compiled by Vox seeks to demonstrate not only that guns are uniquely responsible for the lethality of certain crimes, suicides and even daily life, but also to show that effective policies can make a difference in these rates. Furthermore, despite the great polarization of American politics, when using an approach based on individual policies or regulations, there is reason to think advances can be made in the legislative arena.

Now since the Vox data product encompasses 17 different charts and various data sources, there is no surprise that not all charts are equally effective in conveying this overall message. In fact at various times, Vox seems to muddy its own arguments for the sake of pulling in one more chart or visualization. The mass shooting calendar for example is just to show that mass shootings happen frequently and so not talking about gun control in the wake of a mass shooting is just another way of saying never talk about it. But this entire argument is undercut by the fact that, as shown in a later chart, mass shootings have little impact on opinions about gun control. If this is so, then there is no reason to highlight the timing of mass shootings because they do not move legislation.

The Vox article also gives one reason to question the honesty of the information being presented. The article regularly switches between charts that use homicides and ones that use ‘gun deaths’. While it does make distinctions with suicides and shows that suicides account for a large portion of gun deaths, this lack of a clear path prevents really insightful and cogent arguments. 

Overall, far more compelling might be for Vox to demonstrate, as FiveThirtyEight does here, https://fivethirtyeight.com/features/mass-shootings-are-a-bad-way-to-understand-gun-violence/, that gun deaths are varied in terms of primary victims, primary perpetrators, and primary intents. The last graph shows support for specific policies, and makes the argument that a piecewise approach to legislation will be more effective. The video Vox includes at the start of this article is actually a lot better than the article itself, because while showing that the prevalence of guns are the issue, it also makes clear that there is no "one" problem, but many problems requiring tailored solutions.

Revising some of the existing charts
 
Chart 8 is not clear in its communication. It's a pseudo-heatmap of US states with additional gradient shading for which states have certainly safety laws. There does seem to be a bit of a trend, but the fact that there are states that buck that point and the fact that the differences aren't that dramatic really undercuts any point that is trying to be made.  Additionally, it's unclear how significant these differences really are. A total redesign of this chart will be needed.
 
Chart 11 suggests more guns means more suicides. It's a simple chart but it's simplicity invites issues of honesty in the representation of the information. The fact that this is followed up by Chart 12 which is data on suicide attempts/fatalities for the state of Indiana for a 7 year period in the 1990s really jumps out as being suspicious for its ultra-specificity. More data will need to be uncovered to help address this gap in the information. Considering that suicides are such a large proportion of gun deaths, it seems like this is an area that would really have an outsized impact on the effectiveness of the entire data product.

Intentionally Distorting the Data

In any political debate this is really a time-honored tactic. Here are some ideas on how to implement this with the Vox product. 

Chart 13, the Australia Suicide Chart, looks like it can be easily manipulated to show the change in suicide rates is not nearly as "dramatic" as the article maintains. Omitting data points and/or changing the scale of the graph axis should make it possible to completely eliminate the drop from the buyback program and argue that the decrease in suicide rates was merely a continuation of a trend that began years earlier. 

Chart 7 is meant to show that US is not unique in the amount of crime that it has and so the much higher gun deaths is related to something else. However if I cherry pick the countries used in the comparison and then also make changes to the axis labels, I can make it seem as though the US rate is far greater. Similar techniques can also be applied to cop homicides chart 14, which already looks a bit questionable.

Scaling and extraction techniques could also be used to change the suggestion from chart 15 that support for second amendment rights has been increasing overtime. Chart 2 is an icon chart so changing the scale of the figures could imply that the US doesn’t really have nearly the number of guns that is being suggested.
