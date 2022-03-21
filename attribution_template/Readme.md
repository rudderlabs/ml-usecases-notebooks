[From First-Touch to Multi-Touch Attribution With RudderStack, Dbt, and SageMaker](https://www.rudderstack.com/blog/from-first-touch-to-multi-touch-attribution-with-rudderstack-dbt-and-sagemaker/)


In this repo, a cleaned data of users touches is taken as input and various attribution models are run on it. 
* This [git repo](https://github.com/rudderlabs/dbt-attribution-template) is used to prepare the input user touches data from event stream and ETL datasets that are available in a warehouse. 
* This data should be made available in an s3 bucket using RudderStack Reverse ETL. 
* Once the data is in an s3, the notebook `rudder_mta_model_template_simplified.ipynb` can be used to generate the attribution scores for various touches
* The notebook has a readme at the start. It explains how to run the notebook. It can be run in any standard python environment. 

