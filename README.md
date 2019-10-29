# Data Visualization Project

## Data

The [data](https://gist.github.com/yinhao0424/9f1730ca91ab6a472fc212761267fa39) I visualized for my project is immigration programs from The Office of Foreign Labor Certification (OFLC) including the H1-B visa from 2011 - 2016.

###### Columns: 
 *  CASE_STATUS
 *  EMPLOYER_NAME
 *  SOC_NAME
 *  JOB_TITLE
 *  FULL_TIME_POSITION
 *  PREVAILING_WAG
 *  YEAR
 *  WORKSITE
 *  lon
 *  lat

## Visualizations

I’ve created visualization of this data. 
- React & D3
 1. The first one is a stacked bar chart. It shows the changes for the total number of petition, the different case status. When we put mouse on each bar, it will show us the number of petition of that status in that year. Also, when we hover on a particular color legend. The responding bars will be highlighted and others will fade. 
[![image](https://user-images.githubusercontent.com/44931709/67796926-3c2a1380-fa57-11e9-99e8-173729570e54.png)](https://beta.vizhub.com/yinhao0424/6f8d7fc887384153a52976047a8491d3)

 2. The second one is a bar chart showing the top 20 states applying for h1b visa. 
 [![image](https://user-images.githubusercontent.com/44931709/67796953-49470280-fa57-11e9-988d-c5f202c26ef1.png)](https://beta.vizhub.com/yinhao0424/51ebbe7c02ff4ec89f6adfce406c8742)
 
 3. The third one is an interactive map. When we hover on the color legend, the responding points will be highlighted and others will fade. The dropdown will filter data by year. If we choose a particular year, this map will only show the points in that year. In the meantime, we can still hover on color legent to check out the distribution of different status.
 [![image](https://user-images.githubusercontent.com/44931709/67796883-2b799d80-fa57-11e9-9f8f-74eef330da69.png)](https://beta.vizhub.com/yinhao0424/0f89e14439cd400ca1d9b6d18d88919d)
 
 4. The fourth one shows the number of different case status for each year with D3&React.
[![image](https://user-images.githubusercontent.com/44931709/66445343-784bf480-ea14-11e9-9351-c867695cea39.png)](https://beta.vizhub.com/yinhao0424/b3520ce6b373400fa819398654be5b9c)

- Vega lite API
 1. The first one shows the changes for the total number of petition, the different case status and different job type. 
 [![image](https://user-images.githubusercontent.com/44931709/65516192-8f380600-deae-11e9-934e-d01ca1466616.png)](https://beta.vizhub.com/yinhao0424/75b00344e86f4c8b9253c9dad751387a)

 2. The second one is stacked bar chart showing the amount of petitions in different states as well as its case status.
 [![image](https://user-images.githubusercontent.com/44931709/67796938-42b88b00-fa57-11e9-8d2c-15b1aded4224.png)](https://beta.vizhub.com/yinhao0424/dc8592815d704aa4a69a60e665df0ea3)
 
 3. The third one shows the pattern of petition in a map.
[![image](https://user-images.githubusercontent.com/44931709/66445807-0ecce580-ea16-11e9-933f-3cd10c193067.png)](https://beta.vizhub.com/yinhao0424/5aafc3f42b424fddb2573a7fc377a855)


## Questions & Tasks

The following tasks and questions drive the visualization and interaction decisions for this project:

 * How does the number of petition vary over time? 
 * Is there any correlation between petition status and state?
 * Are there interesting spatial patterns in case status?
 
## Sketches
### Part 1
![image](https://user-images.githubusercontent.com/44931709/65524721-4424ef80-debc-11e9-9263-948eb1c60a3c.png)
 * The first sketch is to build a map shows the distribution of status. 
 * The second sketch is to show each attributes change along with time. For example, How does the number of petition vary over time?
 * The third sketch is to show the correlation between different attributes. Such as, the relationship between wages and approved rate.
 ### Part 2
 ![image](https://user-images.githubusercontent.com/44931709/66012228-568ec280-e494-11e9-9e99-e99645fe5843.png)
 * This sketch shows the extended ideas. Linked the points in the map with a bar chart to show the number of different status in detail by adding zoom/cut/brush functions. Furthermore, I'd like to add a menu bar serving as a filter to choose different years. 
 
 ## Futurn work
 * linked map with a bar chart to show the number of different status in detail by adding zoom/cut/brush functions.



