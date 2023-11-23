# Indepth analysis of EV user's charging behaviour in Leeds, UK  

In this project, we aim to give an indepth analysis of how are EV users charging their EV.    
This can then give us some insights on what are the impacts to the power grid, and how to use technologies like smart charging to mitigate these issues. 

The data used in this project is obtained from [Leeds City Council](https://www.data.gov.uk/dataset/5bb5c097-0e2f-42a3-8aee-1c0189a39082/electric-vehicle-chargepoints-operated-by-leeds-city-council).

The project folder is organised in the following structure:
~~~
.                                                                                                                       
├── artifacts                                                                                                             
│   ├── best_naive_xgb2.joblib                                                                                                
│   ├── best_naive_xgb.joblib                                                            
│   ├── final_pca_xgb.joblib                                                                                            
│   └── stratified_xgb.joblib                                                                                           
├── code                                                                                                                
│   ├── data_preprocessing_pt1.ipynb                                                                                
│   ├── data_preprocessing_pt2_n_user_clustering.ipynb                                                                  
│   ├── electricty_consumption_anna_n_pred.ipynb                                                                        
│   ├── stay_duration_ana_and_pred.ipynb                                                                                
│   └── user_growth_ana.ipynb                                                                                                                                                                                       
├── pre_ana_data                                                                                                        
│   ├── updated_combined_ev_charging_data.csv                                                                           
│   ├── Updated_DM_2014 EVCP use Q2.csv                                                                                 
│   ├── Updated_DM_2014 EVCP use Q3 and Q4.csv                                                                          
│   ├── Updated_DM_2015 EVCP use Q1 and Q2.csv                                                                          
│   ├── Updated_DM_2015 EVCP use Q3 and Q4.csv                                                                          
│   ├── Updated_DM_2016 EVCP use Q1 and Q2.csv                                                                          
│   ├── Updated_DM_2016 EVCP use Q3 and Q4.csv                                                                          
│   ├── Updated_DM_2017 EVCP use Q1 and Q2.csv                                                                          
│   ├── Updated_DM_2017 EVCP use Q3 and Q4.csv                                                                          
│   ├── Updated_DM_2018 EVCP use Q1 and Q2.csv                                                                          
│   ├── Updated_DM_2018 EVCP use Q3 and Q4.csv                                                                          
│   ├── Updated_DM_2019 EVCP use Q1 and Q2.csv                                                                          
│   ├── Updated_DM_2019 EVCP use Q3 and Q4.csv                                                                          
│   ├── Updated_DM_2020 EVCP use Q1 and Q2.csv                                                                          
│   ├── Updated_DM_2020 EVCP use Q3.csv                                                                                 
│   └── Updated_DM_2021 EVCP use Q1.csv                                                                                 
├── ppt_slides.ppt
└── README.md
~~~
