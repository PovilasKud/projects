## CALL CENTER APPLICATION
Main objectives of the project:
  - Make sales department work more efficient;
  - Gather data for analysis;
  - Increase sales conversion rate;

## ARCHITECTURE
![alt text](https://image.ibb.co/mzgthc/architecture.jpg "Architect")

## TECHNOLOGIES USED
SCRAPY - For scraping source of company leads.

PYTESSERACT - For reading telephone numbers from image (Lead source protected telephone numbers by displaying them as images)

DJANGO REST FRAMEWORK - Creating an API for Desktop Application <> Database communication.

DJANGO - Used Django wonderful admin interface for managing Staff members and other data.

PyQT - For developing Desktop Application.

CELERY - For managing some background tasks.

REDIS - For celery as message broker.

POSTGRESQL - For database engine.

UBUNTU - API, Scraping and Django Admin deployed on Ubuntu server.

SUPERVISOR - For managing services.

KALBU.LT IP TELEPHONY API - For making phone calls from desktop application.

## DESKTOP APPLICATION
Call Center desktop application features:
- Filtering lead database;
- Sending emails;
- Making calls to leads;

![alt text](https://preview.ibb.co/hjijoH/call1.png "Architect")
![alt text](https://preview.ibb.co/edkKNc/call2.png "Architect")
![alt text](https://preview.ibb.co/hjU2ax/call3.png "Architect")
![alt text](https://preview.ibb.co/jwRhax/call4.png "Architect")
