# Use-of-XGBooster-and-SHAP
A housing data is taken from internet and a model is built using XGBooster and is visualized with
the help of SHAP

the correlations are shown with the help of a seaborn heat map

parameter optimization is performed 

graph for feature importance is plotted 

shap summary graph is plotted 

shap dependence graph is plotted 

shap waterfall graph is plotted 

the overall r2_score(y_test,gridcv_xgb.predict(X_test) was  0.998

the RMSE (y_test,yhat) was 27.486

the list of feature was :'id', 'price', 'bedrooms', 'bathrooams', 'sqft_living', 'sqft_lot', 'floors', 'waterfront', 'view', 'condition', 'grade', 'sqft_above', 'sqft_bbasement', 'yr_built', 'yr_renovated', 'zipcode', 'lat', 'long', 'sqft_living15', 'sqft_lot15'
 
