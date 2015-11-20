#Choosing a Relational Database Management System (RDBMS)

There is a lot to consider when choosing which relational database to use on your next project. As far as choices, you have to choose between [SQLite](https://www.sqlite.org/), [MySQL](https://www.mysql.com/), and [PostgreSQL](http://www.postgresql.org/). Here is a quick summary of when or when not to use each.

<small>Note: If you are looking for more information, take a look at [Digital Ocean's article on RDBMS](https://www.digitalocean.com/community/tutorials/sqlite-vs-mysql-vs-postgresql-a-comparison-of-relational-database-management-systems). Much of my notes is based on this article.</small>

##SQLite - The Portable Choice

**Use** If Your Application...

* Requires portablitly, not expandability (eg. is embedded)
* Desires a disk access replacement
* Is designed for testing purposes

**Do Not Use** If Your Application...

* Requires multiple users to access and modify the database itself, each with their own permissions
* Requires concurrent write operations

##MySQL - The Popular Choice

**Use** If Your Application...

* Requires distributed operations
* Requires the largest support knowledgebase
* Requires a stand alone database server
* Requires high security
* Desires easy hosting
* Needs a customized solution
* Requires a speedy, hosted solution

**Do Not Use** If Your Application...

* Requires high reliability
* Requires strict SQL compliance
* Requires concurrent write operations
* Requires a very active development community

##PostreSQL - The Advanced Choice

**Use** If Your Application...

* Requires strict SQL compliance
* Requires the strongest available support (but not necessarily the largest knowledgebase)
* Requires programmatic extensibility/customizability
* Requires Nesting and other Objective support
* Requires the highest reliability

**Do Not Use** If Your Application...

* Requires simple read-heavy operations
* Requires the largest support knowledgebase
* Desires easy hosting/setup
* Requires replication

