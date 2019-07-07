# MinSizeKmeans_GEO
Execution of Behrouz Babaki's implementation of Kmeans into GeoData https://github.com/Behrouz-Babaki/MinSizeKmeans


## Code on Jupyter Notebook with Python3:

```
!wget -O MinSizeKmeans.zip https://github.com/Behrouz-Babaki/MinSizeKmeans/archive/master.zip
!unzip MinSizeKmeans.zip
!cp -r MinSizeKmeans-master/minsize_kmeans/. .
!pip install pulp
```

```
import pulp
%run minmax_kmeans.py end_real.data 3 2 4 -n 3 -o mm.out
```

https://colab.research.google.com/drive/17KZUCeoPFRXS8rprQyniKo-oeaN4Ek1Z


Exemplo de aplicação da API do google maps para multiplas paradas

https://codesandbox.io/s/old-tree-2ij2x
