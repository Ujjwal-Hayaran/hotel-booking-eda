# Resources

## Used in this project
- Dataset on Kaggle: https://www.kaggle.com/jessemostipak/hotel-booking-demand
- Original paper: Antonio, Almeida & Nunes (2019), *Hotel booking demand datasets*, Data in Brief 22: https://www.sciencedirect.com/science/article/pii/S2352340918315191
- pandas user guide (groupby, missing data): https://pandas.pydata.org/docs/user_guide/
- seaborn tutorial: https://seaborn.pydata.org/tutorial.html
- scikit-learn linear models: https://scikit-learn.org/stable/modules/linear_model.html
- scikit-learn model evaluation (precision, recall): https://scikit-learn.org/stable/modules/model_evaluation.html

## To read next
- *Python for Data Analysis* by Wes McKinney
- *An Introduction to Statistical Learning* (free): https://www.statlearning.com
- *Storytelling with Data* by Cole Nussbaumer Knaflic
- Kaggle Learn (free short courses): https://www.kaggle.com/learn
- Antonio, Almeida & Nunes (2017), *Predicting hotel booking cancellation to decrease uncertainty and increase revenue*, Tourism & Management Studies 13(2)

## Hotel terms I had to look up
- **ADR:** average daily rate, revenue per room-night sold
- **Occupancy:** room-nights sold divided by room-nights available (not possible here, the data has no room capacity)
- **RevPAR:** ADR x occupancy
- **OTA / TA / TO:** online travel agency, travel agent, tour operator
- **GDS:** global distribution system used by travel agents
- **Overbooking:** selling more rooms than exist, expecting cancellations

## Ideas for a next version
- Random forest or gradient boosting with class weights for cancellations
- Train on earlier dates, test on later ones
- Investigate the Non Refund deposit anomaly
- Power BI dashboard of the KPIs
- Redo Q1 to Q20 in SQL
