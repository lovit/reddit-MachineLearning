# Reddit (Machine Learning)

Subreddit. Subsamples of reddit (topic : machine learning)

Each line is submission (a article). Line in each file is json format. 

```python
import json

with open("RS_2018-01", encoding='utf-8') as f:
    lines = [line.strip() for line in f]

submissions = [json.loads(line) for line in lines]

```

