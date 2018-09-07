## System Internals

* Problem - This action cannot be completed because the file is open in another application
* Solution -

find and close the process that has the file open, do this:

Open resource monitor
Open the CPU tab in the monitor
Select all processes (not sure if this is needed, you can probably just search for the handle)v
Expand "associated handles"
Search for the file you need
Close the process that has the handle

* https://superuser.com/questions/1039567/this-action-cannot-be-completed-because-the-file-is-open-in-another-application
* https://www.reddit.com/r/AdviceAnimals/comments/2dvbva/the_action_cant_be_completed_because_the_folder/cjtmywc/
