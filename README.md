# Steaming Time Variation Analysis (Lime Scaling and Descaling)

## 📌 Overview
The goal of this project is to analyze the descaling frequency of devices based on a predefined steaming threshold.

When a cleaning process is launched on a cooking devices, limescale is being produced in the steam generator. With a predefined steaming threshold and the descaling option selected at cleaning start, a descaling process is triggered in the steam generator once the steaming limit is reached.

## 🛠 Libraries Used
- Python
- NumPy
- Pandas
- Matplotlib

## 📊 Analysis Performed
1. Data Sorting based on device serial number
2. Cummulative distribution calculation
3. New descaling time beased on previous descaling time and steamingthreshold 

## 📈 Results
- Descaling was triggered at half of the steaming threshold value for some devices
- Another proportion started descaling process at the threshold limit

## 🚀 How to Run

1. Clone the repository:
git clone https://github.com/ErikaStella/steaming-time-analysis.git

2. Install dependencies:
pip install -r requirements.txt

3. Open the Jupyter Notebook:
jupyter notebook steaming time variation analysis.ipynb

## 👤 Author
[Erika Kamga]
