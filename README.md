# Load the data
The following code can be used to import a merged CSV file containing 8000 samples:

```python
import pandas as pd

data = pd.read_csv('https://raw.githubusercontent.com/AdrianRakk/amazon-reviews/main/sentiment_merged/merged_reviews.csv',
                   sep=';', encoding='utf8')
```

Data source: https://www.cs.jhu.edu/~mdredze/datasets/sentiment/index2.html
