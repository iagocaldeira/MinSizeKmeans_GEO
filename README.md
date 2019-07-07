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


### Exemplo de aplicação da API do google maps para multiplas paradas

https://codesandbox.io/s/old-tree-2ij2x

### Resultado da classificação

* Carro 1:

  * R. Eurita, 768 - santa tereza
  * Rua Cairu 125
  * Avenida Cachoeirinha, 281 - Santa Cruz

* Carro 2:
  * R. Júlia lina, 101 - Frei Eustáquio
  * Rua firmino costa 185, jardim montanhês

* Carro 3:
  * Rua Opala, 110, Cruzeiro
  * Rua Mestre Luiz 46 São Pedro Bh


### Links das rotas criadas pelo agrupamento de endereços para o destino no Mineirão


https://www.google.com/maps/dir/R.+Eurita,+768+-+Santa+Tereza,+Belo+Horizonte+-+MG,+31010-210/Rua+Cair%C3%BA,+125+-+Conc%C3%B3rdia,+Belo+Horizonte+-+MG,+31110-630,+Brasil/Avenida+Cachoeirinha,+281+-+Santa+Cruz,+Belo+Horizonte+-+MG/Mineir%C3%A3o+-+Avenida+Ant%C3%B4nio+Abrah%C3%A3o+Caram+-+S%C3%A3o+Jos%C3%A9,+Belo+Horizonte+-+MG/@-19.891782,-43.9813728,13z/data=!3m2!4b1!5s0xa690f74c891431:0x1e3146978ad2501b!4m26!4m25!1m5!1m1!1s0xa699880334565f:0x62a351ffb9cf8d10!2m2!1d-43.9156457!2d-19.9178654!1m5!1m1!1s0xa69a0434c2093b:0x1eb81f0913f62ccd!2m2!1d-43.937893!2d-19.903806!1m5!1m1!1s0xa69a77a6dada61:0x21672ddc9803300b!2m2!1d-43.9414782!2d-19.8829935!1m5!1m1!1s0xa690f71348ff6d:0x35b9453242d27588!2m2!1d-43.9711315!2d-19.865867!3e0


https://www.google.com/maps/dir/R.+J%C3%BAlia+Lina,+101+-+Frei+Eustaquio,+Belo+Horizonte+-+MG/Rua+Firmino+Costa,+185+-+Jardim+Montanh%C3%AAs,+Belo+Horizonte+-+MG/Mineir%C3%A3o+-+Avenida+Ant%C3%B4nio+Abrah%C3%A3o+Caram+-+S%C3%A3o+Jos%C3%A9,+Belo+Horizonte+-+MG/@-19.8868893,-44.0037383,14z/data=!3m2!4b1!5s0xa690f74c891431:0x1e3146978ad2501b!4m20!4m19!1m5!1m1!1s0xa696beebfa9f41:0x226fb100a637fafa!2m2!1d-44.004178!2d-19.9058556!1m5!1m1!1s0xa69727fe0c6fdb:0x74f07cac974859af!2m2!1d-43.9815422!2d-19.9067813!1m5!1m1!1s0xa690f71348ff6d:0x35b9453242d27588!2m2!1d-43.9711315!2d-19.865867!3e0


https://www.google.com/maps/dir/Rua+Opala,+110+-+Cruzeiro,+Belo+Horizonte+-+MG/Rua+Mestre+Luiz,+46+-+S%C3%A3o+Pedro,+Belo+Horizonte+-+MG/Mineir%C3%A3o+-+Avenida+Ant%C3%B4nio+Abrah%C3%A3o+Caram+-+S%C3%A3o+Jos%C3%A9,+Belo+Horizonte+-+MG/@-19.9037933,-43.9909137,13z/data=!3m1!5s0xa690f74c891431:0x1e3146978ad2501b!4m20!4m19!1m5!1m1!1s0xa699c8518b9f27:0x73073556e9262eb!2m2!1d-43.9261273!2d-19.9445865!1m5!1m1!1s0xa699d1a68ff61b:0x947441ef6203a253!2m2!1d-43.936225!2d-19.942578!1m5!1m1!1s0xa690f71348ff6d:0x35b9453242d27588!2m2!1d-43.9711315!2d-19.865867!3e0
