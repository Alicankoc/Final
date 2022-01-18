# Final
import numpy as np
import matplotlib.pylab as plt
import seaborn as sns
data = np.random.randint(100, size=(100,100))
print(data)
import numpy as np; np.random.seed(0)
import seaborn as sns; sns.set_theme()
data = np.random.randint(100, size=(100,100))
ax = sns.heatmap(data)
a = [data % 2 == 1]
print(a)
type(a)
b = np.array(a)
print(b)
type(b)
c = b*1
print(c)
import pandas as pd
d = pd.DataFrame(np.vstack(c))
import numpy as np; np.random.seed(0)
import seaborn as sns; sns.set_theme()
ax = sns.heatmap(d)
type(d)
