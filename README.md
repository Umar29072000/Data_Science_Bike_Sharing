# Bike Sharing Dashboard
This dashboard is an interactive dashboard that tells about Bike Ride average in various condition, taken from January 2011 to January 2012. The dashboard provides time filter to filter out specific time range into the data and the insights.
## Streamlit Link
https://datasciencebikesharing-ioemmap27ramm3btjps9yq.streamlit.app/
## File Contents
```
├───dashboard
| ├───day_data.csv
| ├───hour_data.csv
| └───streamlit.py
├───data
| ├───day.csv
| └───hour.csv
├───notebook.ipynb
├───README.md
└───requirements.txt
```
## Setup environment
```
conda create --name main-ds python=3.8
conda activate main-ds
pip install numpy pandas scipy matplotlib seaborn jupyter streamlit babel
```
## Run steamlit app
```
streamlit run dashboard/streamlit.py
```
## Streamlit Dashboard Screenshot

<img width="1280" alt="1" src="https://github.com/Umar29072000/Data_Science_Bike_Sharing/blob/12b2c5ba2c72605c8493a2bcb5f443768459f2a2/dashboard%20screenshot/1.png">
<img width="1280" alt="2" src="https://github.com/yudhasaputra/Data-Analytics-Project-BikeSharingDataset/assets/34949406/fc409102-704f-4dbe-9604-92f98483897b">
<img width="1280" alt="3" src="https://github.com/yudhasaputra/Data-Analytics-Project-BikeSharingDataset/assets/34949406/7eb98f0e-0a62-4143-a185-7bae653a5e57">
<img width="1280" alt="4" src="https://github.com/yudhasaputra/Data-Analytics-Project-BikeSharingDataset/assets/34949406/20c22f4d-fc7b-4db0-b8f5-ff60f2f2fb15">
