# Automated preprocessing pandas - Data Science
Dataframe review with Pandas.


These two algorithms will help you to automate preprocessing on dataset.  <br/>
Ces deux algorithmes vont vous permettre d'automatiser le preprocessing sur une colonne puis sur un dataset complet.
<br/>

## Example of ouput with a column of a dataset ( whatever the type )

    In[1]: column_info(data['IMDB'])

     ● données:
    0    7.8
    1    7.1
    2    7.8
    3    5.4
    4    5.1
    Name: IMDB, dtype: float64
    -------------------------
     ● type de données : <class 'pandas.core.series.Series'>
    -------------------------
     ● moyenne : 6.736986301369863
    -------------------------
     ● variance : 0.9587357838629629
    -------------------------
     ● maximum : 8.6
    -------------------------
     ● minimum : 4.0
    -------------------------
     ● valeur les plus présentes: 7.2 : 10 fois , 7.8 : 9 fois
    -------------------------
     ● valeurs manquantes: 0
    -------------------------
     ● longueur: 146
    -------------------------
     ● nombre de valeurs distinctes non NaN: 41
    -------------------------


## Example of ouput with an entire dataset ( whatever the type ) 
<br/> the second parameter is the name of the index column
<br/>

    In[1]: dataset_info(data, 'FILM')
    
     ● taille: (146, 22)
    -------------------------
     ● types de données: float64    15
    int64       6
    object      1
    dtype: int64
    -------------------------
     ● valeurs manquantes: 0
    -------------------------
     ● nombre de valeurs: 3212
    -------------------------
     ● variance maximum pour la colonne : IMDB_user_vote_count
       avec une variance de : 67406.50917130285
    -------------------------
    
<br/>

### With this following window in html 
<br/>
This plot needs Plotly

<br/>   

        pip install plotly

documentation : <https://plotly.com/python/>
<br/>
![feature_max_evolution](https://user-images.githubusercontent.com/63207451/95136225-03fe7b00-0766-11eb-99af-766deea9f2e2.png)

<br/>

<br/>

<p align="center">
  <a href="https://github.com/antonin-lfv" class="fancybox" ><img src="https://user-images.githubusercontent.com/63207451/97302854-e484da80-1859-11eb-9374-5b319ca51197.png" title="GitHub" width="40" height="40"></a>
  <a href="https://www.linkedin.com/in/antonin-lefevre-565b8b141" class="fancybox" ><img src="https://user-images.githubusercontent.com/63207451/97303444-b2c04380-185a-11eb-8cfc-864c33a64e4b.png" title="LinkedIn" width="40" height="40"></a>
  <a href="mailto:antoninlefevre45@icloud.com" class="fancybox" ><img src="https://user-images.githubusercontent.com/63207451/97303543-cec3e500-185a-11eb-8adc-c1364e2054a9.png" title="Mail" width="40" height="40"></a>
</p>
