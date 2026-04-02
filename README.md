# cybersec_ML
Trying to connect ML with cybersec 
# Log Anomaly Detection using Machine Learning

## Overview

This project explores anomaly detection in system logs using basic machine learning techniques. The goal is to simulate how unusual system behavior can be identified from structured log data.

## Approach

* Processed structured system logs (BGL dataset)
* Applied time-window based aggregation to capture behavioral patterns
* Extracted features such as log volume, severity levels, and event diversity
* Implemented:

  * Supervised model (Random Forest)
  * Unsupervised model (Isolation Forest)

## Output

The model identifies time windows with abnormal activity, such as spikes in fatal errors or unusual system patterns.

## Notes

This is a beginner-level project aimed at understanding log-based anomaly detection. The focus is on building a clear pipeline rather than optimizing performance.

## Future Scope

* NLP-based analysis of log messages
* Real-time anomaly detection
* Visualization/dashboard integration

## Author

Ayati Dubey
