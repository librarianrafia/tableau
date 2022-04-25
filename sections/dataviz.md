
# Data Viz with Tableau 

# Data

## What is Data?
 > "What are the differences between data, a dataset, and a database?
  * *Data* are observations or measurements (unprocessed or processed) represented as text, numbers, or multimedia.
  * A *dataset* is a structured collection of data generally associated with a unique body of work.
  * A *database* is an organized collection of data stored as multiple datasets. Those datasets are generally stored and accessed electronically from a computer system that allows the data to be easily accessed, manipulated, and updated. 
  - [Definition via USGS](https://www.usgs.gov/faqs/what-are-differences-between-data-dataset-and-database#:~:text=Data%20are%20observations%20or%20measurements,a%20unique%20body%20of%20work.) 
* For the purposes of this workshop, we recommend finding an already existing data set for your project, as creating, cleaning and/or structuring a new dataset is often time and labor intensive. 
    * Remember that just because data may be avaible digitally, it does *not* automatically exist as a dataset. You may have to do work manually (copying and pasting into a spreadsheet) or computationally (scraping the data) to create a dataset usable for analysis and data viz.  
* Read more about [Data Cleaning.](https://www.tableau.com/learn/articles/what-is-data-cleaning)

# What are the stages of data ?

[![data life cycle](https://github.com/librarianrafia/tableau/blob/main/images/rdc.png)](https://github.com/librarianrafia/tableau/blob/main/images/rdc.png)

## Processed/transformed
* Processing data puts it into a state more readily available for analysis, and makes the data legible. For instance it could be rendered as **structured data**. This can also take many forms, e.g., a table. 
* Examples of structured data formats: 
- XML
- JSON
- CSV
- Note about Text as Data in Tableau

## What makes a useful dataset?
* [Analyze stage of the Data Lifecycle.](https://www.usgs.gov/data-management/analyze)

* What do we mean by a 'good' data set? 
The considerations you should keep in mind for [creating a data set,](https://researchdata.ox.ac.uk/home/managing-your-data-at-oxford/organising-your-data/) are the same things you want to look for when searching for a dataset for research. 
* Is there a [Data dictionary](https://www.usgs.gov/data-management/data-dictionaries) or any kind of documentation that states how the date was derived and why it was recording in the way it was. 
   * Good documentation makes material *understandable, verifiable, and reusable* (by you or by others).
   * What are the file naming conventions? 
   * Is there metadata?
       * Metadata is simply ‘data about data’.  It is related to the broader contextual information that describes your data, but is usually more structured in that it conforms to set standards and is machine readable.  One typical use of metadata is to create a catalogue record for a dataset held in an archive. By using a standard set of tags, an automatic system can tell where the information about the title, creator, description and so forth begin and end.  
   * Data that is not structured or cleaned is referred to as unstructured, noisy or dirty. *A messy data set can be used but you will need to spend time [processing that data:](https://www.usgs.gov/data-management/process) either cleaning, structuring and/or organizing it.* 

# Preparing Data
* After gathering the data needed for research and before conducting the actual analysis, data often requires preparation (also sometimes refereed ot as pre-processing the data). Preparing data can take a lot of time and effort.
* "Data cleaning is the process of fixing or removing incorrect, corrupted, incorrectly formatted, duplicate, or incomplete data within a dataset. When combining multiple data sources, there are many opportunities for data to be duplicated or mislabeled." 
    * How do you clean data?
        * Step 1: Remove duplicate or irrelevant observations
        * Step 2: Fix structural errors
        * Step 3: Filter unwanted outliers
        * Step 4: Handle missing data
        * Step 5: Validate and QA (quality assurance)
            * [Guide To Data Cleaning: Definition, Benefits, Components, And How To Clean Your Data](https://www.tableau.com/learn/articles/what-is-data-cleaning) 

## Forms of data
* There are many ways to represent data, just as there are many sources of data. 

# Data Viz

## What is data visualization?
* You are making an argument visually with data. 
* Data viz workflow
- [Why are you making a viz? For who?](https://www.tableau.com/learn/articles/data-visualization)
- What data do you need?
- What is the [best viz](https://www.juiceanalytics.com/chartchooser)for your purpose? 
- (Spatial data:map, temporal data: timeline, bar chart, [etc.](https://datavizcatalogue.com/))
    -see more about [Taxonomy](http://www.interactiondesign.us/courses/2011_AD690/PDFs/Shneiderman_1996.pdf)
- What data will you actually represent ?
- You want enough data that your argument makes sense, but too much data makes the viz confusing.


### Good vs bad Viz
* [dataisbeautiful](https://www.reddit.com/r/dataisbeautiful/)
* [dataisugly](https://www.reddit.com/r/dataisugly/); [WTFviz](https://twitter.com/wtfviz?lang=en) 

* [A collection of dataviz caveats by data-to-viz.com](https://www.data-to-viz.com/caveats.html)
* [misrepresentation](https://imgur.com/wll2Vaq)

## Tools for preparing/cleaning data
- You might use Excel, [Open Refine](https://openrefine.org/) or Tableau prep

# Tableau 

## Tools
* The benefits of pre-built tools are they are usually easy to use, they don’t require too much technical knowledge, and they can be very useful in teaching.
- Example: Tools: Excel or Tableau vs. Coding (Python & Panda) 
* The main drawback of pre-built tools is because they have predefined functions, they offer less control to the researcher and limit what a user can accomplish. (The dates issue in excel!)
* Choosing a pre-built tool is based on the goal of the user. Each pre-built tool has its own strengths, outputs, and weaknesses. 

# What is Tableau? 
* Why choose [Tableau?](https://www.tableau.com/products)
* What does Tableau require? What assumptions are built into the tool(s)? 
 - [Learning paths](https://www.tableau.com/learn/learning-paths?_ga=2.67567634.2062626085.1648763358-586568521.1648763358)
    * Does your data need to be in a specific format for Tableau?
    * How do you import data into Tableau? 
    * How do you create worksheets, visualizations & dashboards in Tableau?

    [Tableau Help is your friend!](https://www.tableau.com/support/help)    

### Tableau options
- Tableau product suite: [Tableau Prep](https://www.tableau.com/products/prep), Tableau Desktop, Tableau Server & Tableau Online, Tableau Mobile.
* You have data that you want to [create a visualization of.](https://www.tableau.com/learn/articles/data-visualization)
    * What are the different options?
    * Which ones do you have access to?
    * What is it you want to do?

 **Tableau Public**
* "Tableau Public is *free software* that can allow anyone to connect to a spreadsheet or file and create interactive data visualizations *for the web."*
* Sign up for a [free account here](https://public.tableau.com/en-us/s/)
* [Viz of the Day](https://public.tableau.com/app/discover/viz-of-the-day)
* [More data viz examples](https://www.tableau.com/learn/articles/best-data-visualization-blogs_)


**Tableau Desktop**
* [Tableau Desktop](https://www.tableau.com/products/desktop) is part of the Tableau Creator suite. It allows you to *analyze data* and *create visualizations* on your desktop.
- Does your institution subscribe? Or are you eligible for their academic program as a [student or instructor?](https://www.tableau.com/community/academic)
    * [Tableau for Teaching:](https://www.tableau.com/academic/teaching): Teach data skills across all disciplines and levels in your classroom. 
    * [Request free 1 year license here.](https://www.tableau.com/academic/teaching#form)

## Tableau GLossery 
* [Useful terms](https://help.tableau.com/current/reader/desktop/en-us/terms.htm)
* [Tableau File Types and Folders *Applies to: Tableau Desktop*](https://help.tableau.com/current/pro/desktop/en-us/environ_filesandfolders.htm)
* [Tableau Environment](https://help.tableau.com/current/pro/desktop/en-us/environ_st.htm)


## Tableau Workflow & Demo
* [See slides](https://github.com/librarianrafia/tableau/blob/main/sections/storydata.pdf)


### Examples in Tableau Public
- [Peace Ossom Williamson - Profile | Tableau Public](https://public.tableau.com/app/profile/pow123)
- [Paige Morgan - Profile | Tableau Public](https://public.tableau.com/profile/paige.morgan)
- [As Colleges Announce Changes to Their Fall Instruction Plans, This Map Will Be Updated](https://public.tableau.com/views/ChangestoCollegesFallPlans/ChangestoCollegesFallPlans?%3Aembed=y&%3AshowVizHome=no&%3Adisplay_count=y&%3Adisplay_static_image=y&%3AbootstrapWhenNotified=true&%3Alanguage=en&:embed=y&:showVizHome=n&:apiID=host0#navType=0&navSrc=Parse)
- [Mapping Social Movements.](https://depts.washington.edu/moves/index.shtml) Their maps are in Tableau, see [SNCC example here](https://depts.washington.edu/moves/SNCC_map-events.shtml) 



 
### *Highly recommended practices* 

#### Read the Data and methodology sections of research and/or data journalism articles
* When you are considering learning new tools or techniques, we highly recommend searching for academic or data journalism articles where the authors have asked similar questions or used related methodologies. 
    * When reading these articles, pay particular attentions to the literature review, and to the *data and methodology sections.* 
    * Where did these researchers find their data set they are using? 
    * If they created it, did they make it accessible in a repository on a website, or a Github repository?
- Read some data journalism articles on [The Pudding](https://pudding.cool/), [ProPublica](https://www.propublica.org/datastore) or this [roundup of data journalism projects from 2021](https://datajournalism.com/read/blog/best-data-journalism-projects-2021)
 - [The 10 Best Data Visualization Blogs to Follow -Tableau](https://www.tableau.com/learn/articles/best-data-visualization-blogs)

 
* Go to [The Pudding](https://pudding.cool/) and read one of their data journalism pieces. 
* In their [archive](https://pudding.cool/archives/), you can choose by topic or type of chart, based on your interests. 

* As you read, pay special attention to the following questions: 

## Their data
* Where did their data come from?
* Is the data public?
* How big was the data? Did they use all of it?

## Their analysis
* What is their thesis statement?
* What was their hypothesis?
* What choices did they make as the analysis developed?
* Were there caveats or ramifications to their choices?
* What were their conclusions?

## Their visualizations
* What types of visualizations did they use?
* Did the visualization help or hurt the arguments they made?
* Was the visualization distracting or confusing?
* Could you make a similar (if more simple) visualization?

## Overall 
* Did you think the article was interesting? 
* Did having data to back up their thesis statement help make their argument?

Further reading: This 3-part series on data journalism and data projects in general.
* [Part 1](https://pudding.cool/process/how-to-make-dope-shit-part-1/)
* [Part 2](https://pudding.cool/process/how-to-make-dope-shit-part-2/)
* [Part 3](https://pudding.cool/process/how-to-make-dope-shit-part-3/)

* [Info Viz Glossary](https://infovis-wiki.net/wiki/Category:Glossary)
* [The Data Notebook](https://uta.pressbooks.pub/datanotebook/)
* [A GENTLE INTRODUCTION TO EXCEL AND SPREADSHEETS FOR HUMANITIES PEOPLE](https://hfroehli.ch/2021/06/17/a-gentle-introduction-to-excel-and-spreadsheets-for-humanities-people/)

## [Link to Recording of session](https://hdl.handle.net/11274/13594)

