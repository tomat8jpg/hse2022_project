# hse2022_project

Ссылка на коллаб: https://colab.research.google.com/drive/1OlXW54U6pglytdSzLrwvx5x574kZYRtY?usp=sharing  
# Сводная таблица. 
| Название вида | H. aestuarii | Н. beimenensis | H. chromatireducens | H. elongatae | H. socia |
| :---: | :---: | :---: | :---: | :---: | :---: |
| количество ДНК носителей в геноме | 1 | 1 | 1 | 1 | 1 |
| общая длина этих последовательностей | 3543891 | 4053030 | 3973651 | 4061825 | 4753299 |
| количество аннотированных генов | 3341 | 3799 | 3776 | 3802 | 4534 |
| доля аннотированных генов в геноме | 90.33 | 89.83 | 88.83 | 90.34 | 90.04 |
| кол-во участков с zh-score >500 | 26103 | 24540 | 19579 | 26136 | 40009 |
| общая длина участков с zh-score >500 | 112006 | 110183 | 86786 | 112573 | 166561 |  

# Строим гистограммы значений zh-score для всех геномов, полученных с помощью Zhunt  
![image](https://user-images.githubusercontent.com/60805733/173428127-f96d16fa-9d71-4f45-86ee-9a0e1c95c326.png)
![image](https://user-images.githubusercontent.com/60805733/173428158-cdca809a-7f96-49d8-82ab-e10bfc7f4fe2.png)
![image](https://user-images.githubusercontent.com/60805733/173428220-1f1b1700-3228-49e3-8cb4-26396ec71342.png)
![image](https://user-images.githubusercontent.com/60805733/173428237-d20ba9ef-1ceb-4080-92cf-76c65a933835.png)
![image](https://user-images.githubusercontent.com/60805733/173428266-f94027af-4ec5-49a7-8d36-b4939b42e059.png)


# Информация по полученным гомологичным кластерам
Всего получилось 1763 кластеров, после отбора кластеров генов, которые имеются у всех 5 организмов осталось 11  
Гистограмма кластеров по количеству разных геномов в кластере:  
![image](https://user-images.githubusercontent.com/60805733/173427226-4900b2d3-5123-457c-b14e-10eebed48cbb.png)


# Таблица с информацией по выбранным кластерам  

| Кластер | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| сколько генов в кластере | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 |
| функция этих генов | lysine exporter | L,D-transpeptidase | GlsB/YeaQ/YmgE | CDP-alcohol phosphatidyltransferase | hypothetical protein | efflux RND transporter periplasmic adaptor subunit | aminoacyl-tRNA hydrolase | acyl-CoA dehydrogenase | exodeoxyribonuclease V subunit alpha | peroxide stress protein YaaA |

# Таблицы по каждому кластеру:
| **Кластер 1** |  H. aestuarii | Н. beimenensis | H. chromatireducens | H. elongatae | H. socia |
| :---: | :---: | :---: | :---: | :---: | :---: |
| расположение Z-DNA относительно гена, вошедшего в данный кластер | upstream | downstream | downstream | upstream | downstream |
| Z-DNA score | 884 | 701 | 2752 | 2173 | 1139 |

| **Кластер 2** |  H. aestuarii | Н. beimenensis | H. chromatireducens | H. elongatae | H. socia |
| :---: | :---: | :---: | :---: | :---: | :---: |
| расположение Z-DNA относительно гена, вошедшего в данный кластер | downstream | downstream | upstream | upstream | downstream |
| Z-DNA score | 735 | 981 | 884 | 844 | 2752 |

| **Кластер 3** |  H. aestuarii | Н. beimenensis | H. chromatireducens | H. elongatae | H. socia |
| :---: | :---: | :---: | :---: | :---: | :---: |
| расположение Z-DNA относительно гена, вошедшего в данный кластер | downstream | upstream | upstream | downstream | upstream |
| Z-DNA score | 908 | 1117 | 908 | 1403 | 981 |

| **Кластер 4** |  H. aestuarii | Н. beimenensis | H. chromatireducens | H. elongatae | H. socia |
| :---: | :---: | :---: | :---: | :---: | :---: |
| расположение Z-DNA относительно гена, вошедшего в данный кластер | upstream | downstream | downstream | upstream | downstream |
| Z-DNA score | 884 | 884 | 884 | 884 | 1677 |

| **Кластер 5** |  H. aestuarii | Н. beimenensis | H. chromatireducens | H. elongatae | H. socia |
| :---: | :---: | :---: | :---: | :---: | :---: |
| расположение Z-DNA относительно гена, вошедшего в данный кластер | upstream | upstream | downstream | downstream | upstream |
| Z-DNA score | 3429 | 9301 | 1848 | 1281 | 1821 |

| **Кластер 6** |  H. aestuarii | Н. beimenensis | H. chromatireducens | H. elongatae | H. socia |
| :---: | :---: | :---: | :---: | :---: | :---: |
| расположение Z-DNA относительно гена, вошедшего в данный кластер | downstream | downstream | upstream | upstream | downstream |
| Z-DNA score | 4546 | 2766 | 818 | 3738 | 1302 |

| **Кластер 7** |  H. aestuarii | Н. beimenensis | H. chromatireducens | H. elongatae | H. socia |
| :---: | :---: | :---: | :---: | :---: | :---: |
| расположение Z-DNA относительно гена, вошедшего в данный кластер | upstream | upstream | upstream | downstream | downstream |
| Z-DNA score | 2752 | 507 | 1801 | 908 | 28780 |

| **Кластер 8** |  H. aestuarii | Н. beimenensis | H. chromatireducens | H. elongatae | H. socia |
| :---: | :---: | :---: | :---: | :---: | :---: |
| расположение Z-DNA относительно гена, вошедшего в данный кластер | upstream | upstream | downstream | upstream | upstream |
| Z-DNA score | 884 | 571 | 908 | 13714 | 884 |

| **Кластер 9** |  H. aestuarii | Н. beimenensis | H. chromatireducens | H. elongatae | H. socia |
| :---: | :---: | :---: | :---: | :---: | :---: |
| расположение Z-DNA относительно гена, вошедшего в данный кластер | upstream | downstream | upstream | upstream | upstream |
| Z-DNA score | 8486 | 1220 | 3429 | 981 | 1229 |

| **Кластер 10** |  H. aestuarii | Н. beimenensis | H. chromatireducens | H. elongatae | H. socia |
| :---: | :---: | :---: | :---: | :---: | :---: |
| расположение Z-DNA относительно гена, вошедшего в данный кластер | downstream | downstream | downstream | upstream | downstream |
| Z-DNA score | 651 | 981 | 784 | 1738 | 3429 |

Множественное белковое выравнивание для каждого выбранного кластера лежит по [ссылке](https://github.com/tomat8jpg/hse2022_project/tree/main/clustalW)


Визуализация расположения участков Z-DNA для каждого выбранного кластера  
![image](https://user-images.githubusercontent.com/60805733/173441966-18538f96-b2ea-465e-a538-a25c65fd40be.png)
![image](https://user-images.githubusercontent.com/60805733/173441983-a5865c3a-5d4e-4c08-8893-de7986994e87.png)
![image](https://user-images.githubusercontent.com/60805733/173442030-cc4ce2c8-b15c-4367-a4b8-3e9f43b81edf.png)
![image](https://user-images.githubusercontent.com/60805733/173442100-9bf53a33-2b96-492c-a47b-72589acbaef4.png)
![image](https://user-images.githubusercontent.com/60805733/173442134-c297cb80-ebb4-4861-bbd8-78adefb313da.png)
![image](https://user-images.githubusercontent.com/60805733/173442194-1d00acb4-a5e4-42ac-99a4-58c5ad89a3a1.png)
![image](https://user-images.githubusercontent.com/60805733/173442218-e6460945-4b6e-40dc-ad87-d3f00366b026.png)
![image](https://user-images.githubusercontent.com/60805733/173442248-a8795b90-e6cd-4b00-b3e1-e0895e20a3f1.png)
![image](https://user-images.githubusercontent.com/60805733/173442295-07977196-f959-4195-98be-c8580b7e23eb.png)
![image](https://user-images.githubusercontent.com/60805733/173442331-4727b4b7-868a-401f-ad43-46a1259dd691.png)

