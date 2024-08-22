<h1 style="font-size:36px;"> <div align="center"> <b> Crime Rates in Maryland </b> </div> </h1>

<h1 style="font-size:24px;"> <b> 1. Project Description & Business Problem </b> </h1>
The Maryland Department of Public Safety needs to understand crime trends over the past decades to inform their strategic planning. They aim to reduce crime rates by 10% in the next five years. To achieve this, they need a detailed analysis of the historical data, identification of hotspots, understanding of seasonal patterns, and insights into the effectiveness of past interventions.

<h1 style="font-size:24px;"> <b> 2. Dataset </b> </h1>
The data (MD_Crime_Data.csv) on Maryland crime rates is shared via an .csv file. The dataset contains 1105 rows and 39 columns. The original dataset was provided by Data In Motion through their weekly Data Analyst Challenge. 

<h1 style="font-size:24px;"> <b> 3. Software used </b> </h1>

- Python == 3.10.12
  - numpy == 1.25.2
  - pandas == 2.0.3
  - matplotlib == 3.7.1
  - seaborn == 0.13.1
  - geopandas == 0.13.2
  - scipy == 1.11.4
  - sckit-posthocs == 0.9.0
  - ipywidgets == 7.7.1 

<h1 style="font-size:24px;"> <b> 4. Key Findings </b> </h1>

- Maryland crime rates have been steadily declining since the mid-1990s. <br>
- Larceny theft has consistenly been the most frequently occurring crime in Maryland. <br>
- Baltimore City consistently had the highest crime rates, while Carroll and Kent Counties had the lowest rates during the 2000-2020 period. Crime rates in Baltimore City and Worcester County consistently exceed Maryland state averages, while Kent, Garrett, and Carroll Counties consistently fall below Maryland state crime rate averages. <br>
- Overall, Maryland is characterized by a positive, moderate relationship between population size and crime rate; however, this pattern varies widely when jurisdictions are considered individually. <br>
- Murder rates, followed by rape, have experienced the greatest volatility over the years, likely due to the relatively low number of these types of crimes occurring each year. During the period from 1975 to 2020, Baltimore County, Kent County, and Wicomico County saw the greatest decline in violent crime rates, while Wicomico County, Talbot County, and Caroline County experienced the most considerable reduction in property crime rates. <br>
- Baltimore City, Baltimore County, Worcester County, Dorchester County, Wicomico County, and Allegany County recorded the highest overall crime rates from 2016 to 2020. In Baltimore City and Baltimore County, these rates were primarily driven by the prevalence of violent crimes. In Worcester and Allegany Counties, the high overall crime rates can largely be attributed to frequent property crimes. The elevated overall crime rates in Dorchester and Wicomico Counties are likely influenced by both property and violent crimes occurring at rates higher than those seen in other counties. Policies should propose solutions that target violent vs. non-violent crimes in the respective counties. <br>

<h1 style="font-size:24px;"> <b> 4. Recommendations </b> </h1>

- <b>Targeted Approach to Reduce Crime:</b> In Baltimore City and Baltimore County, the highest overall crime rates are driven primarily by violent crimes. To address this, increased law enforcement presence and enhanced community policing efforts are recommended. Additionally, implementing violence prevention programs, such as conflict resolution training and youth engagement initiatives, can help prevent violent crimes from occurring. Strategies should be modeled after successful interventions in Kent and Wicomico Counties, which have seen the greatest reductions in violent crime rates in Maryland over the last 45 years. High crime rates in Worcester and Allegany Counties are largely due to frequent property crimes. To reduce property crime rates, focus on theft prevention initiatives, improving surveillance, and community education on property crime prevention measures. Additional strategies should be modeled after successful resolutions in Talbot, Caroline, and Wicomico Counties, which have seen the greatest reductions in property crime rates in Maryland over the last 45 years. <br>

- <b>Pinpoint Factors Aggravating Crime Rates:</b> Since larger population size seems to play a role in crime rate prevalence, larger jurisdictions with higher crime rates should implement targeted interventions, while smaller areas with lower crime rates can focus on maintaining their status through continued community engagement and preventive measures. Additional factors that could affect crime rates, such as poverty levels, unemployment rates, access to education, substance abuse rates, and availability of social services, should be evaluated to further refine crime prevention strategies. <br>

- <b>Develop Task Force to Address Crime Rate Volatility:</b> While rape and murder are the least frequently occurring crimes, these crimes have seen the greatest fluctuations in the past 45 years. To stabilize these crime rates, establish specialized units charged with handling associated cases. Enhance training for officers in handling sensitive cases and provide additional resources for victim support services. <br>

- <b>Community Education Campaigns:</b> Launch public awareness campaigns in high-crime areas, educating residents on crime prevention techniques and encouraging the reporting of crimes. Provide information on support services available to crime victims and engage community leaders in promoting safety initiatives. Highlight the benefits of increased community policing to increase vigilance in high-crime areas and aid with a prompt police response. <br>


<h1 style="font-size:24px;"> <b> 5. Skills Demonstrated </b> </h1>

- Python: Exploratory Data Analysis & Hypothesis Testing
  - basic python: functional programming, for loops
  - pandas: shape, nununique, iloc, isnull, describe, mean, append, sort_values, idxmax, groupby, concat, dropna, join, astype
  - matplotlib & seaborn: line chart, area chart, regression plot, heatmap
  - geopandas: choropleth map
  - scipy: shapiro, spearmanr
  - scikit_posthocs: dunn
  - ipywidgets: interactive choropleth slider
  
