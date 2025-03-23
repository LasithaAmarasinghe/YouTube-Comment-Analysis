# YouTube-Comment-Analysis

This tool analyzes the sentiment of comments on YouTube videos. It uses sentiment analysis to classify comments as positive, negative, or neutral, and provides visualizations to display the distribution of these sentiments.

<img src="https://github.com/LasithaAmarasinghe/YouTube-Comment-Analysis/raw/main/static/index.png" width="800" height="auto">

## 🎥 Demo

Here’s a quick demo of the **YouTube-Comment-Analysis**:

[![▶️ Watch the demo](https://github.com/LasithaAmarasinghe/YouTube-Comment-Analysis/raw/main/static/thumbnail.png)](https://vimeo.com/1068613686/94d8fc8668)

## 🚀 Features

- **YouTube Comment Analysis**: Fetch and analyze comments on a YouTube video.
- **Sentiment Classification**: Categorizes comments into Positive, Negative, or Neutral sentiments.
- **Visualization**: Displays sentiment distribution as bar and pie charts.
- **Notable Comments**: Highlights the most positive and negative comments with sentiment scores.

## 🛠️ Technologies/ Tools

* Jupyter Notebook / [Google Colab](https://colab.research.google.com/)
* Python 3+
* Python packages
  * Google API Client - `pip install google-api-python-client`
  * VaderSentiment - `pip install vaderSentiment`
  * Matplotlib - `pip install matplotlib`
  * Emoji - `pip install emoji`
  * Numpy - `pip install numpy`
  * Flask - `pip install flask`
* HTML5
* CSS3
 
![Python](https://img.shields.io/badge/python-3670A0?logo=python&logoColor=FFFF00)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?logo=jupyter&logoColor=white)
![Matplotlib](https://img.shields.io/badge/matplotlib-%23FF6F00)
![vaderSentiment](https://img.shields.io/badge/vaderSentiment-purple)
![Emoji](https://img.shields.io/badge/emoji-%23white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?logo=numpy&logoColor=white)
![flask](https://img.shields.io/badge/flask_-black)
![html5](https://img.shields.io/badge/html5-%23FF6F00.svg?logo=html5&logoColor=white)
![css3](https://img.shields.io/badge/css3-8A2BE2.svg?logo=css3&logoColor=white)

## 📖 Setup Instructions  

1. Clone the repository:
   ```sh
   git clone https://github.com/LasithaAmarasinghe/YouTube-Comment-Analysis.git
   ```
2. Navigate to the project directory:
   ```sh
   cd YouTube-Comment-Analysis
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Set Up YouTube API

   To interact with the YouTube API, you need an API key. Follow these steps to get a YouTube API key:

    * Go to the [Google Developer Console](https://console.developers.google.com/).
    * Create a new project.
    * Enable the **YouTube Data API v3** for your project.
    * Generate an **API key** for your project.
    * Paste the generated API key into the `app.py` file under the `API_KEY` variable:

    ```python
    API_KEY = 'your_api_key_here'  # Replace with your actual API key
    
5. Run the Flask application:
   ```sh
   python app.py
   ```

6. Use the Analysis

   * Open your browser and go to `http://127.0.0.1:5000/`.
   * Enter the YouTube video URL in the provided input field.
   * Click on **"Analyze Comments"** to process the comments of the video.
   * The results page will display the sentiment analysis results along with sentiment distribution charts.
  
## 📊 Results

<img src="https://github.com/LasithaAmarasinghe/YouTube-Comment-Analysis/raw/main/static/result.png" width="800" height="auto">

## 📋 License
 
 * This project is licensed under the MIT License. See the [LICENSE](MIT-LICENSE.txt) file for details.
