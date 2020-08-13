# COVID19-Analysis-using-SIR-model
I have done an analysis and data modelling of Covid-19 disease cases in India and Italy using a compartmental model named SIR model.
This model comprises of three parameters- Suspicious, Infectious and Recovered. These parameters show the no of people who are suspicious, infected and recovered in particular country or in whole world.

There are a lot of data which is available on internet. Here I have used mostly used dataset from the John Hopkins University's Center for Systems Science and Engineering (JHU CSSE). The links for the datasets are:
* [time_series_covid19_confirmed_global.csv](https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv)
* [time_series_covid19_deaths_global.csv](https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_global.csv)
* [time_series_covid19_recovered_global.csv](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_recovered_global.csv)

## Data Modelling and Predictions
Just because the rise in number of cases is exponential, it does not imply that we can fit the data to an exponential curve and predict the number of cases in the coming days. Compartmental model techniques are normally used to model infectious diseases. Same could be used in the case of  COVID-19 too. The simplest compartmental model is the SIR model. The following excerpt  from this source link describes the model and its basic blocks. 

The model consists of three compartments: S for the number of susceptible, I for the number of infectious, and R for the number of recovered or deceased (or immune) individuals. This model is reasonably predictive for infectious diseases which are transmitted from human to human, and where recovery confers lasting resistance, such as measles, mumps and rubella.

Each member of the population typically progresses from susceptible to infectious to recovered. This can be shown as a flow diagram in which the boxes represent the different compartments and the arrows the transition between compartments, i.e.
![SIR Model](https://github.com/mayank2705/COVID19-Analysis-using-SIR-model/blob/master/SIR_model.png)

Most important graphs of the Data modelling and analysis done are as follows:-
For the world scenario ![](https://github.com/mayank2705/COVID19-Analysis-using-SIR-model/blob/master/newplot%20(1).png)


