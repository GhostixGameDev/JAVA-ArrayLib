# JAVA-ArrayLib
Utilities for arrays that I use for my highschool assignments. Works with every class compatible with [Comparable](https://docs.oracle.com/javase%2F8%2Fdocs%2Fapi%2F%2F/java/lang/Comparable.html).<br />

<br />
<br />
====================================================<br />
Initialization:
ArrayUtils&lt;Class&gt; example = new ArrayUtils(Class, int size);
====================================================<br />
Static methods: <br />
<ul>
  <li>binarySearch(array, objective): Returns the int position of the objective in the array. If not found returns -1</li>
  <li>quickSort(array): Returns a sorted array.</li>
  <li>swap(array, int i, int j): Swaps two values in an array.</li>
  <li>in(objective, array): Returns true if the objective is inside the array.</li>
</ul>
<br />
====================================================<br />
Instance methods: <br />
<ul>
  <li>getArray(): Returns the array.</li>
  <li>setArray(array): Overwrites the array.</li>
  <li>changeSize(int newSize): Expands or decreases the array but keeping all the values (Except the ones out of bounds if decreased).</li>
  <li>length(): Returns the array length.</li>
  <li>sort(): Sorts itself using quickSort</li>
  <li>search(objective): Prints the position of the objective in the array if found.</li>
  <li>showArray(): Prints the array values.</li>
</ul>
