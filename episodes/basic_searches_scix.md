---
title: 'Basic Searches in SciX'
teaching: 15
exercises: 10
editor_options: 
  markdown: 
    wrap: 72
---

::: questions
- How do you find an article by a specific author?
- How do you find articles about a specific topic?
- What other types of resources can you discover besides articles?
:::

::: objectives
- Execute a basic author search
- Execute a basic keyword search
- Refine a search using facets
- Identify useful metadata and resources through the abstract view
- Follow links from the abstract page to access resources such as the
  open access version of the article, related software, and associated
  datasets
:::

## Basic Searches in SciX

Once you've accessed the SciX main page, you're ready to explore its search
capabilities. In this episode, we'll cover both author and keyword
searches, then show you how to refine your results.

::: instructor
You might mention the kinds of searches you commonly perform in SciX (e.g., finding articles for your domain or checking citation metrics).
The guided examples will be more meaningful if you modify them for your discpline or facility.
- Who is an author your learners would know?
- What is a topic in which your learners would be interested?
:::

## Setting Up Your Environment

When you navigate to SciX, ensure you can see the homepage.  The SciX address is [scixplorer.org](https://scixplorer.org/)

![Screenshot of the SciX homepage](fig/scix-homepage.png){alt='Screenshot of the SciX homepage showing the main search bar and navigation options'}

::: instructor
Ask learners: "Can everyone see the SciX homepage on their browser?"
:::

## Selecting Your Discipline

On your first visit, select your preferred discipline from the dropdown
menu in the upper left.

**Note:** This step customizes your search tools but does not limit your
overall search.

![Dropdown menu showing discipline selection options](fig/scix-select-discipline.png){alt='Dropdown menu for selecting a discipline in SciX, such as Planetary Science'}

## Quick Help & Navigation

SciX offers a help carousel on the main search page. Click the
left/right arrows to view introductory resources, including a quick
start guide and search examples.

![Quick Help](fig/quick-help.png){alt='Help carousel on the SciX homepage showing navigation arrows and learning resources'}

For more detailed assistance, click the "Help" button in the upper
right.

![SciX help carousel with a Help button in the top right](fig/extensive-help.png){alt='SciX homepage with the Help button highlighted in the top-right corner'}

## Starting a Search

As an open science search engine, SciX is primarily concerned with
ensuring that literature, data, and software are findable or
discoverable. So, let’s find some relevant papers. Author searches are
among the most common performed in SciX.

![Main search bar highlighted on the SciX homepage](fig/starting-search.png){alt='Highlighted search bar on the SciX homepage for entering search terms'}

::: challenge
If you select author from either the quick fields or the dropdown menu,
SciX will add the field to the search bar.

![Starting an author search](fig/starting-author-search.png){alt='Author field selected in the SciX search bar'}

## Author Search

1. In the search field, select **author** from the quick fields or
   dropdown.
2. Type `"shoemaker"` (for example, for Gene Shoemaker) and click the
   blue magnifying glass.
:::

::: instructor
Learners can just type names and phrases into the search bar. However, they will have greater control over structured searches using fields like shown here than unfielded searches.
:::

::: solution
![Searching on author name Shoemaker](fig/add-author-name-search.png){alt='Search results initiated for author name "Shoemaker"'}
:::

:::: challenge
## Search by Author

Try searching for Gene Shoemaker on your own. How many results do you
get? Discuss with your neighbor.

::: solution
![Results for Gene Shoemaker](fig/results-view-shoemaker.png){alt='Search results view showing 2,560 items for "Shoemaker"'}

author:”shoemaker” returned 2,560 results when this example was run as you can see in the upper
left; because SciX adds new material on daily and weekly cycles you may see a different count. 

The results are sorted by relevance and are in descending order.
You can change the sorting criterion by using the dropdown menu to
select: date, author count, citation count, entry date, first author,
normalized citation count, or read count. Click the button next to the
dropdown menu to switch between descending and ascending order.
:::
::::

For each article returned, you see the title, author list, date of
publication, journal, and citation count. Looking at the three icons on
the right, you can tell whether SciX links to the full-text, references
or citations, and data.

![Article results view in SciX](fig/articles-result-view.png){alt='List of search results showing article titles, author names, dates, and icons for full-text, references, and datasets'}

As an open science digital library, SciX is also concerned with ensuring
you can access the papers, data, and software that you want.

![Article results view in SciX with callouts showing resources available if paper, references or citations, or data icons are clicked](fig/article-results-view2.png){alt='Results view with callouts showing what is available when paper, references or citations, or data icons are clicked'}

Looking at the list of results as a whole, I see some interesting
articles with an author named “Shoemaker” but perhaps not immediately,
Gene Shoemaker, planetary scientist. The author box on the left allows
me to narrow my results. It lists variants of the name “Shoemaker” at
the top followed by the names of co-authors.

The most common variants and co-authors are listed first.

Clicking a name variant opens additional options:

- **Limit to** preferred name(s), showing only papers by that variant
- **Exclude** unlikely variants to remove unrelated results

This helps narrow your results to the specific individual you're interested in.

![The Author facet in SciX shows variants of "Shoemaker" along with frequent co-authors, allowing the user to refine results to the correct individual.](fig/narrowing-author-list.png){alt='Author facet sidebar showing Shoemaker variants and frequent collaborators'}

### Refine by Institutional Affiliation

You can further narrow your search results using the **Institutions** facet.

For example, if your target author worked at Lowell Observatory, you can:

- **Limit** to papers with authors from that institution
- **Exclude** results from other affiliations

This is especially useful when multiple authors share similar names but work at different institutions.

![Institutions facet in SciX](fig/refine-by-institution.png){alt='SciX sidebar facet showing a list of institutions such as Lowell Observatory with checkboxes to include or exclude them from results'}

::: instructor
SciX also has an affiliation (aff:) field search that searches the exact affiliation text provided by the author or publisher.  The Institution facet uses a SciX standardized abbreviation and is similar to the institution (inst) field search. Some institutions listed in the facet can be opened to identify authors with individual departments. Learners asking detailed questions about this feature should be encouraged to read the SciX [blog post about it](https://scixplorer.org/scixblog/affils-update). 
:::

### Refine by Date

You can also adjust the **date range** of your results using the slider in the left sidebar.

- Drag the endpoints of the slider to limit results by year
- Click the expand icon (four arrows) to see a larger or more precise timeline

Use this if you're researching a specific publication window or want to filter out older or newer results.

![Date range slider controls in SciX](fig/date-slider-expanded.png){alt='Date range slider with adjustable endpoints and expand icon in SciX facet panel'}

::: challenge
### Keyword Search

Return to the SciX main search page. Use the "all search terms" dropdown menu to start a keyword search for 'crater.' 
![SciX main search page showing hover over search term help](fig/scix-allsearchterms.png){alt='SciX main search terms with "all search terms" menu extended; abs search is highlighted and explained'}
:::

::: solution
![Results for Keyword crater](fig/scix-keyword-crater.png){alt='SciX results view showing 8,901 items for "Crater"'}

keyword:”crater” returned 8,901 results when this example was run as you can see in the upper
left; because SciX adds new material on daily and weekly cycles you may see a different count. 
::::

### Understanding SciX Synonym Expansion

SciX automatically expands keyword searches with discipline-specific synonyms,
related terms, and even common misspellings or alternate forms. For example,
a search for `crater` might automatically include terms like:

- craters, cratering, cratered
- craterlets, craterlike, crateris
- craterform, subcrater, craterization
- krater, cratori, noncrater, etc.

This expansion improves discoverability across disciplines that might use
different terminology for the same concept.

If you only want the **exact term** you typed (no expansion), add an equals
sign: `=crater`.

This exact-match feature is helpful when you're targeting highly specific
terms or avoiding irrelevant results.

::: challenge
## Keyword Search

Return to the SciX main search page. Execute an exact keyword search for 'crater'. 

::: solution

![Exact keyword search for crater (synonym expansion disabled](fig/scix-keyword-crater-exact.png){alt='SciX results view of search for exact match keyword crater'}

=keyword:”crater” returned 2,329 results when this example was run as you can see in the upper
left; because SciX adds new material on daily and weekly cycles you may see a different count. 

With exnonym expansaion disabled, fewer results are returned. However, those precise results may be just what you need.
:::
:::

::: challenge
## Keyword Search

Experiment with an author or keyword search, both with and without the equal sign.
What differences do you observe? Discuss your experiences with a partner
:::

::: instructor
As time allows, encourage learners to share their expectations and experiences with expanded and exact searches.
:::

### Narrowing Results Using Keyword Facet

After running a keyword search, you can refine your results using the
**Keywords** facet in the sidebar. Authors or publisheres provided these keywords, 
which are listed in order of frequency with in your results.

You can:

- Choose to **limit to preferred keywords** or **exclude undesired ones**
- Click the upward arrow in the lower right corner of the facet to browse the full list of keywords

![SciX Keywords facet for search refinement](fig/scix-keyword-facet){alt='SciX results view with Keywords facet open and arrow to access enhanced search panel highlighted'}

- Sort keywords by frequency or alphabetically
- Search for a specific keyword or partial match
- Download keywords for use outside of SciX

![SciX Keywords facet search panel showing search for terms begining with 'sh'](fig/scix-keyword-facet-search.png){alt='SciX Keywords facet search panel with results of search for keywords begining with 'sh' sorted by frequency'}

This is especially useful when you're trying to focus on a specific subtopic
or filter out irrelevant results.

::: instructor
Keyword searches are complicated because publishers use different keyword systems, which can also change over time. The keyword_schema field identifies the system where known. 
Authors who want their papers to be discovered (and cited) might want to give some additional attention to the keywords they suggest for their papers.
:::

### Filtering by Refereed Status

SciX allows you to filter your search results based on whether a paper is
**refereed** (peer-reviewed) or **non-refereed**.

You can find this option in the **Refereed** facet in the sidebar. It's useful
if you're looking only for peer-reviewed journal articles or want to include
other materials like conference proceedings or dissertations.

**Note:** SciX considers dissertations to be refereed. Most conference
abstracts and proceedings are categorized as non-refereed.

- Select "Refereed" to limit results to peer-reviewed works
- Select "Not Refereed" to explore grey literature, preprints, or early drafts

![Refereed filter option in SciX sidebar](fig/scix-refereed-filter.png){alt='Facet panel in SciX showing checkbox filters for refereed and non-refereed papers'}

### Filtering by Publication Type

You can also filter your results by **Publication Type**, helping you
focus on specific formats such as:

- Journal articles
- Book chapters
- Dissertations
- Conference papers
- Technical reports

Use the **Publication Type** facet in the sidebar to:

- Limit results to your preferred document types
- Exclude formats that aren't relevant to your research

This is particularly helpful when your search returns a mix of source types
and you're only interested in peer-reviewed articles or long-form research.

![Publication type facet filter in SciX](fig/scix-publication-type.png){alt='Sidebar in SciX showing checkboxes for filtering by publication type such as journal, dissertation, or report'}


### Using Field-Specific Searches

You can target your search to specific parts of an article by using field
prefixes. These are especially useful when you're looking for a term in just
one section (e.g., the title) or want to exclude it from another (e.g., the body).

Common field-specific prefixes in SciX include:

- `keyword:` — author- or publisher-provided keywords
- `abs:` — title, abstract, and keywords
- `abstract:` — abstract text only
- `title:` — title only
- `body:` — article body only
- `ack:` — acknowledgments only
- `full:` — full text of the article

You can also use Boolean operators (`AND`, `OR`, `NOT`) to combine or exclude terms.

For example:

```text
abs:(crater AND mars) NOT body:jezero
```

This finds articles that mention crater and Mars in the title, abstract, or keywords,
but **exclude** any that mention Jezero in the body text.

![Field-specific keyword search syntax](fig/scix-field-specific-search.png){alt='SciX search bar showing field-specific search using abs:(crater AND mars) NOT body:jezero'}



## Exploring the Abstract View

Click an article title to open the abstract view. Here, you can find:

- Detailed bibliographic information (title, authors, publication
  details)
- Links to additional resources like open access articles, software,
  and datasets

![Detailed abstract view with links to open access, datasets, and software](fig/scix-useful.png){alt='Abstract page showing detailed metadata and icons for datasets, code, and open access'}

::: challenge
### Challenge

Select an article and review its abstract view. What extra details can
you find that weren't in the results view?
:::

### Launching Searches from the Abstract View

In the abstract view, SciX displays **provided keywords** associated with
the paper. These keywords are clickable — selecting one launches a new
search using that term.

This is a fast way to explore related literature or shift your search
direction based on what you find interesting in the current article.

![Abstract view showing clickable keywords](fig/scix-abstract-keywords.png){alt='SciX abstract page with magnifying glass icons next to keywords, indicating clickable search links'}

::: discussion
## Reflection and Discussion

Take a few minutes to perform a search on a topic relevant to your work
using both author and keyword searches. Then, discuss with a partner:

- What did you search for?
- Did you find relevant materials?
- What aspects of the process were straightforward or challenging?
:::

::: challenge
## Bonus Challenge

Try exporting a citation from one of your articles. Explore the export
options and compare different formats.
:::

::: keypoints
- SciX enables effective author and keyword searches with powerful
  synonym expansion.
- Facet filters help narrow down results by author variants,
  institutional affiliation, and publication date.
- The abstract view provides in-depth details and links to additional
  resources.
:::
