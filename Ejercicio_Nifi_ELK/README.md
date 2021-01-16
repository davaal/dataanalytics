dataanalytics_EDEM

## Ejercicio_NIFI_ELK

#### 1. Exploramos los datos y copiamos link de la API.
     https://data.cityofnewyork.us/resource/erm2-nwe9.json 
  
#### 2.Levantamos Docker (docker-compose up -d) con Kibana, Elasticsearch y Nifi
  
#### 3. Nifi
    InvokeHTTP
    SplitJson
    PutElasticsearchHTTP
  
#### 4. Kibana
    Index pattern
    Reindex 
    Geo-points
   
