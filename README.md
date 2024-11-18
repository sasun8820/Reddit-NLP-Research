# Reddit NLP Project
- Collaboration with the Mailman School of Public Health at Columbia University, under the guidance of Dr. Kechna Cadet and Dr. Silvia Martins


## Project Overview 
- Aimed to analyze opioids-related polysubstance use data from Reddit using natural language processing (NLP) techniques. The goal was to uncover hidden patterns in drug use and sentiment trends, offering valuable insights into public health concerns surrounding polysubstance abuse.
### Key objectives:
- Retrieve and preprocess Reddit data to identify polysubstance use discussions.
- Compute co-occurrence metrics to understand relationships between substances.
- Classify posts into sentiment categories to assess public perception and trends.

## Methodology

### Data Acquisition
- Utilized the **PRAW API** to scrape drug-related posts from Reddit.
- Extracted data using a comprehensive list of substance-specific keywords and slang terms.

### Data Analysis
#### Co-occurrence Metrics
- Computed co-occurrence metrics between drug mentions.
- Created **heatmaps** to visualize frequent substance pairings.
- Generated **network graphs** to explore relationships between substances.

#### Sentiment Analysis
- Applied **BERT’s pre-trained model** on Hugging Face to classify posts into six sentiment categories:
  - Positive
  - Negative
  - Neutral
  - Anger
  - Sadness
  - Joy
- Tokenized and cleaned text data using standard NLP preprocessing steps.

### Visualization
- Created visual representations of the findings:
  - **Heatmaps** to highlight substance co-occurrence patterns.
  - **Network graphs** to visualize connections between substances.


## Data 

## Results 
