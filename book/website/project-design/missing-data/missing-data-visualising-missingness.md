<!-- 
Identify the major themes/topics that make up your chapter. 
These will be the subchapters of your chapter.
Write about each one in a different `chapter-content.md` file.
Make as many copies of this file as you need for all your subchapters
-->

(pd-missing-data-visualising-missingness)=
# Visualising Missingness

Visualization techniques can be incredibly helpful when trying to understand your data and any patterns of missingness. Different programming languages offer unique tools and packages to help with this. We will introduce some for [R](pd-visualising-missingness-r) and for [python](pd-visualising-missingness-python). Lastly, we will use some of these tools to show simulated visualisations of all three data structures described in {ref}`pd-missing-data-structures`. 

(pd-missing-data-visualising-missingness-plottypes)
## Plot Types
1. Nullity Matrix
2. 
> **Write an introduction for your subchapter here**.
> Your introduction should briefly introduce the topic of your subchapter and highlight its key ideas.
> Even though your introduction should be short and focused, you should try to explain why and how the subchapter fits the overall context of the chapter and what the reader should expect to learn from it.

<!-- 
> Each of the key ideas you talk about in the introduction should have a section of its own.
> When you mention a key idea in your introduction, remember to cross reference it to the section of your subchapter where you explain it further.
> This will be useful for people who may only want to read specific parts of your content.
> See the [style guide](https://the-turing-way.netlify.app/community-handbook/style/style-crossref.html) for The Turing Way's recommendations on cross referencing.

> In this template, we assume that our subchapter has three key ideas, your subchapter may have more or less than this. 

> It may be beneficial to run your content through a grammar checker (such as Grammarly) to catch grammatical mistakes.
-->

<!-- 
In the label, replace `keyidea1` with a word that best describes the section or key idea you want to explain -->
(pd-missing-data-visualising-missingness-R)=
## R

> **Talk about your key idea in detail**. Feel free to use images, code blocks, and admonitions to communicate your ideas.
> You may break the section down into subsections if you wish, however, remember to add [labels](https://the-turing-way.netlify.app/community-handbook/style/style-crossref.html) to any additional headers you create to facilitate cross-referencing.

> Remember to use the [style guide](https://the-turing-way.netlify.app/community-handbook/style.html) and Jupyter Book's [Cheat Sheet](https://jupyterbook.org/reference/cheatsheet.html) to guide your writing.
> The [style guide](https://the-turing-way.netlify.app/community-handbook/style/style-citing.html) also contains _The Turing Way's_ recommendations for referencing and citation.

> To include an image in your writing, use the MyST directive shown below. 
> Remember to add your image to the `figures` [folder](https://github.com/the-turing-way/the-turing-way/tree/main/book/website/figures) and use the correct path, else it will not be displayed.

```{figure} ../../figures/image-name.png
---
name: image-name
alt: describe your image for readers who rely on screen readers
---
Your image caption here
```

> To include code blocks, simply enclose your code in three sets of backticks shown below.

```python
def simple_function():
    pass
```

> To include an admonition or to highlight a block of text that exists slightly apart from the narrative of your section, use the directive shown below. Jupyter Book's [documentation](https://jupyterbook.org/content/content-blocks.html#) has other useful examples.

```{note}
Here is a note!
```


(pd-missing-data-visualising-missingness-Python)=
## Python
The [missingno python package](https://github.com/ResidentMario/missingno) is a great tool for visualizing missing data. 


(sectioninitials-filename-summary)=
## Summary

> **Add a short summary of this subchapter with key takeaways.**
> You may also recommend and link to other chapters/subchapters you want your readers to explore after reading this subchapter.

| Plot Type | R package and function | Python missingno function |
| -------- | ------- | |
| Nullity matrix | vis_miss | matrix |
| Nullity by Column |  | bar |
| Heatmap of nullity correlation | | heatmap |
| | | dendogram |

<!-- IMPORTANT!

- Use this template to create your chapter's subchapters.
- Refrain from writing very long subchapters as readers may be unwilling to read them. Rather, you should split long subchapters into smaller subchapters if necessary.



BEFORE YOU GO

- Have a look at the Style Guide and the Maintaining Consistency chapters to ensure that you have followed the relevant recommendations on
  - Avoiding HTML
  - Consecutive headers
  - Labels and cross referencing
  - Using images
  - Latin abbreviations
  - References and citations
  - Title casing
  - Matching headers with reference in table of content

-->