# SCV---ACEZE
Space Created Value from team ACEZE

## How to process
"Data_Processing_FullGrid.ipynb" is the full data-processing programme. It will process full gneral&grid data.

"Data_Processing_vQuick.ipynb" only process general data. It is a quicker version that does't caculate grid data. The output is used to train models.

"Model_Training.ipynb" trains first hurdle Conditional Threat Magnitude Regressor, then Spatial Control Transition Model (xC).

## Sample Data Download
The sample data is too large. It has been uploaded to this link.
https://drive.google.com/drive/folders/1dfPfgl5aZkMQmY64vlkAv1pmTHe_FxQZ?usp=share_link

"epv_events.parquet.gzip" includes the full unprocessed data

"processed_data_light" includes the general data for model training.

"processed_data_as_team" includes a full data (with grids) of 5 games for team 407.
