# hello-world

create external table airline_ids (id string, desc string)
ROW FORMAT DELIMITED
FIELDS TERMINATED BY ','
ESCAPED BY '\\'
LINES TERMINATED BY '\n'
STORED AS TEXTFILE 
location 's3a://arcadia-sample-data/airlineinfo';
