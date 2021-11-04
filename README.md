# ArrayList Practice

In this assignment, you'll be writing three methods related to ArrayLists. 

The first method is countOdd(). This method takes an ArrayList<Integer> as input and returns the number of odd numbers in the ArrayList. The method should have the following signature:
```shell script
public static int countOdd(ArrayList<Integer> list) { }
```

The next method is checkDuplicates(). This method takes two ArrayList<Integer> as input and returns true if there is a number that appears in both ArrayLists.
```shell script
public static boolean checkDuplicates(ArrayList<Integer> list1, ArrayList<Integer> list2) { }
```

Finally, the last method is convertToArrayList(). Unlike the other methods, this method takes an **int[]** as input. The method returns an ArrayList<Integer> containing the values from the int[].
```shell script
public static ArrayList<Integer> convertToArrayList(int[] arr) { }
```

<br />
<br />

## Run your code with:
The easiest way to run your code is to press the play button in [MyMain.java](src/main/java/MyMain.java).

However, you can also run your code by typing the following into the Terminal.

```shell script
make run
```

Alternatively, if that doesn't work, use:

```shell script
./gradlew run
```

## Run your tests with:
The easiest way to run your code is to press the play button in [MyTests.java](src/test/java/MyTests.java).

However, you can also run your code by typing the following into the Terminal.

```shell script
make test
```

Alternatively, if that doesn't work, use:

```shell script
./gradlew test
```