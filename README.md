# ConDBnector

The Python interface to all of the popular and known databases. Single library that offers connection to all kinds. That in fact, a singleton pattern with a connection to the most used and popular dbms. E.g. OracleDB, MySQL, Microsoft SQLServer, Postgresql, DynamoDB, MariaDB, Splunk, Solr and others.

The importance of such project reflect for example when a software use more than one DB.

### Current Situation
Right now the project only supports connection to MySQL. The long term goal is that the library will support the connection of all 355 DB engines from the following rank - https://db-engines.com/en/ranking.
Since the above list contains lots of DBs and most of them are not popular, implementation progress will go from top to buttom.

The specification of the DB should be like in the following example:
```python
conn = ConDBnector.connect(host='localhost', port=3306, user='root', passwd='', db='mysql')
```
