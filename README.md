# Agriculture_Data-Analytics_Project
The Crop Recommendation System, coupled with dataset visualizations and Exploratory Data Analysis (EDA), is built using different libraries and the Django framework. This tool advises on optimal crops based on specified parameters, offering a user-friendly interface for informed agricultural decisions. 

                        *Crop Recommendation and Analysis Django Project - README*

Project Overview:

The Crop Recommendation and Analysis Django project is designed to assist farmers in making informed decisions regarding crop selection and optimizing agricultural practices. The project aims to provide crop recommendations based on various parameters by leveraging diverse datasets such as soil, temperature, production, price, area, rainfall, yield, season, pesticide, state, and fertilizer. Additionally, the project performs historical data analysis, offering insights into trends and optimizing agricultural strategies for better yields and economic returns.

Repository Structure:

The GitHub repository is organized as follows:

- */data*: Contains datasets related to soil, temperature, production, price, area, rainfall, yield, season, pesticide, state, and fertilizer.
- */src*: Holds the Django project source code.
- */docs*: Documentation files, including this README.

*Commits:*

The commit history reflects a logical progression of the project. Each commit is accompanied by a meaningful message describing the changes made. Commits are organized to maintain a clean and comprehensible development history.

*Installation Instructions:*

1. *Setup Environment:*
   - Install Python and Django.
   - Create a virtual environment for project isolation.

2. *Navigate to Project Directory:*
   - Move to the project directory: cd crop-recommendation-django.

3. *Database Setup:*
   - Run migrations: python manage.py migrate.

4. *Load Data:*
   - Load datasets into the database: python manage.py loaddata data/*.json.

5. *Run Server:*
   - Start the Django development server: python manage.py runserver.

6. *Access the Application:*
   - Open a web browser and go to http://127.0.0.1:8000/ to use the application.

*Usage Guidelines:*

- *Crop Recommendation:*
  - Input parameters such as soil type, temperature, etc., to receive personalized crop recommendations.
    
- *Data Analysis:*
  - Explore historical trends and insights through the provided dashboard.

*Contributing:*

If you wish to contribute to the project, please follow the standard GitHub workflow:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make changes and submit a pull request.

*Contributors of the project:*

1. Siddharth R Bhardwaj
2. Driti Arun Singhania
3. Ria Ann Bijo
4. Sejal Saluja
   

*Acknowledgements:*

Give credit to any external libraries, datasets, or sources used in the project.
