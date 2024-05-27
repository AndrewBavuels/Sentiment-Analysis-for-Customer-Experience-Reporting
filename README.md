# **Sentiment Analysis for Customer Experience Reporting 📈📲🎵**

The goal for this project was to apply advanced natural language processing techniques to **analyze customer reviews** and then, identify **areas for improvement** in the user experience.

*"**Fun Fact:** This project idea popped out while I was reviewing LinkedIn Jobs. One of them roles got my attention, regarding customer experience improvement and teamwork, to test new features for an App."*

## 1. Project description 👇

> 
### _Development of KPI Dashboards and Reporting System, using Python, Pandas, and NLP tools._

For this project I used a "Spotify App Reviews" dataset from [Kaggle](https://www.kaggle.com/datasets/mfaaris/spotify-app-reviews-2022). After being processed, the output was explored and saved in Tableau Public.


### Problems detected to solve are as follows:

- Complex issues and gaps that affect customer experience
- There is no assigned role structure for the identified problems
- No reporting system to communicate issues effectively to stakeholders
- Insufficient capacity to reply customer/user reviews


## **2. Technology stack 💻**

### Programming language:
- [Python](https://docs.python.org/3/)


### Python Libraries:
- [matplotlib.pyplot](https://matplotlib.org/stable/contents.html): For data visualization.
- [numpy](https://numpy.org/doc/stable/): For mathematical operations and array manipulation.
- [pandas](https://pandas.pydata.org/docs/reference/frame.html): For data manipulation and analysis.
- [nltk](https://nltk.org/): For sentiment analysis among natural language processing tasks.

### Functional architecture design:

![Spoti_pipeline](https://github.com/AndrewBavuels/Final-Project-Sentiment-Analysis-for-Customer-Experience-Reporting/blob/main/images/pipeline.png)

## **3. Minimal Functional Product ⚙️**

- Notebook with the code that processes the dataset, from its Data Cleaning to the Area Classification, **described in the Functional architecture design**. 
- Dashboards for both Issues & Satisfaction Management uploaded to Tableau Public, containing the visualizations created from the processed dataset. **The link is found in the Demo as main.txt file**

### Dashboards previews:

- Issues Management: Dashboard from Negative Reviews

![Issues Dashboard](https://github.com/AndrewBavuels/Final-Project-Sentiment-Analysis-for-Customer-Experience-Reporting/blob/main/images/Issues%20Dashboard.png)

- Satisfaction Management: Dashboard from Positive Reviews

    > *"I named this dashboard Spotiliebers (a parody term from Justin Bieber Fans) referring to Spotify Users Support, in order to give a fresh touch to this project".*

![Spotiliebers Dashboard](https://github.com/AndrewBavuels/Final-Project-Sentiment-Analysis-for-Customer-Experience-Reporting/blob/main/images/Spotiliebers%20Dashboard.png)

## **4. Demo 📊📈📉**

To show what it looks like in action, [click here](https://public.tableau.com/app/profile/andres.buelvas.diago/viz/Final_Project_m3_main_Relational_Model/1_1_IssuesDashboard?publish=yes).
> **_Note:_** The demo is also contained in the main.txt file from the Dashboard folder.

## **5. Folder structure 📁**
```
└── project
    ├── _wip_
    ├── .gitignore
    ├── notebooks
    │   └── main.ipynb
    ├── images
    │   ├── pipeline.png
    │   ├── Issues_Dashboard.png
    │   └── Spotiliebers_Dashboard.png
    ├── data
    │   ├── raw
    │   │   └── spoti_reviews.csv
    │   └── processed
    │       └── reviews_report.csv
    ├── dashboard
    │   └── main.txt
    └── README.md    
```

## **6. Next steps 💡**

- Develop an action plan to address problem areas identified in the 80-20
- Establish a multidisciplinary team with clearly defined roles to address the problem areas identified in the 80-20
***
- Automate the connection with new data in the reporting system
- Integrate other data formats such as MySQL, PostgreSQL, JSON, XML

###  **Contact info📧**
For further information, reach me at andrew.bavuels@gmail.com
