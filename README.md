Implemented a class MyIntArrayList - a collection that can store elements of type int. 
The MyIntArrayList collection operates similarly to the ArrayList<E> collection. 
Accordingly, a property of the class is that it will have automatic resizing.

Specifications:

In the implementation of the MyIntArrayList class, it is forbidden to use the ArrayList<E> collection, but the use of the array is allowed. 
Consequently, all operations must be implemented manually without using the functionality provided by the methods of the ArrayList<E> class.

Functionality:

I. Constructors:
-  MyIntArrayList()
-  MyIntArrayList(MyIntArrayList c)
-  MyIntArrayList(int initialCapacity)

II. Methods:
-   void add(int index, int element)
-   boolean add(int e)
-   int size()
-   boolean contains(int e)
-   int get(int index)
-   int indexOf(int e)
-   int lastIndexOf(int e)
-   boolean remove(int e)
-   int removeElementAtIndex(int index)
-   void clear()
-   int set(int index, int e)
-   boolean addAll(MyIntArrayList c)
-   boolean addAll(int index, MyIntArrayList c)
-   int[] toArray()
-   void ensureCapacity(int minCapacity)
-   void trimToSize()




