# AWS Fraud Detector
A demo and guide of how to use AWS Fraud Detector

## Fraud Detector
https://www.loom.com/share/e869743a3f414b14a07c08c6c5aaad9d

## Notes
Notes on using this (learned the hard way)
- You have to have more than 400 fraudulent cases for it to work
- You can't have storage in different region than your model
- No capitals or spaces in your column names
- EVENT_TIMESTAMP and EVENT_LABEL columns are required 
- Expect AT LEAST 45min of training

The process is as follows
- Create an event type (which will also require you to create entities and add labels)
- Then create a model based upon that event type
- PowerPoint in Repo with examples


## Kaggle Link
https://www.kaggle.com/mlg-ulb/creditcardfraud


