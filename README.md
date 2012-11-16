P05
===

Project 5

The purpose of this code is to have a counter that reads 0 the first time it is ran and then progressively gets larger each time the progam is ran.

The code Prints out messages depending on if the code is refreshed as well as the first time that it is ran. IT also pirnts out how many time the program has been run.

To build the code you must install the make file then you must type mknod /dev/counter c 17 0. After that you type service up /usr/sbin/counter - dev /dev/counter ,  to make the counter. Now you can type cat /dev/counter to run the counter.

To execute just type cat /dev/counter.

Something interesting I learned about the project is the itoa call makes things into a string. This makes it easier to print the object out to the screen.

I do not understand what most of the code that is run with the counter does. It doesn't make sense to me probably because I did not have enough time to look through what the rest of the code does.

One of the biggest problems I had was to print the number of times the program ran to the putty window. I ended up using the itoa function to get it to print to the putty window.

I wish someone had went over some of the ways to change the int to a string to make it easier to print out.