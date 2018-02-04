# README

Working rails app on elastic beanstalk. Just be sure to create an RDS database and input necessary environment variables:

- RDS_HOSTNAME – The hostname of the DB instance.

- Amazon RDS console label – Endpoint (this is the hostname)

- RDS_PORT – The port on which the DB instance accepts connections. The default value varies between DB engines.

- Amazon RDS console label – Port

- RDS_DB_NAME – The database name, ebdb.

- Amazon RDS console label – DB Name

- RDS_USERNAME – The user name that you configured for your database.

- Amazon RDS console label – Username

- RDS_PASSWORD – The password that you configured for your database.

- SECRET_KEY_BASE - necessary for rails app