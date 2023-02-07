## [**Project 1**: Forecasting Malaysia's solid waste generation using a Bayesian-optimized artificial neural network with ensemble learning for improved generalization](https://github.com/nicholashoy/forecast-waste-ANN)

[_Show Publication_](https://www.sciencedirect.com/science/article/abs/pii/S0098135422002812)

- Identified strongly correlated socioeconomic indicators using Pearson correlation analysis for eight waste physical composition to be used as predictors[^1].

![](/images/Picture1.jpg "Correlogram")
- Developed a Bayesian-optimized artificial neural network to concurrently optimize the model's learning rate and number of neurons to achieve minimum prediction error[^2].

![](/images/Picture2.png "Objective function model")
- Forecasted the solid waste generation based on the ensemble learning approach which shows that the developed model reduces overfitting and forecast uncertainty compared to the default model[^3].

![](/images/Picture3.png "Food waste forecast")

[^1]: Correlogram ranks the correlation strength from a–d in descending order. f: food; g: garden; pa: paper; pl: plastic; gl: glass; t: textile; m: metal; oth: others; ovr: overall MSW; Pop: population; Pop%: population growth rate; Upop%: urban population percentage; Rpop%: rural population percentage; Life: life expectancy; Fert%: fertility rate; Empy: number of persons employed; Workhr: average work hours; HCI: human capital index; Tert%: tertiary education enrolment rate; CO2: CO<sub>2</sub> emissions; CO2Tp: CO<sub>2</sub> emissions from the transport sector; Engy: energy use; Elec: electricity consumption; GNI: gross national income; GNE: gross national expenditure; GS: gross savings; Comp: number of listed domestic companies; Income: national income per capita.
[^2]: The observed blue points are based on the stochastic predictions of the surrogate model, while the blue asterisk symbol represents the model minimum feasible.
[^3]: Comparison of the Bayesian-optimized artificial neural network model and the default model at ensembles of 10, 50, 100, and 250 members.

## **Project 2**: Loading
