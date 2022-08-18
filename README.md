# NAble-RMM-Run-Commands-As-User-Context
This script will allow you to run automated scripts from NAble RMM N-sight in the User context. Normally, scripts execute as SYSTEM. This script will get the currently logged on user and execute it as that user.

NOTE: There must be a user logged into the machine, or this script will not work. If no user is logged in, the script is unable to obtain a user context.
