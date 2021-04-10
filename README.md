# Physician-Drug-Adoption-Prediction
Predict whether a drug would be adopted by the Physicians based on their historic record in next quater.


### Objective
   Predict whether the a physician can prescribe the drug to his/her patients based on hsitoric data:
   
### The dataset consists of the following fields:
##### DataSet 1 
          1. physician_id
          2. urban_population_perc_in_physician_locality
          3. percent_population_with_health_insurance_in_last10q
          4. physician_gender
          5. physician_tenure
          6. physician_age
          7. physician_speciality
###### DataSet 2 
          1. physician_id	year_quarter
          2. brand_prescribed
          3. total_representative_visits
          4. total_sample_dropped
          5. saving_cards_dropped
          6. vouchers_dropped
          7. total_seminar_as_attendee
          8. total_seminar_as_speaker
          9. physician_hospital_affiliation
          10. total_patient_with_medicaid_insurance_plan
          11. brand_web_impressions
          12. brand_ehr_impressions
          13. brand_enews_impressions
          14. brand_mobile_impressions
          15. brand_organic_web_visits
          16. brand_paidsearch_visits
          17. total_competitor_prescription
          18. new_prescriptions	physician_segment
      
#### Machine Learning Steps followed to predictthe Loan status:
          1. Load the Dataset 
          2. Data Cleaning to fill missing values and remove unwanted values.
          3. Preprocesing the data of Categorical variables.
          4. Apply Standard Scaler to normalize the data
          5. Split Train and Test dataset
          6. Apply KNN model on the dataset
               - accuracy score - 0.80101
          7. Performance on Test Data
                  - accuracy score - 0.73
