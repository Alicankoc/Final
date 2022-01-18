# Final
### import numpy as np
### import matplotlib.pylab as plt
### import seaborn as sns
### data = np.random.randint(100, size=(100,100))
### print(data)

Commands entered with import allow us to use them. data = np.random.randint(100, size=(100,100)) command is used to create a 100*100 matrix. Imaging was performed with the print command. 


![resim](https://user-images.githubusercontent.com/95621469/149931797-b86ab985-4b20-4c27-8724-f89bf8ada00c.png)
### import numpy as np; np.random.seed(0)
### import seaborn as sns; sns.set_theme()
### data = np.random.randint(100, size=(100,100))
### ax = sns.heatmap(data)

The seaborn package was used to generate the heatmap. With the data = np.random.randint(100, size=(100,100)) command, 100*100 matrix data is defined and a heatmap is created using the seaborn package abbreviation "sns" together with the ax = sns.heatmap(data) command. 


![resim](https://user-images.githubusercontent.com/95621469/149931828-3de26123-bbd5-4b44-815c-4b37f478efd1.png)
### a = [data % 2 == 1]
### print(a)
### type(a)
### b = np.array(a)
### print(b)
### type(b)
### c = b*1
### print(c)

Odd numbers are filtered out using the a = [data % 2 == 1] command. Checked with print command to verify. b = np.array(a) using the command "a" is made by defining "b" from list to numpy.ndarray as type. Later, it was defined as "c" and (1) was converted to (0). 


![resim](https://user-images.githubusercontent.com/95621469/149931869-1d2430c5-8af1-4525-afdf-e0911d662b0a.png)
![resim](https://user-images.githubusercontent.com/95621469/149931876-c5294388-7b1a-4df6-aa82-9bdeaf77cb58.png)
### import pandas as pd
### d = pd.DataFrame(np.vstack(c))
### import numpy as np; np.random.seed(0)
### import seaborn as sns; sns.set_theme()
### ax = sns.heatmap(d)
### type(d)

The panda package is defined with the import pandas as pd command. With the command d = pd.DataFrame(np.vstack(c)) "c" data is introduced to "d" for the panda package. Then, using the seaborn package, a heatmap was created with the ax = sns.heatmap(d) command. 


![resim](https://user-images.githubusercontent.com/95621469/149931894-0dac8684-23be-45ae-a87a-c145567f45c0.png)
