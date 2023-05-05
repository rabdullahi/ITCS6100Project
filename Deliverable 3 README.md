**Deliverable 3**

[Link to Analysis](https://github.com/rabdullahi/ITCS6100Project/blob/main/Deliverable%203.ipynb)

[Link to Powerpoint](https://docs.google.com/presentation/d/1z_zjIIS54rWIcV58Hy7Y0hJTb5wCd84C7iQkLr4t6Ec/edit?usp=sharing)

[Link to Document](https://docs.google.com/document/d/1fK5alSp12kTX8QFMmFE-K8XgFrRS02mOsIQsm31v9ko/edit?usp=sharing)


**Future works, Comments:**
1. What was unique about the data? Did you have to deal with imbalance? What data cleaning did you do? Outlier treatment? Imputation? 

The data is unique, we used “nunique” and we got back various distinct elements. We found out we had 7266 rows of outliers so we removed them. We didn’t have to do imputation as we didn’t have any missing values. 

2. Did you create any new additional features / variables? 

We created a new column “DayType” which identifies which days are weekdays and weekends. 

3. What was the process you used for evaluation?  What was the best result?

For the evaluation, we  first did a parameter grid to see what the most optimal set of parameters was. The SARIAX model showed the best results. The model residuals have normal distribution. 

4. What were the problems you faced? How did you solve them?

One of the problems we faced was calculating the weekdays and weekends time series. We solved it by separating the day type into weekdays and weekends, then we used the new dataframe “energy_out” for the rest of the analysis. Another problem we faced was with the predictive analytics aspect, we realized predicted each hour of a month isn’t practical so we looked at the days instead and we can see the trends more clearly. 

5. What future work would you like to do? 

Future work could focus on analyzing the integration of renewable energy sources into the electricity grid. One potential use of the electricity consumption and production dataset is to examine patterns and trends in electricity demand and production, allowing researchers and practitioners to identify the challenges and opportunities associated with integrating renewable energy sources. 
We can investigate Romania's possibilities for renewable energy sources. This can entail assessing the present output of solar and wind energy and identifying areas where these sources could be increased. Developing new renewable energy sources like geothermal or tidal energy may also be investigated for their economic potential. 

6. Instructions for individuals that may want to use your work?

If someone wishes to apply our findings, they can use the same dataset and the procedures described in our approach. They should, however, keep in mind the particular context of our study as they modify the approach and analysis to fit the needs of their own research topic and objectives. Before transferring our insights to their own conditions, individuals should also carefully review and validate them. To make sure their models are accurate and trustworthy, they need also validate their findings and assess their performance. Finally, we suggest them to follow recent advancements in the field of energy production and consumption and to apply them to their upcoming work.


