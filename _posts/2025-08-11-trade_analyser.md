---
title: CHASS Trade Analyser Canadian International Merchandise Trade (CIMT) Database
author: Tanya Nguyen
date: 2025-08-26
category: Jekyll
layout: post
---
# Introduction

**Database Availability**: To current Athabasca staff and students

**Database link**: [Trade Analyser Canadian International Merchandise Trade Database](https://0-clouddc-chass-utoronto-ca.aupac.lib.athabascau.ca/ds/trade/){:target="_blank"
}

**About**: The Trade Analyser provides web interfaces for Canadian trade data and World trade data produced by Statistics Canada, International Trade Division.

Canadian trade data contains monthly trade statistics, 1988 to latest available, showing quantity and value (CDN $), HS10 (imports)/HS8(exports) (Harmonized Commodity Description and Coding System) classification, province or state of the U.S., country of origin/destination, and dutiable trade indicator and amount.

World trade data contains annual trade statistics, showing volume of trade (US $) between pairs of trading countries, imports and exports, 1980-2005. This data is no longer updated by Statistics Canada.

Trade Analyser @ CHASS features:
* Various levels of data aggregation
* Commodities search
* Bilingual

**Date range coverage**: 1988-2014

**Similar Tools**: The [Search by product (HS code) – Trade Data Online](https://ised-isde.canada.ca/app/ixb/tdo/crtr.html){:target="_blank"}, will allow you to pull import and export searches similar to Trade Analyser with a wider and current date range coverage from 1990 to the latest 24 months.

# Documentation & Help
To get started look up the data codebook and view the commodity and country codes used in Trade Analyser. Another useful document to browse is the [2007 Code Changes](https://0-clouddc-chass-utoronto-ca.aupac.lib.athabascau.ca/ds/trade/en/manuals/Import_End200612_Start200701.xls){:target="_blank"} Excel sheet (this will directly download into your Downloads folder) or the [Canadian Export Classification](https://www150.statcan.gc.ca/n1/en/catalogue/65-209-X){:target="_blank"} (website), which you can have open while you are trying to search the commodity code.

# Instructions: Canadian Import and Export Tables


This section of the Trade Analyser allows you to select commodities that are imported and exported into or out of the Canadian provinces and from which countries. There are two types of import tables to download data from: **HS10 Imports Monthly Data** and **HS10 Commodities** and two types of export tables: **HS8 Exports Monthly Data** and **HS8 Commodities**. 

You will need to submit a query to pull data from these tables. However, since the query form is identical among the tables, the instructions below will cover all of them at once using images from the HS10 Imports Monthly Data table. In addition, when comparing the two import table outputs the data seems identical. **HS8 Exports Monthly Data** will show monthly quantity and values of the commodities. **HS8 Commodities** may not be as helpful as it only shows history or code changes of a commodity. 

## Step 1: Specify HS commodities codes (10,6,4 or 2 digits) for retrieval
1. There are three options to select the HS commodity codes. The easiest is to **manually enter the codes**. To browse the codes, download and open the [2007 Code Changes](https://0-clouddc-chass-utoronto-ca.aupac.lib.athabascau.ca/ds/trade/en/manuals/Import_End200612_Start200701.xls){:target="_blank"} Excel sheet or [Canadian Export Classification](https://www150.statcan.gc.ca/n1/en/catalogue/65-209-X){:target="_blank"} (website). Click **SEARCH Harmonized System (HS)** link to open the **Trade HS Commodities Search box**.

2. The ‘Search by’ drop-down menu allows you to search by two options: 
    1. 	Commodities HS Codes (combinations of 10, 6, 4, or 2 digits can be used, i.e. 2903390023, 285200, 1099, 12) or 
    2. Commodities HS Names (i.e. apple, flooring, footwear).
3. The ‘Search Criteria’ drop-down menu allows you to change the search criteria to ‘contains’, ‘equals’, ‘starts with’, or ‘ends with’ the keyword or number entered.
4. You can select the code to add to your query by checking the check box.
5. You can continue to search different HS names or HS codes at a time, and can add multiple HS codes to your query (separate each code with a single space).
6. To remove the HS code, uncheck the box.
7. Once you have selected the HS codes of your choice (i.e. 0804300020 = pineapples, dried; 4409101020 = Flooring, coniferous (softwood)), select “-add codes to query-”. Now close the Trade HS Commodities Search box or minimize the box to return to the database.
![This is a screenshot of the Trade HS Commodities Search as explained in the HS10 Imports Monthly Data section. It shows apple as a keyword being searched and 120 records were found. Pineapples, dried is selected.](_site\assets\images\commodities-search.png)

## Step 2: Specify provinces of clearance for retrieval
Select the provinces you want to include in your retrieval for the commodities. If unselected, it will search all 13 provinces.

![This is a screenshot of Step 2 showing the 13 provinces that can be selected to search for imported commodities.](_site\assets\images\province-clearance.png)
 
## Step 3: Specify countries of origin for retrieval
Select the countries you want to include in your retrieval for commodities. If unselected, it will search for all 287 countries.
![This is a screenshot of Step 3 showing the 287 provinces that can be selected to search for imported commodities.](_site\assets\images\countries-origin.png)
 
## Step 4: Specify a time frame
1.	Select the start date and end date for the time period selection. The format can be in yyyy-mm or yyyy. Note this database only covers years from 1988 to 2014.
2.	If the time period is left blank, it will pull all dates from 1988 to 2014.

## Step 5: Specify the output details and submit query
1.	There are some optional fields for the data output, such as add province and country codes to the dataset, email address notification for larger downloads, or a zip file compression. For the most part, these can be left at the defaults.
2.	For the output format, you can select text, html, CSV, or DBF. CSV is recommended which will allow you to download a copy that you can edit and run analyses on.
3.	Select submit query. A new tab will open with two split screens showing the query job was completed.

## Query Completed Job
1.	If the query was successful, a message will show the job was completed and the link to the files can be downloaded or viewed.

![A screenshot of the completed job query was ran and two Excel sheets can be downloaded.](_site\assets\images\query-job.png)

2.	For the most part, you will only need the file on the right-hand side of the split window screen.
3.	The CSV file should be simple to interpret, and the columns at the top for the import or export tables are:
    1.	dt-Date (YYYY-MM): year-month or the trade
    2. hs-HS10 code or hs-HS8 code: this was selected in step 1
    3. desc_en-Province of Clearance or desc_en-Province of Origin: this was selected in step 2
    4. desc_en-Country of Origin or desc_en-Country of Destination: this was selected in step 3
    5. dutiable-Dutiable Trade Indicator (N=No, Y=Yes): from the Import Tables
    6. duty-Customs Duty Collected ($CDN): from the Import Tables
    7. reexport-Re-export indicator (N=N, Y=Yes): from the Export Tables
    8. quantity-Quantity
    9. value-Value ($CDN)