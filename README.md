<h1 align="center"><strong>Streaming Analysis</strong></h1>

# Introduction
*Insert intro here*

Project objective: (what you expect the project to do) *
This project will analyze viewing data from Netflix and see how it compares to popular tv and movies. 

Statement of Work:  (what work needs to be done) *
I need to gather the data, add to a Jupyter Notebook, and explore the data. 

### Changes to the Project Plan
I turned in my Project Plan when I only had my Netflix dataset. Since then, I was able to obtain my Hulu and Prime Video datasets.

### Project Challenges

# Datasets Used
### Personal Streaming Viewing History
<ul>
  <li>Hulu</li>
  <li>Netflix</li>
  <li>Prime Video</li>
</ul>

### Additional dataset
[Kaggle - Netflix, Movies, and Popularity](https://www.kaggle.com/code/advaypatil/netflix-movies-and-popularity/data)

# How to Run this Project
`Using a Virtual Environment`
  1. Clone this repo `git clone https://github.com/istarlet/streaming_analysis.git`
  2. Download the datasets [here](https://drive.google.com/drive/folders/1kDuL7BR_Rc3V7Fl5HHSQg8jn4fChZEP3?usp=share_link)
  3. Create a new folder in the cloned repo called `Datasets` and add downloaded datasets 

   *(**Note:** If you downloaded the dataset as a .zip file, make sure to add the individual datasets to the new "Datasets" folder and not the folder they were zipped in.)*

  4. Type command
      `pip install -r requirements.txt`
  5. Then run this file https://github.com/istarlet/streaming_analysis/blob/main/streaming_data.ipynb
 
### To deactivate the Virtual Environment
  Type command
  `deactivate`

### Python packages used in this project:
<ul>
  <li>datetime</li>
  <li>matplotlib</li>
  <li>pandas</li>
  <li>seaborn</li>
</ul>

# Project Requirements
## Feature 1 
`Read TWO data files (JSON, CSV, Excel, etc.).`

I read in four CSV files. 
<ul>
  <li>AshleyViewingActivity.csv</li>
  <li>DigitalPrimeVideoViewingHistory.csv</li>
  <li>HuluViewingHistoryUpdated.csv</li>
  <li>titles.csv</li>
</ul>

## Feature 2
`Clean your data and perform a pandas merge with your two data sets, then calculate some new values based on the new data set.`

I cleaned the each dataset in their own Jupyter Notebook.
   > [Hulu](hulu.ipynb)
   > [Imdb](imdb.ipynb)
   > [Netflix](netflix.ipynb)
   > [Prime Video](prime_video.ipynb)

I then concatonated the Hulu, Netflix, and Prime Video datasets together. 

With my new combined streaming dataset, I merged it with the Imdb dataset. 

## Feature 3
`Make 3 matplotlib or seaborn (or another plotting library) visualizations to display your data.`
![image](https://user-images.githubusercontent.com/14065849/202565871-15b3fb4f-5275-4898-9ea7-8b613501426a.png)

![image](https://user-images.githubusercontent.com/14065849/202564382-56d85a9b-482a-4c53-8a17-c2dc9871f003.png)

![image](https://user-images.githubusercontent.com/14065849/202564214-0212921c-00f8-4c2a-97ef-8e7ad750e6e6.png)

![image](https://user-images.githubusercontent.com/14065849/202563303-ce0980b6-cbd9-4e92-a5c5-eb01cdf3e136.png)

![image](https://user-images.githubusercontent.com/14065849/202563724-0d5363c0-f27d-4197-be3a-1206d24f0537.png)

![image](https://user-images.githubusercontent.com/14065849/202563856-1bc221d6-385f-437c-a5aa-6f9ec231a6ae.png)

![image](https://user-images.githubusercontent.com/14065849/202564792-ed918b3d-d55f-4879-8557-8e06915ae14e.png)

## Feature 4
`Utilize a virtual environment and include instructions in your README on how the user should set one up`

I created a virtual environment with instructions in the [How to Run this Project](https://github.com/istarlet/streaming_analysis/blob/main/README.md#how-to-run-this-project) section.

## Feature 5
Annotate your code with markdown cells in Jupyter Notebook, write clear code comments, and have a well-written README.md. Tidy up your notebook, and make sure you don’t have any empty cells or incomplete cells that don’t do anything. Make sure it’s all functional before your final github commit.
