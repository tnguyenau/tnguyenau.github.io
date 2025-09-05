---
title: CHASS CANSIM
author: Tanya Nguyen
category: Jekyll
layout: post

---
# Introduction
**Database Availability**: To current Athabasca staff and students

**Database link**: [CANadian Socio-economic Information Management](https://0-clouddc-chass-utoronto-ca.aupac.lib.athabascau.ca/chasscansim/){:target="_blank"}

If you get a 400 bad request after clicking on the link, try clearing your browser’s cache cookies or open the link in an incognito or inprivate window. See the [AU Library Tech Support Guide](https://libguides.athabascau.ca/techsupport){:target="_blank"} on how to do this.

**About**: CANSIM (Canadian Socio-Economic Information Management System) is the Statistics Canada's computerized database of time series covering a wide variety of social and economic aspects of Canadian life.

**Coverage**: As of August 19, 2025, CANSIM contains 7473 tables. 

**Similar Tools**: [Statistic Canada Data Table](https://www150.statcan.gc.ca/n1/en/type/data){:target="_blank"}, as of August 19, 2025 there are 12,222 tables.

# Documentation & Help
* [CANSIM OLAP View Introductory Series](https://youtube.com/playlist?list=PLA3DBB5305593E4CE&si=QbWZLVRMRFAKBXu5){:target="_blank"}
** The CHASS DataCentre produced a series of introduction videos about using the OLAP view (Online Analytical Processing). You can access the OLAP view when in  the CANSIM Multidimensional View.

* [CANSIM OLAP View Frequently Asked Questions](https://youtube.com/playlist?list=PLA3DBB5305593E4CE&si=QbWZLVRMRFAKBXu5){:target="_blank"} (AU login required)

* [CANSIM Multidimensional Web Interface Help](https://0-clouddc-chass-utoronto-ca.aupac.lib.athabascau.ca/cansimdim/English/help.html){:target="_blank"} (AU login required)

# Instructions

CANSIM has two types of views, but we will go through the Multidimensional View which is the recommended view. Next, we will briefly show how to navigate the Vital Economic and Social Statistics about Canada.

## Multidimensional View
1.	From the home page (CANSIM at CHASS - University of Toronto), select Multidimensional View, then select CANSIM Multidimensional @ CHASS Main Menu.

2.	In the CANSIM Main Menu, there a few options to search the CANSIM tables or series. The easier option is to start with the Text Search, but if you just want to browse first, try the Browse tables by subjects, keywords, or surveys.

### Text Search

1.	Click the more search options to modify the search fields. Let’s try searching: indigenous people.

2.	Use the radio buttons to select a keyword match by: all the keywords, any of the keywords, or the phrase. If searching indigenous people you will get the following results:

    * All of the keywords: 75 tables
    * Any of the keywords: 521 tables - the largest number of search results
    * The phrase: 24 tables - smallest search results, as it searches the keywords together as a phrase.

3.	There are six search fields that can be searched (table titles, table keywords, dimension descriptions, dimension member descriptions, units of measure, and footnote texts). These can be left at the defaults which checkoff the first four fields.

4.	The next search field is **include the following tables in the results**. This can also be left as the default (i.e. all tables matching the search criteria).

5.	The next search field **include tables of the following frequency in the result**, and its default setting **all tables regardless of frequency**. This can be changed to daily, weekly, monthly, yearly tables, etc.

6.	Lastly you can change search results list order via order the results by. Use the radio buttons to select ordering by table numbers or table labels. Below is a screenshot of a text search for indigenous people, search by phrase, and results ordered by table labels:

![The CANSIM Multidimentional View with red arrows pointing where the search filters were edited (i.e. search for indigenous people, run the search as a phrase, and order the result by table labels.](/assets/images/cansim_1.png)
 
<ol start="7"> <li>Select Submit. On the search results page, there is a table with different column fields and we’ll describe each below: </li>
</ol>

* **Product Identification numbers (PIDs) (replaces the CANSIM table numbers)**: usually an 8-digit number. You can also copy this number and search it in the [StatsCan Data Table](https://www150.statcan.gc.ca/n1/en/type/data){:target="blank"}. If you need to cite this table in your assignment, you can use the table link from the StatCan website.

* **Table Number**: usually a 7-digit number. For tables released after June 4, 2018, they will not have a table number (i.e. N/A). These are also searchable in the [StatsCan data table](https://www150.statcan.gc.ca/n1/en/type/data){:target="_blank}.
    
* **Info**: usually a pop-up window will open and show the number of series in the data, the data date range, data release date, and data dimensions. At the top-right corner there is a download button to download the data metadata.

    ![Screenshot of the info pop-up window. It pop-up window reads: Table 37100117 - Educational attainment in the population aged 25 to 64 living off reserve by Indigenous group, occasional (Percent). A red box surrounds the download button.](/assets/images/cansim_2.png)
    
* **[olap view -new-]**: will open in a new tab. This is an interactive way to manipulate the data table to move dimensions and nest dimensions. It recommended to view the CANSIM OLAP View Introductory Series videos to get started. 
    
* **[by dimensions]**: (more advanced). This will open the table in the same window. It will display which survey(s) the data if from, related subjects that describe the table, and the table dimensions. After selecting and submitting the table dimensions, it will return some series, which you can select and add to your series cart. From there you can modify the series output and submit a query.
    
* **[by series]**: (more advanced). It works the same as [by dimensions] except instead of choosing the table dimensions and returning the series matching the selected dimensions, this displays all the series.

### Tables by Subject
1.	Browse tables by subject. There is a total of 31 subjects that can be expanded to show the nested subjects. Help on navigating the page is available via the help (?) link on the top right corner.

2.	Let’s expand **Travel and Tourism** and select **Domestic Travel**.

3.	This will return the search results page with a table with different column fields. These column fields are described in detail in the previous section **Text Search** in step 7.

### Tables by Keywords
1.	Browse tables by keywords which are alphabetically listed. Keywords that are larger in font have more tables.

2.	Clicking on a keyword will return result page with different column fields. These column fields are described in detail in the previous section **Text Search** in step 7.

### Tables by Surveys

1.	Browse tables by surveys. Surveys are listed alphabetically, and the default page shows surveys starting in A. Click on a different letter at the top ([A] [B] [C] [D] [E]) to navigate to a different alphabetical listing of surveys.

2.	Alternatively, can change the view to show surveys by number via **[by_survey_number]**

3.	Let’s select the letter **[I]**, and select Indigenous Peoples Survey. The table list the following information from left to right:

    1. **survey number** (i.e. 3250)
    
    2. **[survey info]**: Note, these links will not work as AU’s proxy link is added, but you can [search the surveys on StatsCan](https://www23.statcan.gc.ca/imdb-bmdi/pub/index-eng.htm){:target="_blank"}
    
    3. **[tables]**: some have table links that will return a result page with different column fields. These column fields are described in detail in the previous section **Text Search in step 7**.

## Vital economic and social statistics about Canada

The Vital Economic and Social Statistics about Canada can be accessed from the [CANSIM homepage](https://0-clouddc-chass-utoronto-ca.aupac.lib.athabascau.ca/cansimdim/English/ceo/){:target="_blank"}.

There are eight different products that are viewable:
* National accounts
* Labour markets
* Prices
* International trade
* Goods-producing industries (manufacturing, construction and resources)
* Services (trade, transportation, travel and communications)
* Financial markets
* Provincial

Since each product has many different dimensions that can be selected to create tables, we won’t go into each one in detail. However, the navigation for each product is similar, so let’s try looking at **Goods-producing industries (manufacturing, construction and resources)** as an example.

### Navigating Goods-producing industries (manufacturing, construction and resources) Example

1.	You will be taken to the [Goods-producing industries](https://0-clouddc-chass-utoronto-ca.aupac.lib.athabascau.ca/cansimdim/English/ceo/goods.html){:target="_blank"} page.

2.	At the top is a table of contents, let’s click on Farm cash receipts. This scrolls the page to the Farm cash receipts table containing the columns: total cash receipts, animal products, crops, and direct payments.

3.	Click on link **v170365** underneath barley. This will open a series cart page. Let’s go over the seven steps displayed in the series cart that can be edited:

	 1. **Your Series Cart contains the following series**: This shows a link to the Table 32100046 which if you select, will take you to Farm Cash receipts table where you can select other dimensions in the series cart (i.e. can change the geography and type of cash receipt). However, we will keep this the same. Canada [11124]; Barley [1151141](Mar-1971 to Mar-2025, Data: 217)

	2. **Optionally specify a time period**: As the website instruction says, this is optional and the start and end dates can be changed in the following format (yyyy-mm-dd or yyyy). Let’s change the start date to 2000.

	3. **Output display (when multiple series selected, show data...)**: Keep this the default (i.e. As time series listed as columns), as it is the easiest to view displayed output.

	4. **Output format**: There are multiple formats available to output this series (Plain text, HTML, CSV, Excel, SAS, SPSS, Plot-lines graph, and Plot-bars graph). Select the one of your choice.

	5. **Display data quality information**: Leave as the default value (i.e. no). If select yes, the queried table when submitted will show two columns about the status quality of each data point. Click the ‘see details’ link to learn more about the statuses.
    
    6. **Printer friendly Series Cart**: Leave as the default value (i.e. uncheck)
    
    7. **Submit Query**: Click the submit button and your series will either open in a new browser or download the file depending which output display was selected.
    
    8. This produces a tabular table with the date column and the dimensions that were selected (i.e. year-month and barley (dollars).

---
_Data and RDM Learning Hub © 2025 by Tanya Nguyen is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). To view a copy of this license, visit [https://creativecommons.org/licenses/by-nc-sa/4.0/](https://creativecommons.org/licenses/by-nc-sa/4.0/). Jekyll Theme forked from [Tao He](https://sighingnow.github.io/jekyll-gitbook/)_
 
