# behretims
Elte DSD Beehive Realtime Monitoring System project

DANi_Filtering.zip contains all neccesary files needed to:
  - do feature extraction (PreProcessing/preprocessing_batch.py)
  - do file content check (file_content_check_batch.py)
  - Build CNN and do Classification on imgaes on CPU 
  - Build CNN and do Classification on images on GPU 
  - Build RNN and do Classification on timeseries on LSTM 

Content:

Classification/Classification_CNN_CPU.py - Build CNN based on input parameters, and perform classification on images on CPU
Classification/Classification_CNN_GPU.py - Build CNN based on input parameters, and perform classification on images on GPU
Classification/Classification_LSTM_CPU.py  - Build RNN based on input parameters, and perform classification on timeseries on CPU
Classification/Enum/Enum_types.py - Contains all enum(discrete manually defined) types
Data/FE_data - directory for extracted data
Data/WAV_data - directory for input WAV data
Enum/Enum_types.py
Feature_extraction/Feature_extraction.py - contains code for feature extraction
File_content_check/file_content_check.py - contains code for feature extraction
File_content_check/file_content_check_batch.py - contains code for content after feature extraction
Filtering/filtering.py - contains code for filtering
Filtering/dani_filtering.py - contains code for DANi filtering
Outputs/Data_Writter.py  - contains code for writting to file
Outputs/Draw.py - contains code for visualizing spectrograms and ts
Outputs/Visualize_log.py - contains code for visualizing logs after classification
PreProcessing/preprocessing_batch.py - contains code for batch feature extraction and filtering

For further information or support contact the developer:
Dániel T. Várkonyi
(varkonyid@inf.elte.hu)
Please put "behretims project" in mail subject!
