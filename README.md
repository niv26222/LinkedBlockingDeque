# LinkedBlockingDeque




Class Hierarchy:

java.lang.Object
 ↳ java.util.AbstractCollection<E>
    ↳ java.util.AbstractQueue<E>
        ↳ java.util.concurrent.LinkedBlockingDeque<E>
  
  
  

The LinkedBlockingDeque class in Java is a part of the Java Collection Framework and implements the Collection interface and the AbstractQueue class. It also implements the BlockingDeque and provides an optionally-bounded functionality based on linked nodes. This optional boundedness is served by passing the required size in the constructor and helps in preventing memory wastage. When unspecified, the capacity is by default taken as Integer.MAX_VALUE.



Constructors in Java LinkedBlockingDeque:

LinkedBlockingDeque(): This constructor is used to construct an empty deque. In this case the capacity is set to Integer.MAX_VALUE
LinkedBlockingDeque(int capacity): This constructor creates a LinkedBlockingDeque with the given (fixed) capacity.
LinkedBlockingDeque(Collection<E> c): This constructor is used to construct a deque with the elements of the Collection passed as the parameter.
