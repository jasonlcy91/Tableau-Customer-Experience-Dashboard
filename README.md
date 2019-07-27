# Customer Experience Heatmap Dashboard in Tableau

I was tasked to design a composite score for a telco to represent their high value customers (HVC) experience in using data, based on multitude aspect of their experience such as download speed, streaming delay, etc. I created this dashboard to show the customer experience geographical distribution and a couple of tools to help them in their analysis and to drill down to specific cells and customer segment. 

For example, one can find the cells with more than 75% of users having Streaming Score of less than 0.4 (bad) and which total users (of the cell) must be at least 15, so that effort is not wasted trying to fix a cell just to benefit very few people.

Download the Tableau .twb file and the sample data or view [my Tableau Public here](https://public.tableau.com/profile/jason.lee.91#!/vizhome/TelcoCustomerExperienceHeatmapv3/DASHBOARD)

> *Note: To present this dashboard publicly, I have sampled only 5% of the original data, replaced sensitive information and removed few tools from the original dashboard built for the client.*

> I also think this dashboard is a practice for Tableau learners who want to go beyond the basic for more advanced dashboarding and analysis for practical corporate use case (You won't want to always do Pokemon dashboard tutorial. Just joking :D ). Contains
>- Context filters
>- Table and Level of Detail calculations
>- Calculated fields
>- Parameters and measure switches
>- Dashboard actions
>- Donut charts

![Overview](https://github.com/jasonlcy91/Tableau-Customer-Experience-Dashboard/blob/master/telcohvcexperience01.png)
![Advanced filter](https://github.com/jasonlcy91/Tableau-Customer-Experience-Dashboard/blob/master/telcohvcexperience02.png)
