# sleepy-catalogue

Proof of concept OGC API Records Crawable catalog

It uses the minio scalable storage as a backend.

To test just run:

`docker-compose up -d`

Available enpoints are:

http://localhost:9000/crawlable_catalogue/collections.json

http://localhost:9000/crawlable_catalogue/masked_rec/collection.json

http://localhost:9000/crawlable_catalogue/masked_rec/record.json


## Note

Make sure that the bucket is public, in order to enable the endpoints.

