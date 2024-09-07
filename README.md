# SpotifySentimeter : : Spotify Song Sentiment Analysis
 A project done in jupyter notebook for fetching spotify songs and analysing the sentiments to predict the new songs ratings.

## Overview
SpotifySentimeter is a data science project aimed at analyzing the sentiment of songs on Spotify. Comprises of scraping playlists data such as song titles, singers, writers, and durations, and uses the Genius Lyrics API to fetch the song lyrics along with selenium to search for the lyrics that are not present in the API. The project then applies Natural Language Processing (NLP) techniques, including **Sentiment Intensity Analyzer** from the VADER library, to score the sentiment of each song's lyrics. Furthermore, with the leverage of ANN ,the model trains better to get the sentiment scores for new upcoming songs. The final output is a sentiment-based insight for each song in the dataset.

## Features
- **Spotify Web Scraping**: Fetches song metadata (title, artist, writer, duration) from Spotify playlists.
- **Genius Lyrics Integration**: Fetches song lyrics using the Genius API.
- **Exploratory Data Analysis (EDA)**: Visualizes trends and distributions in song data.
- **Sentiment Analysis**: Uses VADER (Sentiment Intensity Analyzer) to analyze the sentiment of song lyrics (positive, negative, and neutral).
- **Data Visualization**: Plots sentiment scores and other insights for songs.
- **Artificial Neural Network**: Trains the model better on the sentiments to predict new sentiments and ratings for the upcoming songs.

## Tech Stack
- **Programming Language**: Python
- **Libraries Used**: 
  - Web Scraping: `BeautifulSoup`, `requests`
  - API Integration: `GeniusAPI`
  - NLP: `VADER Sentiment Intensity Analyzer`
  - Data Manipulation: `Pandas`, `NumPy`
  - Visualization: `Matplotlib`, `Seaborn`
  - Data Cleaning: `NLP` tools
- **APIs**:
  - **Spotify API**: Scrapes playlist data.
  - **Genius API**: Fetches song lyrics for further sentiment analysis.

## Installation
To run the project locally, follow these steps:

1. Clone this repository:
    ```bash
    git clone https://github.com/Muhammad-Hamza-Khan-03/SpotifySentimeter.git
    ```

2. Navigate to the project directory:
    ```bash
    cd SpotifySentimeter
    ```

3. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Obtain API keys:
   - **Genius API**: Sign up for a Genius developer account and obtain an API key. Replace the placeholder in the code with your key.

5. Run the project:
    ```bash
    python main.py
    ```

## Usage
1. **Scraping Spotify Playlists**: The project scrapes song details like title, artist, and duration from any given Spotify playlist.
2. **Fetching Lyrics**: It uses the Genius API to fetch the lyrics of the corresponding songs.
3. **Sentiment Analysis**: Sentiment Intensity Analyzer (VADER) is applied to each song's lyrics to determine the positive, negative, neutral, and compound sentiment scores.
4. **Visualization and EDA**: Sentiment analysis results are visualized using various data plots, showing insights about the mood of songs in a playlist.
5. - **Artificial Neural Network**: Spervised learning of model using approach of Deep neural networks enhancing the prediction.

## Data Flow
1. Scrape Spotify playlist data.
2. Fetch lyrics using Genius API.
3. Perform EDA on playlist data.
4. Analyze song lyrics for sentiment scores.
5. Deep Neural Networks for prediction analysis
6. Visualize results.


## Sample Visualizations
<!-- ![Sentiment Distribution](assets/sentiment_distribution.png) -->
<!-- ![Top Artists by Sentiment](assets/top_artists_sentiment.png) -->

## Conclusion
SpotSentiment provides a comprehensive analysis of the lyrical sentiment of Spotify playlists. It can be used to detect the overall mood or emotional tone of songs in a playlist, providing deeper insights into music trends.

## Future Enhancements
- Improve lyric matching for songs with ambiguous titles.
- Add support for additional music platforms (e.g., Apple Music, YouTube Music).
- Explore more advanced NLP techniques for sentiment analysis.
- Implement real-time playlist sentiment analysis.

## Contact
For more information, feel free to reach out:
- **Name**: Muhammad Hamza Khan
- **Email**: hamzakhan102003@gmail.com
- **LinkedIn**: https://www.linkedin.com/in/hamza-khan03/