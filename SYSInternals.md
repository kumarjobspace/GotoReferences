## System Internals

* This action cannot be completed because the file is open in another application
o find and close the process that has the file open, do this:

Open resource monitor
Open the CPU tab in the monitor
Select all processes (not sure if this is needed, you can probably just search for the handle)
Expand "associated handles"
Search for the file you need
Close the process that has the handle

* https://superuser.com/questions/1039567/this-action-cannot-be-completed-because-the-file-is-open-in-another-application
