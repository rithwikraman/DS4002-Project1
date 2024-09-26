# DS4002 Project 1 - ChatGPT Sentiment Analysis

## Team Mango:
* Rithwik Raman
* Pranav Arora
* Ayush Acharya

## Software and Platform
* Development was performed in a Python-based Jupyter notebook.
* The following Python packages imported:
  * Pandas
  * Matplotlib
  * Seaborn
  * NumPy
  * Scikit-Learn
* Scripts were ran on the Google Colab Runtime Environment platform.

## Map of Documentation
### DS4002-Project1
* DATA
 * GPT_reviews.csv
 * Review_groups_output.csv
 * final_review_groups_output.csv
* OUTPUT
 * Avg_Rating_Per_App.png
 * LDA_Group_Distribution_Per_App.png
 * Ratings_Distribution.png
 * Sentiment_Distribution_Across_Groups_Bar.png
 * Sentiment_Distribution_Across_Groups_Pie.png
 * Sentiment_Distribution_Per_App.png
 * Total_Thumps_Up_Per_App.png 
* SCRIPTS
 * DS_4002_Project_1_final_script.ipynb
* LICENSE
* README.md

## Reproducing these Results
* Download the dataset from: https://github.com/rithwikraman/DS4002-Project1/blob/main/DATA/GPT_reviews.csv
* Download the LDA result dataset from: https://github.com/rithwikraman/DS4002-Project1/blob/main/DATA/Review_groups_output.csv
* Upload it to your Google Colab Runtime Environment
* Update .read_csv() to the location of your GPT_reviews.csv dataset
* Run the scripts until cell 19. 
* Once you reach the LDA analysis portion within the script (Cell 19), update the read_csv() to the location of your Review_groups_output.csv
* Run the Jupyter Notebook and view the results
