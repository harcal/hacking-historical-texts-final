# Workflow

<figure>
    <p class="center-text">
        <a href="{{ site.baseurl }}/index.html">Home</a> |
        <a href="{{ site.baseurl }}/pages/background.html">Background</a> |
        <a href="{{ site.baseurl }}/pages/sources.html">Sources</a> |
        <a href="{{ site.baseurl }}/pages/workflow.html">Workflow</a> |
        <a href="{{ site.baseurl }}/pages/analysis.html">Data Analysis</a> |
        <a href="{{ site.baseurl }}/pages/reflections.html">Reflections</a> |
        <a href="{{ site.baseurl }}/pages/bibliography.html">Bibliography</a> |
        <a href="{{ site.baseurl }}/pages/credits.html">Credits</a>
    </p>
</figure>

The first step was finding data relating to a topic I wanted, which would be something regarding the Irish in America during or after the Great Famine. After selecting a viable dataset which could yield potentially beneficial results, the data was downloaded from the Harvard Dataverse and modified by me to work in compatibility with Tableau. Identifiers such as sex and location were altered in order to be better recognized by Tableau. The formatting used by the author and contributors was odd to me, as it was counter intuitive when using that information in tandem with data analysis programs. Below you can see a workflow for the overall process taken when gathering, researching and analyzing data. 

![Example Image](https://i.imgur.com/YnqmANs.png)

The process involved regarding the data consisted of three steps:

* Getting the data
* Cleaning/altering the data
* Visualizing the data

![Example Image](https://i.imgur.com/2VBOofb.png)

Once a suitable dataset was found I began cleaning and changing the codex in place in order to make the file more compatible for Tableau. I also created two backups of the file as opening Tableau seemed to sometimes cause data corruption. I also saved the file as a text file rather than a CSV file. In the above image you can see an example of me cleaning the data, in that specific case deleting information that would be useless when analyzing and comparing in Tableau. Columns containing large amounts of descriptive text would be useless, and were deleted. The variables "m" and "f" were changed to Male and Female. Unforunately for two important variable it was difficult to reformat them for analysis, as they contained too many differing identifiers. For example, the last known location column was not changed as it would require finding and replacing the acronyms of every state and city manually, which would take too much to do for a project of this scale. The date identifier also opened up a new question regarding the data, as the advertisement year of each individual did not have a millenial/centurial prefix. This meant it was impossible to tell which century the advertisement was originally listed. 

I also chose to delete identifiers that were missing to be data to be relevant/valuable, such as "occupation_new" and previously known locations of the 4th or 5th. Identifiers relating to the location of the contact were sparse as well, and were thus deleted. The primary data left behind would have a focus on the person lost. 
