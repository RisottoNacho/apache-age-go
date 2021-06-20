# apache-age-go

Go driver support for [Apache AGE](https://age.apache.org/), graph extention for PostgreSQL.

### Go get & gomod
* over Go 1.16
* This module runs on golang standard api [database/sql](https://golang.org/pkg/database/sql/) and [antlr4-python3](https://github.com/antlr/antlr4/tree/master/runtime/Go/antlr)

```(shell)
go get github.com/rhizome-ai/apache-age-go
```
#### gomod
```(go)
require  github.com/rhizome-ai/apache-age-go {version}
 
```
Check [latest version](https://github.com/rhizome-ai/apache-age-go/releases)

### For more information about [Apache AGE](https://age.apache.org/)
* Apache Incubator Age : https://age.apache.org/
* Github : https://github.com/apache/incubator-age
* Document : https://age.incubator.apache.org/docs/

### Check AGE loaded on your PostgreSQL
Connect to your containerized Postgres instance and then run the following commands:
```(sql)
# psql 
CREATE EXTENSION age;
LOAD 'age';
SET search_path = ag_catalog, "$user", public;
```

### Usage

### License
Apache-2.0 License