# AR-Sanad 280K Dataset v1 and v2 For Hadith Narrator Disambiguation

AR-Sanad 280K dataset contains sanads with identified narrators. The dataset could be used to train models to identify narrators in Hadiths. [v1 Paper](https://www.mdpi.com/2078-2489/13/2/55), [v2 paper](https://link.springer.com/article/10.1007/s00521-024-10194-2)

### Large Dataset
The large dataset has 279,625 artificial sanads in the training and validation sets and could be used to identify 18,298 narrators. It also has a test set of 27,056 real sanads
from the 6 most famous hadith books.

### Lite dataset
The lite dataset has 39,147 artificial sanads in the training and validation sets and could be used to identify 2,222 narrators.

### v2
An updated version of the artificial sanads in the large dataset for more details refer to [this](https://link.springer.com/article/10.1007/s00521-024-10194-2).

### Narrators Data
Narrators' information include: Full names, namings (appearance forms), Shuhra, Rank by Ibn Hajar, Birth date, etc.

### Models
We provide AraBERT models trained on the large dataset. 


Frozen AraBERT: we train the classification layer only.

Tuned AraBERT: We tune the weights of both the BERT model and the classification layer.


We also provide code to test the models on our test set. In "EvaluateOnTest.ipynb".
