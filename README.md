# Caterpillar-Tube-Pricing-Prediction
Data Source-https://www.kaggle.com/c/caterpillar-tube-pricing

train_set and test_set contain information on price quotes from suppliers. Prices can be quoted in 2 ways: bracket and non-bracket pricing. Bracket pricing has multiple levels of purchase based on quantity (in other words, the cost is given assuming a purchase of quantity tubes). Non-bracket pricing has a minimum order amount (min_order) for which the price would apply. Each quote is issued with an annual_usage, an estimate of how many tube assemblies will be purchased in a given year;
tube contains information on physical parameters of tube assemblies;
 
bill_of_materials contains the list of components, and their quantities, used on each tube assembly;
specs contains the list of unique specifications for the tube assembly;
tube_end_form contains list of end types which are physically formed utilizing only the wall of the tube;
components contains the list of all of the components used;
type... contain the names for each feature;
comp... contains information on physical parameters of components by their type;
