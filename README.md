To start the WhatsApp Business API Client with 1 database container, 1 Webapp container and 1 Coreapp container, run:
docker-compose up -dExample output:
Creating volume "biz_whatsappMedia" with local driver
Creating volume "biz_mysqlData" with local driver
Creating biz_db_1 ... done
Creating biz_wacore_1 ... done
Creating biz_waweb_1  ... done
Check that all containers have an UP state by running:
docker-compose ps By default, the Webapp container will be running on port 9090 and the database container will be running on port 33060. 
