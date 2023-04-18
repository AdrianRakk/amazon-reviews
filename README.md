# Load the data
The following code can be used to import the merged CSV file:

```python
import pandas as pd

data = pd.read_csv('https://github.com/DOT503-DevOps/amazon-reviews/raw/main/sentiment_merged/merged_reviews.csv',
                   sep=';', header=0)
```

Data source: https://www.cs.jhu.edu/~mdredze/datasets/sentiment/index2.html
