\# cisc275-fall2019-first-git
1. Create java files to make this code compile and run.

2. What five objects are created in the main?
	1) arraylist of type Dog named dogs
	2) Dog object named Fido with 4 legs
	3) Dog object named Fido with 3 legs
	4) Dog object named Alfie with 4 legs
	5) Comparator Animal object

3. Can you spot the Comparator constructor call? Where is the class 
definition for the Comparator?
	Yes I can spot the Comparator constructor call, it is located in 
	the Collections.sort method call in line 16, Collections.sort(dogs, new Comparator<Animal>(). 
	The class definition of the Comparator interface is located in the imported file 
	'java.util.Comparator', and the compare method within the Compartor class is overridden 
	following the constructor call.
