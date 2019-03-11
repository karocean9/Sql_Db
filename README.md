# Sql_Db
SQL database creations, installation and setup 

# Create a new DB from Command Prompt

Step 1: Install the SSMS from Microsoft

Step 2: Open Command Prompt and Run It as Administrator

Step 3: Type the following commands to check if the installation is successful (You need to Reboot After the Installation of SSMS)

```
C:\Windows\system32>SqlLocaldb
Microsoft (R) SQL Server Express LocalDB Command Line Tool
Version 13.0.1601.5
Copyright (c) Microsoft Corporation.  All rights reserved.

Usage: SqlLocalDB operation [parameters...]

Operations:

  -?
    Prints this information

  create|c ["instance name" [version-number] [-s]]
    Creates a new LocalDB instance with a specified name and version
    If the [version-number] parameter is omitted, it defaults to the
    latest LocalDB version installed in the system.
    -s starts the new LocalDB instance after it's created

  delete|d ["instance name"]
    Deletes the LocalDB instance with the specified name

  start|s ["instance name"]
    Starts the LocalDB instance with the specified name

  stop|p ["instance name" [-i|-k]]
    Stops the LocalDB instance with the specified name,
    after current queries finish
    -i request LocalDB instance shutdown with NOWAIT option
    -k kills LocalDB instance process without contacting it

  share|h ["owner SID or account"] "private name" "shared name"
    Shares the specified private instance using the specified shared name.
    If the user SID or account name is omitted, it defaults to current user.

  unshare|u ["shared name"]
    Stops the sharing of the specified shared LocalDB instance.

  info|i
    Lists all existing LocalDB instances owned by the current user
    and all shared LocalDB instances.

  info|i "instance name"
    Prints the information about the specified LocalDB instance.

  versions|v
    Lists all LocalDB versions installed on the computer.

  trace|t on|off
    Turns tracing on and off

SqlLocalDB treats spaces as delimiters. It is necessary to surround
instance names that contain spaces and special characters with quotes.
For example:
   SqlLocalDB create "My LocalDB Instance"

The instance name can sometimes be omitted, as indicated above, or
specified as "". In this case, the reference is to the default LocalDB
instance "MSSQLLocalDB".
```
