GCP Cloud Audit Logs Security Analysis

Purpose:  to capture, store, and analyze GCP audit logs using cloud logging, BigQuery, and SQL queries to analyze data that is relevant to cloud security. 

Step 1: Make sure APIs are enabled
  - Cloud Logging
  - BigQuery API



Step 2: Creating the dataset (audit_logs) so we can see the logs that will be exported later on.


Step 3: Log Router to complete the process of exporting to BigQuery
  - Went to Google Cloud Observability Logging
  - Selected Log Router and created the log routing sink
  - This provided the destination for the data to arrive at (BigQuery)

