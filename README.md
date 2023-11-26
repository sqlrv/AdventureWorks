# AdventureWorks
Postgres implementation of AdventureWorks

The repository corresponds with the "Migrating AdventureWorks to Postgres" series on simpletalk.com.

After installing Postgres, extract the contents of pg_install_awdb.zip into c:\temp\awdb. To install, perform the following command:

	psql -d “AdventureWorks” -u postgres -f pg_install_awdb.sql

You may follow pg_install_awdb with "_01", "_02", etc. for a series section-specific build.
