---
title: 'Literature Exploration in SciX'
teaching: 20
exercises: 20
---

::: questions

- What papers are useful to researchers working on (example topic)?
- What are the top collaborations in (example topic)?
- How could I narrow (example topic) appropriately?

:::


::: objectives

- Expand a search using SciX second-order operators, including useful and review
- Explore connections among authors and papers using SciX visualizations

:::

## Literature Exploration in SciX

In this lesson, we will be focusing on different ways to explore your search results in SciX.

### Setting Up Your Environment

When you to to [SciX](https://scixplorer.org/), ensure you can see the homepage.  

![](fig/scix-homepage.png){alt="Screenshot of the SciX homepage"}

::: instructor 
Ask learners: "Can everyone see the SciX homepage on their browser?"  
:::

### Research Trends

First we will focus on second-order operators, which are search operations that are performed on the results of a previous query. The second order operators available in SciX are: **similar**, **useful**, **reviews**, and **trending**,. Each of these second order operators benefit from taking different things into consideration for the initial query, so we will discuss individually the three we highlight in this lesson.

::: instructor  
You might mention the kinds of topical searches you commonly perform in SciX (e.g., finding articles for your domain or checking citation metrics). The guided examples will be more meaningful if you modify them for your discpline or facility.
:::

To get started, let's run an example search query on SciX.  You can search for any topic you are interested in, but for my demonstration, I am going to look for papers about volcanoes.


Start by entering your terms into the main search bar and executing the search.

![](fig/scix-volcanoes-search.png){alt="Screenshot of SciX search results on Volcanoes."}

Next, click on the Explore button menu to see all of the options, which are categorized under two headings: Visualizations and Operations. The options under "operations" are the second order operators.

![](fig/scix-explore-menu.png){alt="Screenshot of the Explore menu from SciX search results."}

#### Similar

First, let's look at the ```Similar()``` operator.

Results from this second-operator query exclude the results from the original query, so it is best to focus on creating a narrow set of results, or even a single relevant paper, to build off in the "similar" search, so look through the results and select the one to three papers most relevant for your topic.  I'll select just the first article using the checkbox and click on "Similar" under the Explore menu.

It may take a little while for the results from the second order operator to load.  In the background, Science Explorer is combining the abstracts from articles in the original selection and then ranking all abstracts in SciX based on their textual similarity to the combined abstracts.  The articles returned are the most similar to those from the original selection as determined by text analysis.

![](fig/scix-similar.png){alt="Screenshot results that are similar to one of the results from the original Volcanoes search results."}

In addition to lists of papers, ```Similar()```accepts any text as input.  The format is

```
similar:("any text for comparison goes here",input)
```

For instance, I could take text from [U.S. Geological Survey (USGS)](https://www.usgs.gov/) [Volcano Notification Service](https://www.usgs.gov/volcanoes/yellowstone/volcano-updates) report 

![](fig/usgs-volcano-report.png){alt="Screenshot of USGS Yellowstone Volcano Observatory Monthly Report dated 2026 September 01"} 

and feed it into ```Similar()```.

```
similar("Yellowstone Caldera activity remains at background levels, with 61 located earthquakes in August (largest = M2.0). Deformation measurements indicate no significant uplift of the north caldera rim since January 2026 and only minor uplift of the caldera since the beginning of the year.",input)
```

![](fig/scix-similar-example-yellowstone-init.png){alt="Screenshot of SciX main search bar with "Similar()". User has entered text about Yellowstone directly into function."}

to get over 68,000 results.

![](fig/scix-similar-example-yellowstone-results.png){alt="Screenshot of SciX results page from search of "Similar()" with user-input text about Yellowstone monitoring."}

[Michael Kurtz et al. 2020]() and the [SciX ```Similar()``` help] (https://scixplorer.org/scixhelp/search-scix/second-order)  provide examples of sophisticated queries using ```Similar()```

#### Useful

The second-order operator ```Useful()``` examines the references included in papers identified by the original query. It combines them into a list sorted by how often a given paper is referenced in the original set.  The documents returned are the ones cited the most often, by the authors of the chosen papers on the topic, which can include foundational papers, datasets, and software. This query can also expose papers in different, but related fields, such as papers that describe software that other researchers found useful when exploring the topic.

::: challenge
Submit a query to determine what papers are useful to volcanologists.  

::: solution
![](fig/scix-useful.png){alt="Screenshot of SciX results about volcanoes that are useful."}
Using an unfielded search for volcanoes as input, ```Useful()``` returned over 4,00 results when this example was run as you can see in the upper left; because SciX adds new material on daily and weekly cycles you may see a different count.

The top three papers shown contain significant data sets and fundamental software functions.

:::
::: 
#### Reviews

The last second-order operator we will cover today is ```Reviews()```. This operator collects the list of papers that cite the papers in the original query and sorts them by how frequently each paper appears. It does not necessarily return articles from review journals, such as _Annual Review of Earth and Planetary Sciences, Annual Review of Astronomy and Astrophysics,_ or _Annual Review of Information Science and Technology_. You can think of the results from a ```Reviews()``` search as a higher-level view of your topic or taking a step back from the details. These results will be the most relevant papers on your topic when viewed from this broader perspective within its field. 

::: challenge
Submit a query to take a higher-level look at volcanoes, perhaps place it within physical geology more broadly using ``Reviews()```. 

:::solution 
![](fig/scix-reviews.png){alt="Screenshot of SciX results that are reviews of literature about volcanoes."}
Using an unfielded search for volcanoes as input, ```Reviews()``` returned over 127,00 results when this example was run as you can see in the upper left; because SciX adds new material on daily and weekly cycles you may see a different count.

The top three papers shown appear be about tectonic systems.

::::

If you were looking for a more traditional review journal covering a field with which you were less familiar, you could consult the SciX Journals database. It is available at [https://scixplorer.org/journalsdb](). You can type a word or two into the search bar to identify journals with titles containing those words.

![](fig/scix-journalsdb-review.png){alt="Screenshot of SciX Journals Database search results for 'Review' "}

![](fig/scix-journalsdb-ESRv.png){alt="Detail of Screenshot of SciX Journals Database search results for 'Review' near _Earth Science Reviews_'"}

If I try typing "Review", I find a lot of choices. However, scrolling through them, I do not find a volcanology specific review journal. My best option is probably _Earth Science Reviews_ (ESRv). If I click on the abbreviation, I will get all of the papers published in that journal.

![](fig/scix-bibstem-ESRv.png){alt="Screenshot of SciX results for all of the papers published by _Earth Science Reviews_ (bibstem = ESRv)"}

Alternatively, if I click on the full name of the journal, I will get more technical information about the SciX holdings for this journal.

![](fig/scix-journalsdb-ESRv-detail.png){alt="Screenshot of SciX Journals Database listing for _Earth Science Reviews_"}


#### Summary

To review, there are four types of second order operators available in the SciX platform.  These second order operators can provide deeper insights and more information about the topic you are researching.   SciX provides the graphic below to help describe the similarities and differences of these operations.

![](fig/scix-second-operators.png){alt="Graphic summarizing the four second order operators of SciX."}

For more information, we recommend you visit the SciX help page on second order queries.
https://ui.adsabs.harvard.edu/help/search/second-order
You may also find this [Second Order Operators in SciX](https://ads.harvard.edu/handouts/SciX_2ndorder_operators.pdf) handout helpful.


::: discussion
### Reflection and Discussion

Break into small groups and spend 2-3 minutes individually with second order operators looking for research trends in a topic of your choice.  Then discuss what you did and what you learned with your group.

Which operator are you most likely to use:  similar, trending, useful, reviews?

:::


### Connections & Collaborations
Now, let's turn to examining SciX visualizations, and we are going to focus on the paper network and the author network because these two visualizations offer new ways to explore search results.

![](fig/scix-explore-menu2.png){alt="Screenshot of SciX search results on Volcanoes."}

#### Paper Network

This visualization creates groups of papers by looking at the references from each paper and grouping them based on how many are shared.  Since the papers in these groups cite a similar set of other papers, we can expect the papers in the group to be about the same topics.

![](fig/scix-paper-network.png){alt="Screenshot of SciX paper network visualization, showing the main topic groups for papers in the results set."}

Each group is named by extracting shared, unique words from the titles of the set of articles in the group.  This can help provide a general overview of the main topics of your original search results.  Clicking on any specific group will display a list of the most cited papers from that group.

Reviewing a paper network can help you drill down into a topic or help you expand your literature search by identifying papers you may have otherwise missed.

#### Author Network

This visualization is created by looking at authors that frequently appear together and creating groups based on the frequencies of those collaborations.  Each of these groups contain authors that often work with each other, though not every author in each group will have worked with every other author in their group.  You may find it helpful when looking for new opportunities or when trying to eliminate possible conflicts of interest.

![](fig/scix-author-network.png){alt="Screenshot of SciX author network visualization, showing the main groups of authors for papers in the results set."}

Clicking into the section group, the inside edge of the donut, will bring up the list of papers in that group.  Clicking on a specific name, or their specific section of the donut, will instead show all papers by that particular author.

### Summary

By default, both visualizations only use data from the first 400 papers of the search result, but can be expanded up to the first 1000 papers.  Also, both of these visualization graphs have an option to download a text file in comma-separated-value format (csv) of the data that underly the graphic.  The cvs file will provide identifiers for each paper and indicate which other papers are in its same group, along with some other metadata such as citation counts and downloads.

For more details about these two graphs and information about the other graphics provided by SciX, we recommend you review their help page on Visualizations.
https://scixplorer.org/help/actions/visualize
You may also find this [Exploring SciX Visualizations](https://ads.harvard.edu/handouts/SciX_visualizations_handout.pdf) handout helpful.


::: discussion
### Reflection and Discussion

Break into small groups and spend 2-3 minutes individually looking at these visualizations for a topic of your choice.  Then discuss what you did and what you learned with your group.

How could you use either the paper network or author network in your own work?

:::
