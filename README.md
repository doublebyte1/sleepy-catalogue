# sleepy-catalogue

Proof of concept OGC API Records Crawable catalog

It uses the minio scalable storage as a backend.

To test just run

`docker-compose up -d`

Available enpoints are:

http://172.30.0.2:9000/crawlable_catalogue/collections.json

http://172.30.0.2:9000/crawlable_catalogue/masked_rec/collection.json

http://172.30.0.2:9000/crawlable_catalogue/masked_rec/record.json






