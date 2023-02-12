## [**Project 1:** Forecasting Malaysia's solid waste generation using a Bayesian-optimized artificial neural network with ensemble learning for improved generalization](https://github.com/nicholashoy/forecast-waste-ANN)

[_Show Publication_](https://www.sciencedirect.com/science/article/abs/pii/S0098135422002812)

- Performed data collection, cleaning, gap analysis, and imputation on Malaysia's solid waste and socioeconomic data.
- Identified strongly correlated socioeconomic indicators using Pearson correlation analysis for eight waste physical composition to be used as predictors[^1].

![](/images/Picture1.jpg "Correlogram")
- Developed a Bayesian-optimized artificial neural network model to concurrently optimize the model's learning rate and number of neurons to achieve minimum prediction error using MATLAB R2021[^2].

![](/images/Picture2.png "Objective function model")
- Forecasted the solid waste generation based on the ensemble learning approach which shows that the developed model (labelled as (a) in the figure) reduces overfitting and forecast uncertainty compared to the default model (labelled as (b) in the figure)[^3].

![](/images/Picture3.png "Food waste forecast")

[^1]: Correlogram ranks the correlation strength from a–d in descending order. f: food; g: garden; pa: paper; pl: plastic; gl: glass; t: textile; m: metal; oth: others; ovr: overall MSW; Pop: population; Pop%: population growth rate; Upop%: urban population percentage; Rpop%: rural population percentage; Life: life expectancy; Fert%: fertility rate; Empy: number of persons employed; Workhr: average work hours; HCI: human capital index; Tert%: tertiary education enrolment rate; CO2: CO<sub>2</sub> emissions; CO2Tp: CO<sub>2</sub> emissions from the transport sector; Engy: energy use; Elec: electricity consumption; GNI: gross national income; GNE: gross national expenditure; GS: gross savings; Comp: number of listed domestic companies; Income: national income per capita.
[^2]: The observed blue points are based on the stochastic predictions of the surrogate model, while the blue asterisk symbol represents the model minimum feasible.
[^3]: Comparison of the Bayesian-optimized artificial neural network model (labelled as (a) in the figure) and the default model (labelled as (b) in the figure) at ensembles of 10, 50, 100, and 250 members demonstrates the consistency when forecasting using the Bayesian-optimized artificial neural network model.

----------------------------------------------------------------------------------------------

## [**Project 2:** Assessing the global solid waste system's potential in achieving the Paris Agreement 1.5°C and 2°C goals](https://github.com/nicholashoy/forecast-emissions-ANN)

[_Manuscript Currently Under Review_[^4]]

- Performed data collection, cleaning, gap analysis, and imputation on the top 43 solid waste generating countries, accounting around 86% of the global solid waste generation based on the [World Bank's data in 2016](https://openknowledge.worldbank.org/handle/10986/30317).
- Developed a panel data regression model to fill data gaps for country-specific solid waste generation using EViews 2022[^5].

![](/images/Picture4.jpg "Panel data regression")
- Validated the panel data regression model's assumption of homoskedasticity and endogeneity using the heteroskedasticity test and Hausman's test, respectively, before testing for its prediction accuracy.

![](/images/Picture5.jpg "Actual vs fitted")
- Quantified the disaggregated greenhouse gas emissions (i.e., CO<sub>2</sub>, CH<sub>4</sub>, and N<sub>2</sub>O) from the global solid waste system based on each country's waste treatment practices (e.g., incineration, recycling, and landfill) based on the [2006 Intergovernmental Panel on Climate Change (IPCC) Guidelines for National Greenhouse Gases Inventories](https://www.ipcc-nggip.iges.or.jp/public/2006gl/) with consideration of the [2019 Refinement](https://www.ipcc-nggip.iges.or.jp/public/2019rf/index.html).
- Illustrated the global greenhouse gas emissions distribution using a map chart in Tableau and their waste treatment facilities share at different income levels[^6].

![](/images/Picture6.jpg "Global greenhouse gas emissions and their waste treatment facilities")
- Forecasted the disaggregated greenhouse gas emissions of each countries based on the ensemble learning approach using the Bayesian-optimized artificial neural network model.
- Assessed the global solid waste system's global warming impact in achieving the Paris Agreement goals based on the [IPCC 6<sup>th</sup> Assessment Report](https://www.ipcc.ch/assessment-report/ar6/)'s remaining carbon budget.
- Analyzed the extent of mitigation required for the global solid waste system to stay within the Paris Agreement temperature limits within 2050.

----------------------------------------------------------------------------------------------

[^4]: The manuscript is currently undergoing review process. The relevant data and code will be uploaded once the submission process is completed.
[^5]: MSW stands for municipal solid waste, which is defined by the World Bank as solid waste consisting of everyday items resulting from, or incidental to, residential, commercial, and institutional activities.
[^6]: (A) shows 2020’s global greenhouse gas emissions from the solid waste system, while (B) shows 2020’s share of solid waste disposal and treatment facilities. HIC: high income countries; UMIC: upper-middle income countries; LMIC: lower-middle income countries; LIC: low income countries.
