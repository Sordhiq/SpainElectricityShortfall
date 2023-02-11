# SpainElectricityShortfall

There is evidence that the reliance on purely non-renewable fossil-fuel energy sources is unsustainable. Transitioning into renewable energy sources is simply inevitable.

By analyzing the effect of different weather features with time on energy supplied, this project is aimed helping the Spanish government predict future energy deficit from renewable resources and leverage data-driven solutions to model shortfall between the energy produced by fossil fuels and proffer sustainable renewable alternatives so as to accommodate for deficits in the power grid.

To achieve this aim, data around climatic variables such as rainfall, temperaturs, wind speed, snow, relative humidity and pressure were collected across 5 Spanish cities of Bilbao, Seville, Madrid, Valencia and Barcelona. The project began with importing all necessary libraries as well as importing the train and test datasets. Next step was examining the data with some descriptive statistics. Data analysis was followedup with data visualization where some important trends and insights were derived from the data.

Afterwards, feature engineering was conducted, getting the data ready for modelling. Behind proper data engineering and data type conversions, the linear regression models were instantiated and fitted against the train set. Root Mean Squared Error (RMSE) was utilized in measuring the rate of error contained in the model. Similarly, ensemble techniques were introduced to improve the efficiency of the model and at yhe end of the day, the Linear Regression was most efficient among all regression models while the Boosting method was the overall efficient ensemble method. Hence, the shortfall in electricity prediction was based on the Boosting model.

At the end of the project, it was discovered among other observations that
