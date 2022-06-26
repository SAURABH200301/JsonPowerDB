# JsonPowerDB
### This Small Project was about how basic of Json PowerDB(JPDB) and how it is used for CRUD operations. 

Documentation Link(http://login2explore.com/jpdb/docs.html)

# About JsonPowerDB:

JsonPowerDB is a Real-time, High Performance, Lightweight and Simple to Use, Rest API based Multi-mode DBMS. JsonPowerDB has ready to use API for Json document DB, RDBMS, Key-value DB, GeoSpatial DB and Time Series DB functionality. JPDB supports and advocates for true serverless and pluggable API development.

# Benefits of using JsonPowerDB
 - Simplest way to retrieve data in a JSON format.
 - Schema-free, Simple to use, Nimble and In-Memory database.
 - It is built on top of one of the fastest and real-time data indexing engine - PowerIndeX.
 - It is low level (raw) form of data and is also human readable.
 - It helps developers in faster coding, in-turn reduces development cost.
 - Minimize the complexity, maximize thr data processing performance.

# Technology Futuristic
- Fills gap from database to big-data.
- Minimize Total Cost of Ownership

# How JPDB is simple that other DBs

Here is the example of simplest JPDB API PUT as example:
```
{
    "token": "-1935843913xxxxxxxxxxxxxxxxx",
    "cmd": "PUT",
    "dbName": "Student",
    "rel": "Student-Rel",
    "jsonStr": {
        "id": "1",
        "name": "Soniya",
        "email": "soniya@gmail.com",
        "mobileno": "9967825671"
    }
}
```

- **token** here is the connection key generated by JPDb.
- **cmd** is the command here it is *PUT*
- **dbName** as it suggest is the name of your DB
- **rel** refers to the Relation like row in the SQL database
- **jsonstr** is the json formatted data 



![Screenshot (184)](https://user-images.githubusercontent.com/80611268/175801473-0e0b698e-f2c4-4d20-9c9c-90f413eae04b.png)

![Screenshot (183)](https://user-images.githubusercontent.com/80611268/175801492-ba5cdd1b-9d05-4258-89b1-7a0c1bca8f1f.png)


