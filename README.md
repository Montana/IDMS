# IDMS
Identity management system patch for the DB driver for Gilead Sciences, written in PHP by Montana Mendy. This is to make sure the quality of data is at it's finest when logged. IDMS does this by by retrieving identity information from the connected data sources and storing the information in the connector space as connector space objects. 

## Requirments 

- Apache CouchDB - for single node database and clusters
- MySQL with memcache, for scalability. Cannot use Redis via amount of data Gilead produces
- PHP 7, with GD2 image libraries
