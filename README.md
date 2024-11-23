# Yango Traffic Speed Prediction
## 1. Description
Yango Traffic Speed Prediction HACKATHON is a machine learning project designed to optimize urban mobility in Accra by predicting average traffic speeds every 15 minutes. This model helps Yango improve route planning, provide accurate estimated times of arrival (ETA), and offer an enhanced experience for both users and partner drivers.
### Situation:
Urban traffic congestion in Accra is a significant challenge, causing delays and inefficiencies for both commuters and service providers. Efficiently predicting average traffic speeds can mitigate these challenges, enabling more reliable and quicker routes for users.

### Task:
The goal of this project is to build a machine learning model that predicts average traffic speeds on major roads in Accra, leveraging traffic pattern data collected by Yango in September 2024. These predictions must capture variations at different times of the day to ensure accuracy and reliability.

### Action:
A comprehensive data science pipeline was developed, covering data preprocessing, exploratory analysis, and machine learning modeling. By analyzing traffic trends and implementing advanced prediction algorithms, the project aims to deliver robust traffic speed forecasts every 15 minutes.

### Result:
The resulting machine learning model empowers Yango to optimize route planning, reduce travel times, and provide accurate ETAs, directly impacting users’ daily schedules and improving their overall experience.

## 3. Why the Name "Yango Traffic Speed Prediction"?
This project is named after Yango to reflect its core mission: enhancing mobility by leveraging data science to provide actionable traffic insights.


## 3. Table of Contents

- [Project Preview](#4-project-preview)
- [Installation](#5-installation)
- [Dependencies](#6-dependencies)
- [Usage](#7-usage)
- [Contributing](#8-contributing)
- [License](#9-license)
- [Contact Information](#10-contact-information)
- [Acknowledgements](#11-acknowledgements)

## 4. Project Preview

![Project Preview](outputs\visualizations\preview.png)


## 5. Installation

1. Clone the repository:
   ```sh markdown
   HTTPS
   git clone https://github.com/calyxish/Yango-Traffic-Speed-Prediction.git

   GitHub CLI
   git gh repo clone calyxish/Yango-Traffic-Speed-Prediction

   ```
2. Navigate to the project directory
   ```sh
    cd yango-traffic-speed-prediction  
   ```
3. Set up a virtual environment and activate it:
   ```sh markdown
    python -m venv venv  
    venv\Scripts\activate    # On Mac: source venv/bin/activate
   ```
4. Install required packages
   ```sh markdown
    pip install -r requirements.txt
   ```

## 6. Dependencies
   ```sh markdown
python 3.x
pandas
numpy
seaborn
matplotlib
scikit-learn
xgboost
lightgbm
catboost
jupyter Notebook (optional)
   ```

## 7. Usage
### Running YTSP_1 OR YTSP_2:
- 1. Data:
   ```sh markdown
   Cant make data available to the public because:
   it Yango's intellectual property.
   And I am order not to make it to the public.
   ```
- 2. Model to Run:
   ```sh markdown
   YTSP_2.ipynb gave me a better RMSE.
   ```
- 3.  Access the results in the
   ```sh markdown
    outputs/Submissions.csv
   ```
   folder.


## 8. Contributing

Guidelines for contributing to your project.

```sh markdown
Your contributions are welcome! The open-source community thrives on collaboration. If you’re interested in improving Onesimus, please follow these steps:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
```

## 9. License

Distributed under ... Not Yet

## 10. Contact Information
Calyx Ish
GitHub: @calyxish

## 11. Acknowledgements

```sh markdown
Yango for providing traffic pattern data and inspiring the project and such  an awesome HACKATHON.
```