## What I did
Generated synthetic datasets with the same mean but different variance.
Also introduced outliers to observe their effect on distribution.
## Observations
- Datasets with the same mean can have very different distributions depending on variance.
- Low variance data is tightly clustered around the mean.
- High variance data is more spread out and less predictable.
- Higher spread increases uncertainty in the data.
## Effect of Outliers
- Adding a few extreme values increased the overall spread of the data.
- The histogram scale adjusted to include outliers, making normal data appear compressed.
- The distribution looked visually distorted even though most values remained similar.
- Mean did not change significantly in this case because the dataset size was large compared to the number of outliers.
- Variance increased noticeably, showing higher sensitivity to extreme values.
## ML Insight
- Outliers can significantly affect model performance.
- Models like linear regression are sensitive to extreme values.
- The model may try to fit outliers, increasing error on normal data points.
- This shows the importance of preprocessing and handling outliers in real-world datasets.
## Key Takeaway
Same mean does not imply similar data behavior.
Variance and outliers play a critical role in understanding data distribution and model reliability.
