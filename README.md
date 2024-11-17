How to run:
1) node-red in terminal and localhost:1880 -> import the project
2) Create db and csv file by entering a local path on the computer, and create the tables
3) Run historical data
4) Run current weather, forecast, and percentage loss or set them to run automatically.
5) For dashboard localhost:1880/ui
6) For RabbitMQ in node-red broker needs username and password, login to localhost:15672 with username, password and create 5 queues bindings with amq.direct, user1.weather, user2.weather and losspercentagelow.weather, losspercentagemedium.weather, losspercentagehigh.weather. Execution of timestamps with strict sequence of the json message structure for successful results and correct routingKey to receive the messages.
