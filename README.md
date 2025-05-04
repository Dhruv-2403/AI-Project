# 📊 Zipf’s Law Analysis on Song Lyrics Dataset

## 🔍 Project Overview

This project explores **Zipf’s Law** using a dataset of song lyrics. Zipf’s Law states that in natural language, the frequency of any word is inversely proportional to its rank in the frequency table. We aim to validate this phenomenon using real-world data from musical lyrics, applying data preprocessing, analysis, and visualization.

## 🧠 Objective

- Analyze the frequency of words in song lyrics.
- Plot the log-log graph of word rank vs. frequency.
- Check if the word distribution aligns with Zipf's Law.
- Provide insights and interpretations based on the findings.

## 📁 Dataset Description

The dataset includes the following columns:

- `artist` – Name of the artist  
- `title` – Song title  
- `lyrics` – Full song lyrics  
- `album` – Album name  
- `year` – Year of release  
- `date` – Date of release  


## 🧪 Methodology

1. **Data Preprocessing**  
   - Removed punctuation and special characters  
   - Converted all words to lowercase  
   - Tokenized lyrics into individual words

2. **Word Frequency Count**  
   - Counted occurrences of each word using custom Python logic (no external libraries)

3. **Rank-Frequency Distribution**  
   - Sorted words by frequency  
   - Calculated rank of each word  
   - Plotted log(rank) vs. log(frequency)

4. **Visualizations**  
   - Log-log Zipf plot  
   - Bar chart of songs by release year  

## 📈 Visualizations

- ✅ **Zipf’s Law Log-Log Plot**  
- 📊 **Bar Chart of Songs Released Per Year**

## 📌 Key Insights

- The word frequency distribution closely follows Zipf’s Law for the top-ranked words.
- A steep drop-off in frequency indicates the presence of a long-tail distribution.
- Common words (e.g., “love”, “yeah”, “baby”) dominate, while most words occur only once or twice.
- Deviations in tail regions can reflect artist style or genre-specific language.
