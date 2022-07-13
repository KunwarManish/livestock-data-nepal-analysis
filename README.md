# **Analysis of Livestock Data of Nepal**

## **1**. **Data Understanding**

The dataset contains data from Nepalese livestock data subdivided by region/district and the commodities they produce. The data is separated into eight different files, as indicated below. Horses-asses, animal milk production, meat production, cotton production, egg production, rabbit population, wool production, and yak-nak-chauri are among the data collected.

## **2**. **Data Merging and Cleaning**

### **2.1 The data sources and merge them into a single data source. Do necessary data cleaning and pre-processing.**

**Performing Necessary Cleaning and Merging**

**Finding Difference between dataframe to merge**

## **3**. **Exploratory Data Analysis**

**HorsesAsses Population Analysis**

![image](https://user-images.githubusercontent.com/31987649/178689387-c63f6d60-cc6a-4439-a300-4c00999794ca.png)

_Figure 1: Separating HorsesAsses Population on the basic of development region from final merge dataset._

![image](https://user-images.githubusercontent.com/31987649/178689492-9850c355-a0d3-4da0-b2b1-af493ca6b8a5.png)

_Figure 2: Bar Plot of HorsesAsses Population in five development region of Nepal._

The bar graph above represents the population of horses in Nepal&#39;s five development regions. The population of horsesasses is larger in the Mid-Western Region (over 35000) and lower in the Center Region (less than 5000), as seen in the bar graph above. In the Eastern and Western Regions, the population of horsesasses ranges from 5000 to 10,000. In the Far-Western Region, there are nearly 5000 horsesasses.

**Milk Production Analysis**

![image](https://user-images.githubusercontent.com/31987649/178689564-838bb117-94b3-4a23-965c-c69157a1a290.png)

_Figure 3: Bar Plot of milk production in different area of central development region._

The following bar graph represents milk production in six areas of Nepal&#39;s Center Development Region: Nuwakot, Chitwan, Kathmandu, Dhading, Bhaktapur, and Kavre. From these six areas, Kavre produces more milk in both cow and buff milk, as well as total milk production, whereas Bhaktapur produces less milk in both cow and milk, as well as total milk production.

**Meat Production Analysis**

![image](https://user-images.githubusercontent.com/31987649/178689734-39ded432-d0d2-437c-928a-f2b86fecc004.png)

_Figure 4: Bar Plot of Meat Production in five development region of Nepal._

The meat production in Nepal&#39;s five development regions is shown in the bar graph above. As shown in the bar graph above, meat production is highest in the Center Region (about 100000) and lowest in the Far-Western Region (less than 50000). Meat production in the Eastern and Western Regions ranges from 60000 to 80,000 tons. There are nearly 60000 meat producers in the Mid-Western Region.

**Wool Production Analysis**

![image](https://user-images.githubusercontent.com/31987649/178689821-75d779ea-7970-424f-88d0-0633a43cb654.png)

_Figure 5: Strip Plot of Wool Production in five development region of Nepal._

The strip plot above illustrates the Wool production in Nepal&#39;s five development areas. Wool production is highest in the Mid-Western Region Center Region (approximately 300000) and lowest in the Eastern Region, Center Region, and Far-Western Region, as illustrated in the strip plot above (around 50000). The Western Region produces roughly 100,000 cotton production.

**Yak Population Analysis**

![image](https://user-images.githubusercontent.com/31987649/178689932-70c100c4-0319-44ba-aa6c-0f0d70d058e8.png)

_Figure 6: Pie Plot of Yak Population in five development region of Nepal._

The pie plot above represents the population of yak in Nepal&#39;s five development regions. The population of yak is larger in the Eastern Region i.e., 33.12% and lower in the Far-Western Region i.e., 1.30% as seen in the pie plot above. In the Mid-Western and Western Regions, the population of yak is 25.81% and 21.545 respectively. In the Center Region, there are 18.14% yak population.

**Cotton Production Analysis**

![image](https://user-images.githubusercontent.com/31987649/178690037-6a141849-1364-45d3-8010-ea902505d452.png)

_Figure 7: Bar Plot of Cotton Production in three district._

The bar plot above represents cotton production in three districts, as only three districts grow cotton according to the data. Dang district has a wide producing area and produces great quantities but low yields. Similarly, the Bardiya district had a small producing area and a small but remarkable yield. And the Banke district offers a wide variety of yields when comparing producing area and output.

**Egg Production Analysis**

![image](https://user-images.githubusercontent.com/31987649/178690104-7f5eeec3-4105-41b3-a78e-59ea6e9c4f09.png)

_Figure 8: Line Plot of Egg Production in five development region of Nepal._

The line plot above shows egg production in Nepal&#39;s five development areas. Egg production is highest in the Center Region (around 700000) and lowest in the Far-Western Region, as seen in the graph above (less than 100000). In the Western and Mid-Western regions, egg production ranges from 100000 to 200000. In the Eastern Region, there are over 200000 egg producers.

**Rabbit Population Analysis**

![image](https://user-images.githubusercontent.com/31987649/178690223-802a252a-43fe-47cc-b940-e9a1a8814652.png)

_Figure 9: Pie Plot of Rabbit Population in five development region of Nepal._

The pie plot above represents the population of rabbit in Nepal&#39;s five development regions. The population of rabbit is larger in the Mid-Western Region i.e., 35.65% and lower in the Far-Western Region i.e., 4.31% as seen in the pie plot above. In the Western and Centre Regions, the population of rabbit is 27.68% and 16.47 respectively. In the Eastern Region, there are 15.91% rabbit population.

**Analysis of Total Milk Production, Total Milk, Total Meat and Sheep Wool Produced.**

![image](https://user-images.githubusercontent.com/31987649/178690342-0fbaedc6-4511-488d-89d5-16a52c899125.png)

_Figure 10: correlation () function being used to compute correlation of columns._

The above screenshot demonstrates the implementation of correlation function in which the correlation of total milk produced, total egg, sheep wool produced, and total meat is presented.

![image](https://user-images.githubusercontent.com/31987649/178690411-4336bdd3-b05e-47b0-82ab-bab511ad572e.png)

_Figure 11: Heatmap production of different items in different district._

The color codes used in the heatmap above show the strength of each variable, namely total milk produced, total egg, sheep wool produced, and total meat. In the above heatmap, the correlation between the variables is strong if the color is dark, but the connection between the variables is weak if the color is light.
