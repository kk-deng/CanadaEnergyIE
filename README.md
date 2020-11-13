# A study on North America Energy Production vs. Currency Strength

## Background

Canada is the *sixth largest energy producer and the fourth largest net exporter in the world*. Canada’s energy sector accounts for over 10% of its nominal GDP, and it is a large contribution to the Canada government’s revenue as well. Moreover, every year government spent more than 1 billion on the energy research, development, and deployment. Due to the fact that a large amount of the Canada’s total foreign exchange earnings are gained through the crude oil sales, the exchange rate of Canada is strongly correlated to the price of oil. 

Therefore, this project **analyzes the correlation between energy production and the economics of U.S and Canada, in terms of oil exports, GDP and dollar index or exchange rate**. Despite the large oil reserve in Canada, the world is shifting towards using clean and renewable energy.

Thus, the renewable energy production trend in the past 15 years is analyzed as well to see how this change in energy industry will affect Canadian economy and dollar strength for the future.

## Purpose

* This project focuses on examining how oil production and currency are connected. The scope of this project focuses on Canada and U.S only. 

* In this project, multiple datasets from Stats Canada, US EIA, Exchange Rate Open API are extracted, transformed and analyzed to see the total crude production and the GDP contribution of oil export data of each country and the correlation with their currency values. 

* The results from the data can lead to further understandings of how currency values impacted in the near future, when the world is shifting towards cleaner, lower cost, and sustainable energy sources, and thus less relying on crude production. 

## Main Findings

### Q1. Correlation between US Oil Production and the Economy

- Linear growth of US Gross GDP over the past 15 years (1.5x since 2005), as shown in Figure 1.
- US Dollar Index follows a cyclical trend and ends up increased by 1.05x compared to the value in 2005
- Correlation between US Gross UDP and US Dollar Index is 0.37. This weak correlation value is expected since the Dollar Index is affected by many other factors including inflations, recessions, political risks, besides the economic activities.
- US Crude Oil Production and Exports also had a linear growth during the past 15 years. It has a strong correlation with US GDP. However, since Oil Production only accounts for ~1% of US GDP, this strong correlation is not adequate to conclude a correlation between Oil Production and the US Economy in term of GDP.
- Weak correlations between Crude Production/ Export and GDP and the US Dollars Index, as shown in Table 1.

*Table 1: Correlations between US Crude Production, GDP, and US Dollars Index*
<img src="https://i.ibb.co/0FHmHsP/image.png" border="0">

<img src="https://github.com/kk-deng/CanadaEnergyIE/blob/main/Plots/Question%201%20-%20US%20Energy%20Production%20vs.%20Dollars%20(1C).png?raw=true" border="0">

*Figure 1: Correlation between US Oil Production and the Economy*

---
### Q2. Correlation between CA Oil Production and the Economy

- Canada’s crude oil export has a linear growth during the past 15 years (2.3x since 2005), as shown in Figure 2.
- Inversed correlation between crude export and CAD/USD Exchange rate, as shown in table 2.

*Table 2: Correlation between CA Crude Export, GDP from O&G, and CAD/USD Exchange Rate*
<img src="https://i.ibb.co/548cpQR/image.png" border="0">

<img src="https://github.com/kk-deng/CanadaEnergyIE/blob/main/Plots/Question%202%20&%204%20-%20CAD%20Exchange%20Rate%20vs.%20Oil%20Export%20and%20GDP%20contribution%20of%20Oil%20Extraction.png?raw=true" border="0">

*Figure 2: Correlation between CA Oil Production and the Economy*

---

### Q3. US renewable energy production vs. the dollar’s strength

- US’s electricity production from renewable sources has a stead growth over the past 15 years, while electricity from fuel sources has been decreasing. The liner regression relationships are shown in table 3 and Figure 3.

*Table 3: Linear regression relationships for Electricity production by source*
<img src="https://i.ibb.co/JcgPYC8/image.png" border="0">

<img src="https://github.com/kk-deng/CanadaEnergyIE/blob/main/Plots/Question%205%20-%20Time%20vs.%20Oil%20and%20Renewable%20(with%20Regression).png?raw=true" border="0">

*Figure 3: US Electricity production by source*

- Inconclusive correlation between renewable production with US Dollars Index, as shown in Figure 4

<img src="https://github.com/kk-deng/CanadaEnergyIE/blob/main/Plots/Question%206%20-%20Sources%20vs.%20USD%20Index.png?raw=true" border="0">

*Figure 4: US electricity production vs. US Dollars Index*

---

### Q4. CA renewable energy production vs. the dollar’s strength

- Overall renewable energy production is growing, with the majority is from Hydraulic turbine (90%) , followed by wind power turbine, as shown in Figure 5.

<img src="https://github.com/kk-deng/CanadaEnergyIE/blob/main/Plots/Question%205%20-%20Time%20vs.%20Types%20of%20Renewable%20Sources%20for%20Canada.png?raw=true" border="0">

*Figure 5: CA electricity production from renewable sources*

- Canada’s electricity production is mainly from renewable energy (mainly due to hydraulic energy)
- Overall, Production from renewable sources increases as the Non-Renewable sources decreases, as shown in Figure 6, and the linear regression is shown in table 4.

<img src="https://github.com/kk-deng/CanadaEnergyIE/blob/main/Plots/Question%205%20-%20Time%20vs.%20Oil%20and%20Renewable%20(with%20Regression)%20for%20Canada.png?raw=true" border="0">

*Figure 6: CA Electricity production trend*

*Table 4: Linear regression relationships for Production from renewable sources & Non-Renewable sources decreases*
<img src="https://i.ibb.co/S586s8q/image.png" border="0">

- Weak correlation between electricity production from renewable energy sources and the CAD/USD Exchange Rate, as shown in Figure 7.

<img src="https://github.com/kk-deng/CanadaEnergyIE/blob/main/Plots/Question%206%20-%20Sources%20vs.%20CAD%20Index.png?raw=true" border="0">

*Figure 7: Electricity production from renewable sources vs. CAD/USD Exchange Rate*


## Assumptions made for the analysis

* Analysis used nominal GDP and not inflation-adjusted, so it does not represent the true growth
* First date of the month was representative of the entire month
* Assume U.S dollar is a fairly stable currency, and we use CAD/USD index to represent the currency change in Canadian dollars.
* US Dollars Index only factor the exchange rates of six major currencies: EUR< JPY, CAD, GBP, SEK, CHF, with EUR weighted about 58%, the rest of currencies weighted between 3-13% each.

## Next steps

*	Derive Real GDP from nominal GDP by considering the inflation rate over the years, and re-examine the correlations
*	Gain an understanding of other factors affecting dollars strength 
*	Investigation into any new renewable energy initiatives (timing, production impact etc.)
*	Energy production is not limited to electricity 
*	Should explore other uses of energy (e.g. Heating) 

## Credits
Thanks to teammates: **Kelvin Deng, Thao Hoang, May Ang, Yijing Su**
