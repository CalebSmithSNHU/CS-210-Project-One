# Reflection Journal

##### This program gets the time from the OS/motherboard and converts it to a 12 and 24-hour clock in the format HH : MM : SS.  
Additionally, the user can then add time in hours, minutes, or seconds and both clocks will update.
The user can modify the time until they choose to exit the program using the menu.


##### **What did you do particularly well?**

I am proud of how I implemented functions to make the main function extremely small and efficient. 
Likewise, I was determined to get the time from the system instead of having the user input a starting time.
This goal involved me getting familiar with ctime and the functions setw and setfill. 
I learned how powerful in-built functions and libraries can be -- especially in saving time and reducing line count.


##### **Where could you enhance your code? How would these improvements make your code more efficient, secure, and so on?**

As I noted in the top comment of the code, there is a small bug that I was never able to solve: 
on the 12-hour clock, the AM/PM indicator does not switch over properly until 1 PM. 
Bizarrely, it seems to work some of the time but does have the issue more often than not.
Fixing this would make the program 100% in line with the functional requirements and may be able 
to reduce the number of conditional statements used overall -- improving efficiency.


##### **Which pieces of the code did you find most challenging to write, and how did you overcome this? What tools or resources are you adding to your support network?**

Writing the logic for the AM/PM indicator and correctly displaying the time in the 24-hour format proved the most challenging for me.
This required conditional statements for a variety of cases that took me a while to fully grasp.
I used my whiteboard and a million flowcharts to work through the different cases and make sure I didn't miss anything. 
In addition to basic resources like W3 Schools and StackOverflow, I made use of SNHU's peer tutoring to clear up some of my confusion. 
The most useful tool (no exaggeration) was changing my system clock and running the code for each case. 
This was a tedious way to debug and test, but it allowed me to see what the code was doing in every case and easily notice issues. 


##### **What skills from this project will be particularly transferable to other projects or course work?**

In truth, this project gave me confidence to move forward in the rest of the course work. I was overwhelmed when I read the prompt.
Writing pseudo code before getting started helped break the tasks up and remove some of that daunting feeling. 
Making use of functions and libraries showed me good development practices and kept the main function small.
I was meticulous about adding comments as I wrote the program instead of adding them after. 
Admittedly, this adds time and makes you switch tasks more often, but is invaluable in helping one truly understand what each block is doing.
I tried to keep this method up throughout the course to reap the benefits of coming back to partial code that is well documented. 
I want to get better about running the code more often instead of waiting for huge changes and then running it. 


##### **How did you make this program maintainable, readable, and adaptable?**

I wrote clear documentation above and within each block of code to describe what's happening.
I made good use of whitespace to improve readability and help keep the code maintainable.
In terms of adaptation, this project is lacking. One could remove one of the clocks, but other than that, the code is pretty static.
