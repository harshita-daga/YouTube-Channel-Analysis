# YouTube Data Analysis using Python and YouTube Data API  

## Project Overview  
This project demonstrates how to extract, analyze, and visualize YouTube channel and video data using the YouTube Data API. The focus is on analyzing data from popular data analytics and data science YouTube channels, extracting key metrics like subscriber counts, views, video uploads, and video-level engagement.  

## Features  
- Retrieve channel statistics (e.g., subscribers, views, total videos) using the YouTube Data API.  
- Perform comparative analysis across multiple channels.  
- Extract and analyze video-level data (e.g., titles, views, likes, comments).  
- Visualize trends and key metrics using the Seaborn library.  

## Project Workflow  
1. **Set Up YouTube Data API**  
   - Created a YouTube API key from the [Google Cloud Console](https://console.cloud.google.com/).  
   - Explored the [YouTube Data API documentation](https://developers.google.com/youtube/v3) to understand its usage.  

2. **Data Extraction**  
   - Retrieved channel-level data for multiple YouTube channels.  
   - Focused on "Alex The Analyst" for video-level analysis, extracting video titles, views, likes, and comments.  

3. **Data Analysis**  
   - Loaded the extracted data into Pandas DataFrames.  
   - Converted data types for numerical analysis.  

4. **Visualization**  
   - Used Seaborn to create bar plots for:  
     - Comparing subscriber counts and video counts across channels.  
     - Visualizing top-performing videos by views.  
     - Analyzing yearly and monthly video upload trends.  

## Technologies Used  
- **Programming Language:** Python  
- **APIs:** YouTube Data API  
- **Libraries:**  
  - `pandas` for data manipulation  
  - `google-api-python-client` for API interaction  
  - `seaborn` for data visualization  

## Installation and Usage  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/your-username/youtube-data-analysis.git  
   cd youtube-data-analysis
   
2. **Install the required libraries:**  
   ```bash  
   pip install google-api-python-client pandas seaborn

  3. Replace the `api_key` in the code with your YouTube Data API key.  

4. Run the script to extract and analyze data:  
   ```bash
   python your_script_name.py
   
5. Visualizations and insights will be generated based on the extracted data.


