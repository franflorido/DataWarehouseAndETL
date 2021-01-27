# DataWarehouseAndETL

In this repository you will find a data warehouse design and a ETL proces using basically pentaho and MySQL.

In this case studio what we wants is to analyce which flights the frequent passengers of the company choose, what airplanes they use to travel, what rates they pay, how they earn and redeem their points, what is the duration of your stays at destination, etc.

To perform this excercice you will find the CSV´s files of the case of study wich are:

airport.csv -- Constains information about the airports.

airport_city_state.csv -- Contains information abous the states of the airports.

channel.csv -- Contains information about the type of payment available.

customer.csv -- Contains information about the customers in our database.

fare.csv -- Contains information about the type of fare for the flights.

flight.csv -- Contains information about the flights registered.

frequentfliyer.csv -- Contains infromation about the information of all our frequent flyers, like the flights they take, the fare they use etc..

In order to do this exercice we are going to follow four main steps.


Step number 1:

In this step we are going to design the multidimensional model for our data warehouse, having in mind the especifications in the Case study.pdf and the CSV available.

We are going to create the datawarehouse in MySql.

You can find the result of teh design in Design.pdf

Step number 2:

In this step we are going to implement the datawarehouse in MySQl and we are going to design and implement the OLAP model in pentahoo mondrian workbench.

Yuo can find the explanation in OLAP.pdf and the tables File for the data warehouse in databasemodel.sql.txt and the schema for the OLAP model in Schema3.xml

Step number 3:

We are going to perform the data integration process with pentahoo data-integration.

You can find the explanation in data-integration.pdf

Step number 4:

We are going to make some easy visualizations of our OLAP model with the data integrated using pentahoo-server.

You can find the explanation in visualization.pdf


Inthis step we are going 


