#### 数据探索

>思路：数据探索，做一点点的修改-->数据清洗(空值的填充)-->数据预处理（数据的归一化，标准化等）-->模型构建-->训练预测-->保存提交

```python
import pandas as pd
train = pd.read_csv("./train.csv")
train.head()

import pandas_profiling as ppf
# explore data analysis
ppf.ProfileReport(train) 
```
