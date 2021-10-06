# Assignment 1 - Data Curation

Author: Anushna Prakash  
Date: October 7, 2021  
Class: DATA 512 - Human-Centered Data Science

## Purpose
The goal of this project is practice proper documentation of process and sources from start to end of a complete project. For this project, I graph page visits to English Wikipedia pages from 2008 to 2021 August. 

## Licenses
The data for this project is obtained from [Wikimedia Foundation REST API](https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions).  
This repository is licensed under the MIT license. The MIT License is a permissive free software license originating at the Massachusetts Institute of Technology (MIT). As a permissive license, it puts only very limited restriction on reuse and has therefore an excellent license compatibility. For more info please see: [MIT license](https://snyk.io/learn/what-is-mit-license/).

## Data Sources
There are two sources of data for this project. Both require the use of the Wikimedia Foundation REST API. There was a change to how the data is collected in May 2015 that eliminated crawler traffic. From the [Wikimedia legacy Pagecounts API documentation](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts): "This API makes available the pagecounts aggregated per project from January 2008 to July 2016. The main difference among pagecounts and the current pageview data is lack of filtering of self-reported bots, thus automated and human traffic are reported together." New data is collected in the [Pageviews API](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews). There is a one year overlap in this data collection.  
