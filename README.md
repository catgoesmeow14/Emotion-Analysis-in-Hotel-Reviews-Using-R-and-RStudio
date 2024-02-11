# Emotion Analysis in Hotel Reviews

This project focuses on analyzing hotel reviews to categorize each review into emotional sentiments using the NRC Word-Emotion Association Lexicon (EmoLex) in R and RStudio. It aims to provide insights into customer sentiments, which can help improve service quality in the hospitality industry.

## Project Overview

The analysis involves processing hotel guest reviews, categorizing each review into various emotional labels such as joy, trust, fear, and anticipation, and understanding the overall sentiment towards the hotel services. The project utilizes R and RStudio, leveraging packages such as `tm`, `syuzhet`, and `wordcloud` for text mining and sentiment analysis.

## Getting Started

### Prerequisites

- R (Version 4.2.2 or later)
- RStudio

### Installation

1. **Install R Packages**

   Open RStudio and execute the following commands to install the required packages:

   ```R
   install.packages("keras")
   install.packages("tensorflow")
   install.packages("magrittr")
   install.packages("tidyverse")
   install.packages("textclean")
   install.packages("tm")
   install.packages("SnowballC")
   install.packages("wordcloud")
   install.packages("syuzhet")
   install.packages("RColorBrewer")
   install.packages("ggplot2")
   ```

2. **Load Libraries**

   Load the necessary libraries in your R environment:

   ```R
   library(keras)
   library(tensorflow)
   library(magrittr)
   library(tidyverse)
   library(textclean)
   library(tm)
   library(SnowballC)
   library(wordcloud)
   library(syuzhet)
   library(RColorBrewer)
   library(ggplot2)
   ```

## Dataset

The dataset comprises cleaned hotel reviews in a CSV file. The preprocessing includes removal of non-ASCII characters, conversion to lowercase, and elimination of stopwords.

## Analysis Steps

1. **Text Preprocessing**: Clean and prepare the text data for analysis.
2. **Convert to Corpus**: Transform the cleaned text data into a corpus for text mining.
3. **Term-Document Matrix**: Create a term-document matrix to analyze word frequencies.
4. **Emotion Classification**: Use the NRC Word-Emotion Association Lexicon (EmoLex) to classify words into emotional sentiments.
5. **Visualization**: Generate bar plots and word clouds to visualize the analysis results.

## Key Insights

- Identification of the most frequently mentioned aspects in reviews, such as hotel, room, and service quality.
- Analysis of emotional sentiments reveals areas of guest satisfaction and concern.
- Visualization of word frequencies and sentiments offers a comprehensive overview of customer feedback.

## How to Use

To replicate the analysis:

1. Clone this repository or download the R scripts.
2. Ensure you have all the required libraries installed.
3. Run the scripts in RStudio to perform the sentiment analysis and generate visualizations.
