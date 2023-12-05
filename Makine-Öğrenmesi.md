### VERİ OKUMA ###
```
import pandas as pd  
data = pd.read_csv('veriler.csv' , sep=',')  
```
### VERİ KOPYALAMA ###
```
df=data.copy()  
```

### EKSİK VERİ SETİNİ TAMAMLAMA ###  
```
from sklearn.impute import SimpleImputer  
imputer = SimpleImputer(missimg_values=np.nan, strategy='mean')  //Sütunda bulunan verilerin ortalamasını alarak doldur
Yas = 
```


