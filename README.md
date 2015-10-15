## Recursive Merge Sort Algorithm

![](https://upload.wikimedia.org/wikipedia/commons/c/cc/Merge-sort-example-300px.gif)

*Image licensed under Creative Commons c/o Wikipedia user [Swfung8](https://commons.wikimedia.org/wiki/Special:Contributions/Swfung8)*

###About this method
This `merge_sort` method takes in an array of random, unsorted numbers. It then recursively calls itself until the array is fully divided. At that point it compares these two smaller arrays, using the `merge` method, merging the array elements into a third "master" array in order of smallest to largest number. 