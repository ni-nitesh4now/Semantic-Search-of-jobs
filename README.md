# Download the Dataset from here:
https://www.kaggle.com/madhab/jobposts

# Job Post Semantic Search

This is a Python script that performs semantic search on a dataset of job posts. It uses the SentenceTransformer library to encode job posts into vectors and performs cosine similarity-based search to retrieve the most relevant job posts based on a user's input query.

## Prerequisites

- Python 3.x
- pandas
- numpy
- sentence_transformers
- sklearn

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/username/repo.git
   cd repo
2. Install the required dependencies:
   ```shell
   pip install -r requirements.txt

## Usage

Prepare the dataset:

Make sure the job post dataset file (data job posts.csv) is present in the same directory as the script.
Optionally, modify the code to adjust the number of records to process (df = df.head(5000)).
Run the script:
   ```shell
   python job_post_semantic_search.py

Enter your search query when prompted. For example:

```Enter the Input Query: I am looking for jobs on python Developer with aws and elasticsearch skills```
The script will perform semantic search based on your query and display the search results.

Select the index number of a search result to view its details.
