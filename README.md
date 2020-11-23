# Clock-Simulator
Simulates the running of different types of clocks over time. Uses polymorphism and inheritance to represent the clocks. Each clocks will lose a certain amount of time due to the specific drift applied. 

INCLUDED FILES:

 List the files required for the project with a brief
 explanation of why each is included.

 e.g.
AtomicClock.java
CuckooClock.java
GrandfatherClock.java
Sundial.java
WristWatch.java
These files contain the necessary information for the given clocks that allow us to work with and modify them

Bag.java - A simple data structure that holds generic items of type "T".
Clock.java - Abstract class to assist in carrying out the functions of our clocks
ClockSimulation.java - Simulates the running of the clocks over a given time period
Time.java - This is our class for keeping track of time 
TimePiece.java - The interface that is being implemented in order to create and run our clocks 

 * README - this file


COMPILING AND RUNNING:

 From the directory containing all source files, compile the
 driver class (and all dependencies) with the command:
 $ javac ClockSimulation.java

 Run the compiled class file with the command:
 $ java ClockSimulation

 Console output will give the results after the program finishes.
 
 The program itself requires no user input. 
 An example of the output can be shown below: 
 Times after one week
 natural, sun dial, time [  0:00:00], total drift = 0.00
 digital, wrist watch, time [ 23:59:40], total drift = 21.00
 mechanical, cuckoo clock, time [ 23:53:01], total drift = 420.00
 mechanical, grandfather clock, time [ 23:56:31], total drift = 210.00
 quantum, atomic clock, time [  0:00:00], total drift = 0.00


PROGRAM DESIGN AND IMPORTANT CONCEPTS:
The main takeaways from this project was the use of inheritance and polymorphism to create and simulate the running of clocks. We wanted to dynamically store these objects
in a way that we could access and modify them while still following the rules of inheritance and encapsulation. There was also a lot of rendundant code that needed to be replaced by creating a method. The idea is to pull the clocks out of our bag class and tick one second off of them. This then allows us to compute how much time was lost over a given period of time due to the varying drift in the clocks. 


DISCUSSION:
 This was a challenging yet very fun school project that we did. I really loved the deep dive into polymorphism as it's the foundation for object-oriented programming. 
 I did face some issues and had to do a lot of troubleshooting to get through this assignment but I loved the porcess and the learning that came along with this. It really
 helped me kick start this school year off right and helped me find a strong passion for more personal projects to advance my skill. Overall I'd recommend every CS student go 
 through this assignment as it really created a strong foundation for what I wanted to accomplish as a CS student. 
 
 If I were to go through this assignment again I would really focus on creating stronger comments and trying to better format my code. I feel confident in my abilities as a 
 programmer but definitely want to spend more time on creating clean, efficient, and easy to understand code and comments. This way when I go back and look things over I'm 
 better able to identify and fix any mistakes that I may see.
