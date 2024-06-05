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
  <li>linearSearch(array, objective): Returns the int position of the objective in the array. If not found returns -1</li>
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
  <li>get(index): Returns the value at index.</li>
  <li>set(index, newValue): Changes the value at index.</li>
  <li>[!WARNING] clean(tempValue): Leaves null the array.</li>
  <li>append(newValue): Expands the array one slot and gives it the value.</li>
  <li>delete(valueToDelete, boolean isSorted): Searches the value and deletes it, reducing one slot the array. </li>
  <li>deleteAll(valueToDelete, boolean isSorted): Searches the value and deletes it from all positions found, reducing slots of the array. </li>
  <li>fill(value): Fills all the array positions with the value you give. </li>
  <li>changeSize(int newSize): Expands or decreases the array but keeping all the values (Except the ones out of bounds if decreased).</li>
  <li>length(): Returns the array length.</li>
  <li>sort(): Sorts itself using quickSort</li>
  <li>search(objective): Prints the position of the objective in the array if found.</li>
  <li>showArray(): Prints the array values.</li>
</ul>
