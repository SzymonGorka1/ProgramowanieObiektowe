In the project, I took on the task of implementing the car factory functionality.

The program greets us by saying "welcome to the car factory" and presents a 7-element navigation panel where:

1) You can invoke a method in the Factory class that makes the car "drive". The car checks if there is fuel in the tank; if not, the Auto class method for refueling is activated.

2) At this point, we can sort the cars while removing them from the Factory class vector, and represent the remaining cars using an overloaded assignment operator.

3) "Creating a new car" allows us to create a new car using an overloaded istream operator. We directly input the brand, model, and price separated by whitespace. Then, using the vector class method, we place the new car at the end of the vector.

4) Using a range-based for loop, all cars produced and waiting for sale are easily displayed. For this purpose, we also utilize the overloaded ostream operator declared in the Auto class.

5) It opens a file named "file_name.txt" overwriting its content. We can write to and read from the file. To save the factory's content to a file, I used a previously overloaded ostream operator.

6) Similar to the previous point, we read the file's content into the program using an overloaded istream operator. The method requires specifying the number of elements, and new cars are created accordingly.

7) By pressing 7, we finish our work. If we haven't saved the results, the work will be lost.

In the second part of the project, I created a virtual vehicle class, from which both bicycle and mechanical vehicle inherit. In turn, the car and motorcycle classes inherit from the mechanical vehicle class. I created a new dealership class that buys cars from customers at a lowered price and, in the case of a car with the brand "Izera", resets the odometers by half.

In the main function, I included arguments allowing reading commands from a file. In case of no file, the program reads commands from the standard input.

In the third part, I included instructions throwing exceptions in each overloaded input function and created a factory template allowing the creation of all vehicles.
