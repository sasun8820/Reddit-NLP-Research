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
  - Joy
  - Sadness
  - Anger
  - Surpirse
  - Fear
  - Love 
- Tokenized and cleaned text data using standard NLP preprocessing steps.

### Visualization
- Created visual representations of the findings:
  - **Heatmaps** to highlight substance co-occurrence patterns.
  - **Network graphs** to visualize connections between substances.


## Data 
### Sources
- **Reddit Posts**: Collected from public subreddits discussing opioids and related substances using the **PRAW API**.
- **Keywords**: A curated list of opioid-related terms and polysubstance slang terms, categorized into drug types.
- **Data Volume**:
  - Over **33,000 posts** processed, covering a wide range of drug-related discussions (From 2024 Jan to 2024 Jul)

## Results

### Co-occurrence Analysis
- **Heatmaps**:
  - Revealed frequent pairings of substances
- **Network Graphs**:
  - Showed complex relationships between substances, highlighting polysubstance use patterns, such as meth & cocaine
- **Mutual Information**:
  - **Key Substance Pairings** (Top Mutual Information Scores):
  - Ketamine & Klonopin
  - Benzos & Klonopin
  - Heroin & Methamphetamine
  - Cocaine & Methamphetamine
  - Fentanyl & Xylazine
- These pairings indicate substances frequently mentioned together, potentially suggesting co-usage or shared contexts in user discussions.


### Sentiment Analysis
- Posts were classified into six sentiment categories, providing insights into public perceptions and emotions.
  - **Key Observations**:
    - Posts with **joy** took priority, especially in recreational or celebratory contexts, often linked to experiences involving hallucinations 
    - Negative sentiments like **sadness** and **fear** followed, oftenn reflecting distress or concern in discussions of high-risk substance use
