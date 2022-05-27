# BigData project

>Final project for the "Big Data" course of Master degree in computer engineering at University of Verona: "Queries on the dataset inherent to the Verona Cards and the
weather station data using PySpark".
>

## Prerequisites:

- Spark >= 3.2.1, pre-build for Apache Hadoop 3.2 available here https://spark.apache.org/downloads.html
- Python 3

- [x] Have downloaded Verona Card and Weather available at https://univr-my.sharepoint.com/:f:/g/personal/anna_dallavecchia_studenti_univr_it/Em2lYrG7qJBAk2nYYvo305wBq_MYmPok73RbXFSK0AJwrw?e=HqmrCl

## Verona Card Dataset
|  | label	| description	|
|-----|-----|-------------------|
|0	| attivazione	| activation's date of Verona card	|
|1	| id_vc	| Verona identifier	|
|2	| istante	| date and hour of Verona card's use|
|3  | profilo | Verona Card validity (24, 48, 72 hours)|
|4	| poi	| Point of interest visited	|
|5	| classid	| identifier of the usage of Verona Card	|

## Weather Dataset 

|  | label	| description	|
|-----|-----|-------------------|
|0	| data	| date	|
|1	| ora	| hour	|
|2	| t	| temperature in °C |
|3  | ur | - |
|4	| pr	| atmospheric pressure	|
|5	| wind	| wind in km/h	|
|6	| wind_dir	| wind's direction	|
|7	| rain	| rain's millimeters	|
|8	| dp	| -	|
|9	| idstazione | identifier of the weather station	|
