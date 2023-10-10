# Bnakruptcy Predictor Web App - Internship Project at Technocolabs Softwares 💡 



This repository contains the code and resources for deploying a machine learning project end-to-end. The project is implemented using Python 3.10.

## Setting up the Environment

To set up the required environment, follow these steps:

1. Install Anaconda or Miniconda, if not already installed.

2. Create a virtual environment using the following command:

   ```bash
   conda create -p Projectvenv python==3.10.9 -y
   ```

   This command creates a virtual environment named `venv` with Python version 3.10.9

3. Activate the virtual environment:

   ```bash
   conda activate Projectvenv
   ```

   This command activates the `Projectvenv` virtual environment.



   
## Ignoring Virtual Environment

To avoid including your virtual environment in version control, create a `.gitignore` file in the root directory of your project if it doesn't already exist. Then, add the following line to the `.gitignore` file:

```plaintext
/venv/
```

## Dependencies

To install the project dependencies, run the following command:

```bash
pip install -r requirements.txt
```

This command will install all the required packages and libraries listed in the `requirements.txt` file.

## Usage

To use this project, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/ayoubdaoudii/Bankruptcy_Predictor_Web_App_Technocolabs_Softwares_internship.git
   ```
   
2. Change to the project directory:

   ```bash
   cd Bankruptcy_Predictor_Web_App_Technocolabs_Softwares_internship
   ```
3.  Run the Python Application: Execute the following command to run the web application:
   ```bash
   python app.py
   ```

## Project Name
Bankruptcy Predictor Web App

## Project Description 📝
The Bankruptcy Predictor Web App, developed by Technocolabs Softwares, is a cutting-edge solution designed to empower businesses with the ability to predict and prevent financial distress. Inspired by the economic crisis of 2007, our mission is to equip companies with the tools they need to navigate financial challenges effectively and ensure market sustainability.

## Purpose of the Project 🎯
The primary goal of the Bankruptcy Predictor Web App is to equip businesses with a powerful tool for predicting and mitigating financial distress. In light of the economic challenges witnessed in events like the 2007 crisis, our project aims to provide companies with a proactive means of safeguarding their financial stability. Through the development of accurate and reliable predictive models, we aspire to enable businesses to measure and predict their financial condition effectively. By harnessing advanced statistical techniques and machine learning algorithms, our goal is to empower organizations to make data-driven decisions that fortify their financial health and resilience in an ever-evolving market landscape

## Key Objectives 🌟
- Predict and Prevent Financial Distress: Develop a robust predictive model that allows businesses to predict and prevent financial distress effectively.

- Accurate Financial Measurement: Create a system for accurately measuring and forecasting the financial condition of corporate entities, providing valuable insights.

- Data-Driven Decision-Making: Empower organizations to make informed, data-driven decisions that enhance their financial health and resilience.

- Proactive Financial Management: Enable businesses to proactively navigate financial challenges, ensuring market sustainability, and preventing economic crises like the 2007 downturn from recurring.

## Target Audience 🎯👥
- Business Owners and CEOs: Small, medium, and large business owners, as well as CEOs, seeking proactive financial management tools to safeguard their companies' financial stability.

- Financial Analysts: Professionals in the finance and analysis field looking for advanced tools to predict financial distress and evaluate corporate financial health.

- Risk Managers: Risk management professionals and departments interested in early warning systems to mitigate financial risks.

- Investors and Lenders: Investors and lending institutions keen on assessing the financial viability of potential investments or borrowers.

- Financial Consultants: Consultants specializing in financial advisory and corporate finance, offering data-driven insights to their clients.

- Academic and Research Institutions: Educational institutions and researchers in finance and data science interested in studying and utilizing advanced predictive models.

- Startups and Entrepreneurs: Startup founders and entrepreneurs aiming to ensure financial stability and growth in their businesses' early stages.

- Regulatory Authorities: Government bodies and regulatory authorities interested in monitoring corporate financial health and sustainability.

## Expected Outcomes 📈🔍
- Improved Financial Decision-Making: Businesses and professionals will have access to a powerful predictive tool that enhances their ability to make informed and data-driven financial decisions.

- Enhanced Financial Stability: Companies using the app will be better equipped to navigate financial challenges proactively, leading to improved financial stability and resilience.

- Risk Mitigation: The app's predictive models will aid in early identification and mitigation of financial risks, helping businesses avoid distress and crises.

- Market Sustainability: By empowering businesses with proactive financial management tools, the project contributes to market sustainability and prevents catastrophic economic events from recurring.

- Data-Driven Insights: Users will benefit from actionable data-driven insights, enabling them to measure, predict, and address financial issues effectively.

- Educational Value: Academic and research institutions will gain access to a valuable tool for studying financial dynamics and exploring advanced predictive models.

- Business Growth: Startups and entrepreneurs will have the means to secure and expand their businesses, attracting potential investors and lenders with enhanced financial viability.

## Project Structure 
```
📁 artifacts
   └── 📄Data.csv
   └── 📄model.pkl.csv
   └── 📄preprocessor.pkl
   └── 📄test.csv
   └── 📄train.csv

📁 logs

📁 src
   └── 📁 components
       └── 📄 __init__.py
       └── 📄 model_trainer.py
   └── 📁 Pipeline
       └── 📄 __init__.py
       └── 📄 predict_pipline.py
       └── 📄 train_pipline.py
   └── 📄 exception.py
   └── 📄 logger.py
   └── 📄 utils.py
📁 static
📁 templates
📄 .gitignore
📄 README.md
📄 app.py
📄 data_ingestion.py
📄 data_transformation.py
📄 requirements.txt
📄 sample_test.py
📄 setup.py
```
### Description of files 

`artifacts`: This directory contains artifacts related to your project, including the preprocessor.joblib file. It may also include subdirectories for model-related files in the Models folder.

`src`: This is the main source code directory.

`components`: This directory contains subdirectories for various components of your project, such as data cleaning, data preprocessing, feature engineering, data ingestion, and model training.
config: This directory contains configuration files for your project, such as entity_config.py.

`Pipeline`: This directory holds scripts related to the different stages of your data processing pipeline, from data cleaning to model training and prediction.

`exception.py`: This file likely contains custom exception classes for handling errors and exceptions in your project.

`logger.py`: This file may contain code for setting up and managing logging in your project.

`utils.py`: This file likely contains utility functions and helper code used throughout your project.

`static and templates`: These directories are typically used for web applications and may contain static files like stylesheets, images, and HTML templates.

`.gitignore`: This file specifies which files and directories should be ignored by Git version control.

`README.md`: The README file that provides an overview of your project, usage instructions, and other important information.

`app.py`: These files likely contain the main application logic for running your web application.

`requirements.txt`: This file lists the project dependencies and their versions.

`setup.py`: A setup file that can be used for packaging and distributing your project.




## Contact

For any questions or inquiries, please feel free to reach out to me via email at [ayoubdaoudi2001@gmail.com](mailto:ayoubdaoudi2001@gmail.com) 
or connect with me on [LinkedIn](https://www.linkedin.com/in/ayoub-daoudi-7735a9228/).
