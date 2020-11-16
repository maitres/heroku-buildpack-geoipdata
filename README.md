# heroku-buildpack-geoipdata
a simple Heroku buildpack that downloads a geo ip data database file to go along with your build

## heroku vars
AWS_BUCKET - your s3 bucket  
GEOIP_DB_PATH - Path to geoip db file in s3, the same path will be created in the project