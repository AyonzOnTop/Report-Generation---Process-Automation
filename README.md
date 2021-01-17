# Report generation with Process automation robot

This project is about automating the process of generating year-end 
report.  

## Technology

The UIPath robotic process automation (RPA) framework was used to build the 
solution.

The solution was divided into two processes
- Dispatcher process bot
- Performer process bot

The Dispatcher takes the record generated for each month from a web portal 
and sends it to a queue on the orchestrator (a cloud platform for managing 
the RPA bots on systems). Then the performer processes the queue of records 
from the orchestrator and generates a year-end report on the records collated 
each month.

<img src="https://www.fastidiousautomation.com/uploads/5/7/2/1/57212291/reframeworkimage_orig.png"></img>

This is a very manual process where the employee had to go to the web portal to collect records for each month.
Then use excel to do some summation of figures to generate the year end report. Now this can be done with a UIPath robot at an instant.

Check generate yearly report pdf above for more information