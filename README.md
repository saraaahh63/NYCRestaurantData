
This project is the product of interdiscplinary research conducted at NYU Shanghai's [Humanities Research Lab](https://www.historybeyond.com/). The Humanities Research Lab brings together undergraduate researchers in data science, interactive media, history, and more to explore how emerging mediums can transform the way we research, experience, and learn history. These students produce collaborative digital humanities research supervised by [Professor Heather Ruth Lee](https://www.heatherruthlee.com/).

NOTE: THIS IS A WORKING DOCUMENT

## The Restaurant Owner Database
**A Quantitative Study of Immigration, Identity, and Restaurant Ownership in Nineteenth and Twentieth Century New York**

The Restaurant Owner Database is a database of licensed restaurant owners in New York City from 1870 to 1933 built from business licensure and census records compiled and cleaned by the Humanities Research Lab. The purpose of this GitHub repository is to introduce data processing and historical research conducted with the Restaurant Owner Database. This is an ongoing project so this repository will be continuosly updated to reflect our changing work.

## Researchers (Summer & Fall 2020)

- Sarah Tahir
- Yi-Chen (Cinny) Lin
- Yinqi Wang
- Yujie (Tracey) Lan
- Huanci (Mary) Wang
- Dorothy Zhang
- Leo Zhang
- Omar Hammami
- Feifan Li

## Abstract

This project explores the relationship between immigrant experiences and restaurant ownership in New York City during the late nineteenth and early twentieth centuries through a quantitative study of the Restaurant Owner Database. Through the use of data visualization, geocoding, and other forms of data augmentation, the Humanities Research Lab was able to transform the Restaurant Owner Database into a robust historical resource. The qualitative and contextual research of Eastern European, Southern European, Germanic, and Anglo-Celtic immigrant groups built off of and informed a data-driven approach to historical research. A review of both secondary and primary sources illustrates potential correlations between historical events or attitudes and spatial shifts in the immigrant restaurant industry over time. Thus, a quantitative study and spatial analysis, supplemented by contextual research, reveals interesting insights into immigrant identity and work among New York City restaurant owners in the late nineteenth and early twentieth centuries.

## Methods

Our goal is to take a data driven approach to historical research. As a result, our methodology is largely focused on data analysis and augmentation in order to grow the database and draw accurate conclusions. However, it is our belief that without context, no amount of raw data is enough to facilitate an understanding of a subject. Thus, a more desciptive goal would be to marry contextual and qualitative research with a quantitative, data driven approach to history in order to develop new understandings of people, places, and events. Key aspects of our methodology are defined below and more detailed descriptions are linked in related folders.

**Quantitative**
- Data Gathering
    - [1880 Scraping](https://github.com/saraaahh63/NYCRestaurantData/tree/master/scraping_files_1880)
- Geocoding
    - [Address Cleaning](https://github.com/saraaahh63/NYCRestaurantData/tree/master/address_cleaning)
    - [Geocoding](https://github.com/saraaahh63/NYCRestaurantData/tree/master/geocode)
- Identifying Gender
    - [IPUMS](https://github.com/saraaahh63/NYCRestaurantData/tree/master/ipums)
- Identifying Nationality / Place of Origin
    - [Nationality API](https://github.com/saraaahh63/NYCRestaurantData/tree/master/nationalityAPI_1913)
    - [Ancestry API](https://github.com/saraaahh63/NYCRestaurantData/tree/master/api_ancestry)
    - [Race](https://github.com/saraaahh63/NYCRestaurantData/tree/master/race)
- Mapping & Data Visualization
    - [Mapping](https://github.com/saraaahh63/NYCRestaurantData/tree/master/googlemap)
    - [NYC geojson](https://github.com/saraaahh63/NYCRestaurantData/tree/master/nyc-geojson)
    - [D3 Example](https://github.com/saraaahh63/NYCRestaurantData/tree/master/nyc_d3_example)

**Qualitative**
- Primary Source Research
- Literature Review
- Data Visualization Research

## Focus Groups

**Southern European**
**Eastern European**
**Germanic**
**Anglo-Celtic**

## Visualization

This research project is a data driven study of history, and as such, it was important to consider data visualization. Thus, the question of visualization was raised early in the research process and, in many ways, informed our subsequent research. The dissemination or communication of research became inseparable from its creation. An early part of our research was mapping our restaurant database on top of immigrant populations in order to understand whether ethnic restaurants were serving their own population.

![Image of Anglo-Celtic Mapping](https://github.com/saraaahh63/NYCRestaurantData/blob/master/Screen%20Shot%202020-12-29%20at%2011.11.25%20PM.png)
    
Through this initial mapping we were able to identify trends we were otherwise blind to; and, since we were dealing with an expanding database, we realized that this ability would be invaluable not only to our own research, but also to future research. Thus, we began exploring the idea of animated or interactive maps as both a companion visualization to our research and a method for other researchers to explore the database. In service of this goal, we first conducted a literature review of data visualization trends in the digital humanities and human-computer interaction. Stanford University’s Spatial History Project was important to our understanding of visualization in a historical context.

The Spatial History Project is a database of visualizations produced by the Spatial History Lab at Stanford University. The goal of the Spatial History Project is to experiment with visualization as a tool to develop new arguments about historical processes and understandings of major historical events. Through in depth study of Spatial History Lab visualizations, we developed a method of integrating narrative techniques and visual forms into data presentation. Furthermore, this process allowed us to gain a deeper understanding of visualization as it applies to patterns in time and space.

The main tenet of our data visualization method is storytelling. Data, whilst objective, often has a human dimension and, as a representation of real life, is filled with stories. The job of a data visualizer is thus to make these stories more apparent to the casual observer. The key to this is to take advantage of emotional force while establishing conceptual coherence. The first step in taking advantage of emotional force is to think character development. Every datapoint is essentially a character. As a character, every datapoint has a past, present and future. Furthermore, no character exists in a vacuum and thus data groups should not be treated as separate compartments, but as several characters that interact and form relationships over time.

To expand on the theoretical framework behind our approach to data visualization, we began experimenting with D3. D3 is a JavaScript library designed to work with data to produce web-based visualizations. In D3 we were able to test features like using a slider to navigate through time, dropdown menus to filter by datagroup, and viewport size to create focus. However, these experiments remain in early stages of development. We will continue to expand upon our visualization work and develop in D3.
