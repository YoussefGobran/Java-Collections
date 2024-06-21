# Interfaces that extend the Java Collections Interface

## Collection Interface
- This interface extends the iterable interface and is implemented by all the classes in the collection framework.
- This interface contains all the basic methods which every collection has like adding the data into the collection, removing the data, clearing the data, etc.
- All these methods are implemented by all the classes irrespective of their style of implementation.
- And also, having these methods in this interface ensures that the names of the methods are universal for all the collections.
- Therefore, in short, we can say that this interface builds a foundation on which the collection classes are implemented.

![image](https://github.com/YoussefGobran/Java-Collections/assets/132088403/ea794da4-2b8d-469e-9ee1-234890ad74fb)

![image](https://github.com/YoussefGobran/Java-Collections/assets/132088403/1bd874fa-f976-4483-8e4b-a5eacaaadb10)

## 1. List Interface
- This is a child interface of the collection interface.
- This interface is dedicated to the data of the list type in which we can store all the ordered collections of the objects.
- This also allows duplicate data to be present in it.
- This list interface is implemented by various classes like ArrayList, Vector, Stack, etc.
-  Since all the subclasses implement the list, we can instantiate a list object with any of these classes.

## 2. Queue Interface
- As the name suggests, a queue interface maintains the FIFO(First In First Out) order similar to a real-world queue line.
- This interface is dedicated to storing all the elements where the order of the elements matter.
- For example, whenever we try to book a ticket, the tickets are sold on a first come first serve basis. Therefore, the person whose request arrives first into the queue gets the ticket.
- There are various classes like PriorityQueue, ArrayDeque, etc.
- Since all these subclasses implement the queue, we can instantiate a queue object with any of these classes.

## 3. Set Interface
- A set is an unordered collection of objects in which duplicate values cannot be stored.
- This collection is used when we wish to avoid the duplication of the objects and wish to store only the unique objects.
- This set interface is implemented by various classes like HashSet, TreeSet, LinkedHashSet, etc.
- Since all the subclasses implement the set, we can instantiate a set object with any of these classes.

## 4. Sorted Set Interface
- This interface is very similar to the set interface.
- The only difference is that this interface has extra methods that maintain the ordering of the elements.
- The sorted set interface extends the set interface and is used to handle the data which needs to be sorted.
- The class which implements this interface is TreeSet.
- Since this class implements the SortedSet, we can instantiate a SortedSet object with this class. 
