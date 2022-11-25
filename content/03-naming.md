---
title: Step 3 - Naming Conventions
nav: Naming
---

If implemented early and consistently, a standardised system for naming files can:
- make file naming easier
- facilitate access, retrieval and storage of files
- make it faster to navigate files
- guard against misplacing or losing files
- assist with version control
- identify obsolete or duplicate records

## What is a File Naming Convention?

A File Naming Convention (FNC) is a system for naming your all your files, where the filename includes a description of the contents and the context. This is a system that is best established as early as possible; ideally before collection research data.

## What is a File Name? 
***File names*** are simply those names that you must give when saving to any new file, and which are listed in the directory of a folder. The FNC is used at that stage with each file that forms any part of your research.

### What are the benefits of using a file naming convention? 
Naming files consistently, logically and in a predictable manner will prevent against unorganised files, misplaced or lost data.  It can also prevent backlogs or project delays by presenting a clear and real-time display of the current or completed work.

### Coming up with a plan for your team on how to name files.

{% include alert.html text="Former PhD student and subsequent founder of the Figshare platform, Mark Hahnel, typified a common challenge: 

*‘During my PhD I was never good at managing my research data. I had so many different file names for my data that I always struggled to find the correct file quickly and easily when it was requested. My former Principle Invesitgator was so horrified upon seeing the state of my data organisation that she held an emergency lab book meeting with the rest of my group when l was leaving’*.  

Research Information, April/May 2014  " align="center" color="success" %}

Your research team should agree on the following elements of a file name prior to data collection:
* Vocabulary - choose a standard vocabulary for file names, so that everyone uses a common language
* Punctuation - decide when to use punctuation symbols, capitals and hyphens
* Dates - agree on a logical use of dates so that they display chronologically i.e. YYYY-MM-DD
* Order - confirm which element should go first, so that files on the same theme are listed together and can therefore be found easily
* Numbers - specify the amount of digits that will be used in numbering so that files are listed numerically e.g. 01, 002, etc.

You can also:

* Capitalise the first letter of every new word with no intervening spaces 
i.e. `PAHospitalAdmissionICU_2010_2020_Raw.csv`	
* Keep filenames a reasonable length and keep file name information (metadata) separated using upper and lower case 
i.e.  `Image02_PacificOcean_20200621.jpg`
* Use logical order for sequential number with padded zeros
i.e. instead of `1,2,3` use `001, 002, 003 or 01, 02, 03`
* For Version numbers consider  `V1, V2` and multiple versions `V1, V2, V2.1` etc.
* Document your FNC in a `ReadMe.txt` or other documentation file in main shared project folder. It can be useful for staff orientation.

See this example below which uses a `standard date format` followed by `file topic information` divided by `underscores _`, with words using `CapitalCase` and ending in the `file type`:

`Date_Location_Sensor.filetype`

`YYYYMMDD_SiteA_SensorB.CSV`

Which when applied, would look like this below

`20220621_MtGravatt_Humidity.CSV`

{% include alert.html text="Some characters may have special meaning to software or the operating system of computers. Avoid using the following when you are naming files:

`/   \   "   '   *   ;   -   ?   [   ]   (   )   ~   !   $   {   }   >   #   @   &   |   space   tab   newline   `

Source: [IBM Knowledge Centre](https://www.ibm.com/support/knowledgecenter/en/ssw_aix_71/com.ibm.aix.osdevice/filename_conv.htm)" align="left" color="warning" %}

{% capture text %}
Create an easy naming convention for your data files and documents. 

Any dates are best stored with YYYYMMDD because it can be re-ordered chronologically.

Avoid spaces in your file names because some applications do not support it.{% endcapture %}{% include card.html header="First steps" text=text %}

{% capture text %}
Read and follow Edinburgh University's simple [13 Rules for file naming conventions](https://www.ed.ac.uk/records-management/guidance/records/practical-guidance/naming-conventions){% endcapture %}{% include card.html header="Intermediate steps" text=text %}

{% capture text %}
Do you have a policy in your team around naming conventions? If not, this is a great way of discussing the priorities of the research data.{% endcapture %}{% include card.html header="Advanced steps" text=text %}


### Internal Resources
* Talk to your Research Support Services librarian at [library@griffith.edu.au](library@griffith.edu.au).


### External Resources
* [Naming things by Jenny Bryan](https://speakerdeck.com/jennybc/how-to-name-files)
* [File naming and folder conventions by CESSDA ERIC](https://www.cessda.eu/Training/Training-Resources/Library/Data-Management-Expert-Guide/2.-Organise-Document/File-naming-and-folder-structure)
* [13 Rules for file naming conventions by The University of Edinburgh](https://www.ed.ac.uk/records-management/guidance/records/practical-guidance/naming-conventions).
