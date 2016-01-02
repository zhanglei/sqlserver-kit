# SQL Server Utilities
Useful SQL Server utilities

Source link:
 - [Microsoft's Log Parser Utility: Swell ETL](https://www.simple-talk.com/sql/sql-tools/microsofts-log-parser-utility-swell-etl/) by Robert Sheldon
 - [SQL Server tablediff utility](https://www.simple-talk.com/sql/sql-tools/sql-server-tablediff-utility/) by Robert Sheldon
 - [Seven SQL Server Under-Used](https://www.simple-talk.com/sql/database-administration/seven-sql-server-under-used-utilities/) by Robert Sheldon


| Name                                                      | Official/Download page       | Release Date | Author      | Free version | Paid/Price |
|-----------------------------------------------------------|------------------------------|------------- | ------------| ------------ | -----------|
| [tablediff Utility](#tablediff-utility)                   | [tablediff Utility]          | -            | Microsoft   | Yes          | No         |
| [Microsoft Log Parser](#microsoft-log-parser)             | [Microsoft Log Parser]       | -            | Microsoft   | Yes          | No         |
| [Diskspd](#diskspd)                                       | [Diskspd]                    | 2015-12-14   | Microsoft   | Yes          | No         |
| [HammerDB](#hammerdb)                                     | [HammerDB]                   | 2015-05-04   | Open Source | Yes          | No         |
| [dta Utility](#dta-utility)                               | [dta Utility]                | -            | Microsoft   | Yes          | No         |
| [osql Utility](#osql-utility)                             | [osql Utility]               | -            | Microsoft   | Yes          | No         |
| [sqldiag Utility](#sqldiag-utility)                       | [sqldiag Utility]            | -            | Microsoft   | Yes          | No         |
| [sqldumper Utility](#sqldumper-utility)                   | [sqldumper Utility]          | -            | Microsoft   | Yes          | No         |
| [SqlLocalDB Utility](#sqllocaldb-utility)                 | [SqlLocalDB Utility]         | -            | Microsoft   | Yes          | No         |
| [sqllogship Utility](#sqllogship-utility)                 | [sqllogship Utility]         | -            | Microsoft   | Yes          | No         |
| [sqlservr Application](#sqlservr-application)             | [sqlservr Application]       | -            | Microsoft   | Yes          | No         |
| [SQL XEvent Profiler](#sql-xevent-profiler)               | [SQL XEvent Profiler]        | 2014-03-14   | Idera       | Yes          | No         |
| [DLM Dashboard](#dlm-dashboard)                           | [DLM Dashboard]              | 2015-12-16   | Red Gate    | Yes          | No         |
| [SQL DBA Bundle](#sql-dba-bundle)                         | [SQL DBA Bundle]             | 2015-12-16   | Red Gate    | No           | Yes/$2640  |
| [SQL Check](#sql-check)                                   | [SQL Check]                  | 2015-09-24   | Idera       | Yes          | No         |
| [SQL Fragmentation Analyzer](#sql-fragmentation-analyzer) | [SQL Fragmentation Analyzer] | 2015-06-24   | Idera       | Yes          | No         |
| [SQL Heat Map](#sql-heat-map)                             | [SQL Heat Map]               | 2015-12-07   | Idera       | Yes          | No         |
| [SQL Hekaton Memory Check](#sql-hecaton-memory-check)     | [SQL Hekaton Memory Check]   | 2015-06-10   | Idera       | Yes          | No         |
| [SQL Page Viewer](#sql-page-viewer)                       | [SQL Page Viewer]            | 2014-08-25   | Idera       | Yes          | No         |
| [SQL Update Statistics](#sql-update-statistics)           | [SQL Update Statistics]      | 2015-12-14   | Idera       | Yes          | No         |
| [SQL Statistics Aggregator](#sql-statistics-aggregator)   | [SQL Statistics Aggregator]  | 2015-05-18   | Idera       | Yes          | No         |
| [SQL Backup Status Reporter](#sql-backup-status-reporter) | [SQL Backup Status Reporter] | 2015-08-07   | Idera       | Yes          | No         |
| [SQL Integrity Check](#sql-integrity-check)               | [SQL Integrity Check]        | 2013-08-26   | Idera       | Yes          | No         |
| [SQL Job Manager](#sql-job-manager)                       | [SQL Job Manager]            | 2012-03-19   | Idera       | Yes          | No         |
| [Azure SQL Database Backup](#azure-sql-database-backup)   | [Azure SQL Database Backup]  | 2012-10-02   | Idera       | Yes          | No         |
| [SQL Column Search](#sql-column-search)                   | [SQL Column Search]          | 2015-11-17   | Idera       | Yes          | No         |
| [SQL Permissions Extractor](#sql-permissions-extractor)   | [SQL Permissions Extractor]  | 2015-08-07   | Idera       | Yes          | No         |


## Microsoft Log Parser
Log parser is a powerful, versatile tool that provides universal query access to text-based data such as log files,<br />
XML files and CSV files, as well as key data sources on the Windows operating system such as the Event Log, the Registry, the file system, and Active Directory. 


## tablediff Utility
The tablediff utility is used to compare the data in two tables for non-convergence, and is particularly useful for troubleshooting non-convergence<br />
in a replication topology. This utility can be used from the command prompt or in a batch file to perform the following tasks:
 - A row by row comparison between a source table in an instance of Microsoft SQL Server acting as a replication Publisher and the destination table at one or more instances of SQL Server acting as replication Subscribers.
 - Perform a fast comparison by only comparing row counts and schema.
 - Perform column-level comparisons.
 - Generate a Transact-SQL script to fix discrepancies at the destination server to bring the source and destination tables into convergence.
 - Log results to an output file or into a table in the destination database.


## Diskspd
DISKSPD is a storage load generator / performance test tool from the Windows/Windows Server and Cloud Server Infrastructure Engineering teams.

Compilation is supported with Visual Studio and Visual Studio Express. Use the Visual Studio solution file inside the diskspd_vs2013 directory.


## HammerDB
HammerDB is an open source database load testing and benchmarking tool for Oracle, SQL Server, DB2, TimesTen, PostgreSQL, Greenplum, Postgres Plus Advanced Server, MySQL,  Redis and Trafodion SQL on Hadoop.


## dta Utility
Capture performance and usage data about your Microsoft SQL Server 2005+ databases to inform insights and improve troubleshooting.

Key real-time metrics provide an overview of your databases and detailed measurements about memory usage, connections, network I/O, and file I/O.


## osql Utility
The osql utility allows you to enter Transact-SQL statements, system procedures, and script files.<br />
This utility uses ODBC to communicate with the server.


## sqldiag Utility
The SQLdiag utility is a general purpose diagnostics collection utility that can be run as a console application or as a service.<br />
You can use SQLdiag to collect logs and data files from SQL Server and other types of servers, and use it to monitor your servers over time<br />
or troubleshoot specific problems with your servers.<br />
SQLdiag is intended to expedite and simplify diagnostic information gathering for Microsoft Customer Support Services.


## sqldumper Utility
ou can use the Sqldumper.exe utility to generate a dump file on demand for any Microsoft Windows application.<br />
For example, you can generate a dump file for debugging an application problem when a computer that is running SQL Server 2005,<br />
Microsoft SQL Server 2008, Microsoft SQL Server 2008 R2, or Microsoft SQL Server 2012 is not responding to user requests.<br />
A dump file can be a mini-dump file, a full dump file, or a filtered dump file.


## SqlLocalDB Utility
SqlLocalDB lets you create, delete, start, stop, and perform a number of other related tasks on an instance of SQL Server 2012 Express LocalDB,<br />
an execution mode of SQL Server Express that’s targeted at developers. A LocalDB instance uses a minimal set of files to start the database engine.


## sqllogship Utility
The sqllogship application performs a backup, copy, or restore operation and associated clean-up tasks for a log shipping configuration.<br />
The operation is performed on a specific instance of Microsoft SQL Server for a specific database.


## sqlservr Application
The sqlservr application starts, stops, pauses, and continues an instance of Microsoft SQL Server from a command prompt.


## SQL XEvent Profiler
Idera’s SQL XEvent Profiler emulates the functionality and simplicity of SQL Server Profiler, letting you quickly view data from SQL events<br />
and see what's happening on the server. Plus, it leverages SQL Extended Events (XEvents) as the backing technology — making it more efficient than SQL Trace.


## DLM Dashboard
DLM Dashboard tracks your database schemas and alerts you when they change.<br />
As a SQL Server user, you want to make sure all your databases are in the right state.<br />
DLM Dashboard monitors up to 50 of your databases, and sends you an email alert as soon as your databases start to drift,<br />
or change from their expected state. On the web dashboard, you can see exactly what changed, who made the changes, and when.


## SQL DBA Bundle
Red Gate 7 products for DBA:
 - SQL Backup Pro: Compress, securely encrypt, and strengthen your backups
 - SQL Monitor: Monitor your SQL Server performance and be alerted to problems
 - SQL Multi Script Unlimited: Deploy multiple scripts to multiple servers with just one click
 - SQL Compare: Compare and synchronize database schemas
 - SQL Data Compare: Compare and synchronize database contents
 - SQL Prompt: Write, format, and refactor SQL effortlessly
 - SQL Doc: Automatically generate database documentation


## SQL Check
Download page: [SQL Check]<br/>
Release date: 2015-09-24<br/>
Support Version: 2000/2005/2008/2008R2/2012/2014<br/>
Free version: Yes

With SQL Check you can:
 - check out what happens in batches, compilations, recompilations, and transactions throughout the SQL Server environment so you don’t experience any surprises and know where to direct your attention to prevent potential issues.
 - monitor some of the most important metrics in SQL Server including wait stats, reads, writes, session details, and cache hits.
 - see SQL operations as they occur for the latest information; consider it a heart rate monitor for your SQL Server environment providing instant feedback and results. Customize the refresh rate and amount of historical data for each SQL server.
 - install easily without agents


## SQL Fragmentation Analyzer
Download page: [SQL Fragmentation Analyzer]<br/>
Release date: 2015-06-24<br/>
Support Version: 2000/2005/2008/2008R2/2012/2014<br/>
Free version: Yes

With SQL Fragmentation Analyzer you can:
 - analyze fragmentation by one table or an entire database
 - identify databases in need of defragmentation
 - set fragmentation thresholds: normal, warning, critical


## SQL Heat Map
Download page: [SQL Heat Map]<br/>
Release date: 2015-12-07<br/>
Support Version: 2005/2008/2008R2/2012/2014<br/>
Free version: Yes

With SQL Heat Map you can:
 - get one visual view of storage in all tables of a database
 - see storage allocation, utilization, and type of data
 - quickly locate tables and indexes that need more allocated storage


## SQL Hekaton Memory Check
Download page: [SQL Hekaton Memory Check]<br/>
Release date: 2015-12-07<br/>
Support Version: 2014<br/>
Free version: Yes

With SQL Hekaton Memory Check you can:
 - monitor the impact of memory optimized tables on server memory
 - identify high memory utilizing tables
 - assess server memory capacity
 - simulate moving to In-Memory OLTP


## SQL Page Viewer
Download page: [SQL Page Viewer]<br/>
Release date: 2014-08-25<br/>
Support Version: 2005/2008/2008R2/2012/2014<br/>
Free version: Yes

SQL Page Viewer:
 - displays page level data summary and detail information
 - has elegant GUI design for fast access in 1 click
 - can select any SQL server and database table
 - can navigate to any page data quickly in a tree view
 - can launch directly within SSMS for optimal usability


## SQL Update Statistics
Download page: [SQL Update Statistics]<br/>
Release date: 2015-12-14<br/>
Support Version: 2005/2008/2008R2/2012/2014<br/>
Free version: Yes

With SQL Update Statistics you can:
 - launch directly within SSMS for optimal usability
 - identify out-of-date SQL Server table and index statistics
 - view and change database statistics options
 - create graphical histograms for each column’s statistics


## SQL Statistics Aggregator
Download page: [SQL Statistics Aggregator]<br/>
Release date: 2015-05-18<br/>
Support Version: 2005/2008/2008R2/2012/2014<br/>
Free version: Yes

With SQL Statistics Aggregator you can:
 - aggregate IO statistics to identify problem tables
 - correlate disk activity with query plan nodes
 - compare runs of a query over time
 - export and import results for easy collaboration


## SQL Backup Status Reporter
Download page: [SQL Backup Status Reporter]<br/>
Release date: 2015-08-07<br/>
Support Version: 2000/2005/2008/2008R2/2012<br/>
Free version: Yes

With SQL Backup Status Reporter you can:
 - quickly identify databases which have not had backups
 - view backup history including the backup date and type
 - have simplified grid view for easy sorting and navigation
 - identify full and differential backups for many databases


## SQL Integrity Check
Download page: [SQL Integrity Check]<br/>
Release date: 2013-08-26<br/>
Support Version: 2000/2005/2008/2008R2/2012<br/>
Free version: Yes

With SQL Integrity Check you can:
 - easily run a CHECKDB for any database on-demand
 - view integrity check results to identify corruption
 - routinely verifies when last check was performed
 - receive alerts when databases are due for checks
 - don't need to write and maintain scripts


## SQL Job Manager
Download page: [SQL Job Manager]<br/>
Release date: 2012-03-19<br/>
Support Version: ???<br/>
Free version: Yes

With SQL Job Manager you:
 - have management console to easily view past and current jobs
 - can identify and correct job contention
 - can drag and drop jobs across servers to level workloads
 - can “at a glance” view to see failed or runaway jobs
 - have customizable calendar view


## Azure SQL Database Backup
Download page: [Azure SQL Database Backup]<br/>
Release date: 2015-08-07<br/>
Support Version: ???<br/>
Free version: Yes

Azure SQL Database Backup allows/gives you:
 - to save time and storage space with up to 95% compression
 - backup on-premise or to Azure BLOB storage
 - central data storage to prevent data loss
 - view historical backup and restore operations
 - restore with transaction consistency to and from the cloud


## SQL Column Search
Download page: [SQL Column Search]<br/>
Release date: 2015-11-17<br/>
Support Version: 2005/2008/2008R2/2012/2014<br/>
Free version: Yes

With SQL Column Search you can:
 - find potentially sensitive data
 - search an entire instance or a specific table
 - export results to CSV format for easy analysis and reporting


## SQL Permissions Extractor
Download page: [SQL Permissions Extractor]<br/>
Release date: 2015-08-07<br/>
Support Version: 2000/2005/2008/2008R2/2012<br/>
Free version: Yes

With SQL Permissions Extractor you can:
 - Generate T-SQL scripts for copying of user permissions
 - edit, save, and execute permissions scripts
 - include object level permissions for selected databases
 - copy, extract, modify and apply changes in four steps


[Microsoft Log Parser]:https://www.microsoft.com/en-us/download/details.aspx?id=24659
[tablediff Utility]:https://msdn.microsoft.com/en-us/library/ms162843.aspx
[Diskspd]:https://github.com/microsoft/diskspd
[HammerDB]:http://www.hammerdb.com/
[dta Utility]:https://msdn.microsoft.com/en-us/library/ms162812.aspx
[osql Utility]:https://msdn.microsoft.com/en-us/library/ms162806.aspx
[sqldiag Utility]:https://msdn.microsoft.com/en-us/library/ms162833.aspx
[sqldumper Utility]:https://support.microsoft.com/en-us/kb/917825
[SqlLocalDB Utility]:https://msdn.microsoft.com/en-us/library/hh212961.aspx
[sqllogship Utility]:https://msdn.microsoft.com/en-us/library/bb283327.aspx
[sqlservr Application]:https://msdn.microsoft.com/en-us/library/ms162819.aspx
[SQL XEvent Profiler]:https://www.idera.com/productssolutions/freetools/sqlxeventprofiler
[DLM Dashboard]:http://www.red-gate.com/products/dlm/dlm-dashboard/
[SQL DBA Bundle]:http://www.red-gate.com/products/dba/dba-bundle/
[SQL Check]: https://www.idera.com/productssolutions/freetools/sqlcheck
[SQL Fragmentation Analyzer]: https://www.idera.com/productssolutions/freetools/sqlfragmentationanalyzer/overview
[SQL Heat Map]: https://www.idera.com/productssolutions/freetools/sql-storage
[SQL Hekaton Memory Check]: https://www.idera.com/productssolutions/freetools/hekaton-memory-check-for-sql-memory-optimized-tables
[SQL Page Viewer]: https://www.idera.com/productssolutions/freetools/sql-server-page
[SQL Update Statistics]: https://www.idera.com/productssolutions/freetools/sql-server-statistics/overview
[SQL Statistics Aggregator]: https://www.idera.com/productssolutions/freetools/statistics-aggregator-for-performance-tuning-in-sql
[SQL Backup Status Reporter]: https://www.idera.com/productssolutions/freetools/sqlbackupstatusreporter/overview
[SQL Integrity Check]: https://www.idera.com/productssolutions/freetools/sqlintegritycheck/overview
[SQL Job Manager]: https://www.idera.com/productssolutions/freetools/sqljobmanager
[Azure SQL Database Backup]: https://www.idera.com/productssolutions/freetools/azuresqldatabasebackup
[SQL Column Search]: https://www.idera.com/productssolutions/freetools/sql-column-search
[SQL Permissions Extractor]: https://www.idera.com/productssolutions/freetools/sqlpermissionsextractor