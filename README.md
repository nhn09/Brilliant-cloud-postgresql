# Starting postgresql
 PostgreSQL, also known as Postgres, is an object-relational database management system emphasizing extensibility and uses SQL as the language.
 
### Why postgres? 
 
 * free
 
 * opensource(in which source code is released under a license in which the copyright holder grants users the rights to use, study, change, and distribute the software to anyone and for any purpose.)
 
 * robust (robustness of the database is a fundamental issue in the design of systems which must survive crashes, maintaining data consistency and system availability.)


#### What is a database?

Random data becomes valuable if they are arranged in efficiecnt ways.


Database is a way of Managing data in an arranged manner creating multiple tables made of columns and rows, for furthur operations like 

* Storing 
* Manupulation
* Retrive

And when the tables are inter-related, it is named as **Relational** database.


| Column1       |   Column2     |Column3  |
| ------------- |:-------------:| -----:  |
| This is       | row           | 1!      |
| This is       | row           | 2!      |
| This is       | row           | 3!      |


for these acts to do upon large number of data,the magic spells are found in SQL- structured Query Language. A powerful yet easy programming language.

#### Installation: 

**for MAC**

- [x] Goto the official website of postgres app https://postgresapp.com .
- [x] Select "Downloads".
           In this section,two options will be found.

            1.Latest Release.

            2.Additional Releases
                    this option lets the user run multiple versions of PostgreSQL simultaneously.

            Select the convenient one.
        
- [x] Just click the downloaded file and drop it into Applications folder.


**for WINDOWS**

- [x] Goto the official website of postgres  https://www.postgresql.org/download.

- [x] From the "Packages and Installers" section ,select WINDOWS operating system from the given options.

- [x] From the table of versions, it's preferrable to choose the latest one,and press the supported version of your   windows(64 bit or 32 bit).

- [x] Open the downloaded file,start installation.
                     
                     1. A dialogue box named Set up will open up.Press next.

                     2. **installation directory** : choose the path where it will be installed.

                     3. **Select components** : select them all ( or you may unselect pgadmin and install it separately later)

                     4. **Password** : add a password for super user, You may need it later.

                     5. **Port** : Leave as it is (5432).

                     6. Leave the Advanced Options as it is.

                     7. After showing the summary of what so far done, installation wil begin. 



## Ways to Connect the Database:

* GUI client: as the name refers, graphical interface will result easy manipulation.Such as Datagrip,postico,pgadmin.
* CMD client:Makes the inner logics and interactions clearer. 
* Application: Using intermediate applications.

## Connecting PSQL in windows using SQL shell:

* Open PSQL shell.
* It will show "Server [localhost]:" in the console.For remote server, write the url, otherwise for local server just press enter.
* It will now show "Database [postgres]:" , there is already a default value present for this, so also press enter.
* Port [5432]:this is the default port for Postgres. Press enter.
* Username [postgres]:It is also "postgres", and set by default. Press enter.
* Password for user postgres: While installing , we created a password for superuser, now plug that password here.
* While writing the password, console will remain empty, it's ok to be that way.

Now the shell will look like this-

       WARNING: Console code page (437) differs from Windows code page (1252)
         8-bit characters might not work correctly. See psql reference
         page "Notes for Windows users" for details.
       Type "help" for help.
       postgres=#



## Connecting PSQL in windows using PgAdmin:

* Open PgAdmin, go to server on the left-most corner.
* select postgresQL from the option.
* password window will pop-up, fill that up.

##  Creating own database:

* Normally if we write \l in the shell, it show bunch of previously created databases.But to make a new one, some command is to be used. 

  CREATE DATABASE P_ONE(may use any name) ;
  for a successful command, it will print CREATE DATABASE after the command line.
  commanding \l we can check wheather this database is created or not.

* help command will show a bunch of helpful commands.
* simply type "\c table_name" to connect.


                                           **A very sensitive command**                   











