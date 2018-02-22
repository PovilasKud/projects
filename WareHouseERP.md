
## WareHouse ERP for US Bike parts company
I have build an cloud application for US company which is selling Bike parts on Ebay. The problem they had was that they could not track their sales on ebay and on the spot. There was times that they sold item on the spot and then again on the ebay or vise vesra.

My provided solution was a cloud application which had all there warehouse synchronized with Ebay with Ebay API. Periodic requests made to Ebay API using Celery background tasks. Beside this main feature there was also a competitor tracking on ebay, statistics, exports and other features.

## TECHNOLOGIES USED

DJANGO - Backend engine. 

CELERY - For managing periodic background tasks.

APIs - Ebay API for warehouse sync.

REDIS - For celery as message broker.

POSTGRESQL - For database engine.

Digital Ocean Droplet - project deployed on Ubuntu server.

SUPERVISOR - For managing services.
