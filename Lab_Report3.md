# Failure inducing test that is supposed to reverse the array as the expected but doesn't
```
public class ArrayTests {
	@Test 
	public void testReverseInPlace() {
    int[] input1 = {3,2,1};
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{3,2,1} input1);
	}
```
# Failure inducing test that is supposed to create a new array with the same elements in reversed order

```
  @Test
  public void testReversed() {
    int[] input1 = { 1 };
    assertArrayEquals(new int[]{ 1 }, ArrayExamples.reversed(input1));
  }
}

```
# Working tests that passes but doesn't give the expected outputs 
```
public class ArrayTests {
	@Test 
	public void testReverseInPlace() {
    int[] input1 = { 1 };
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{ 0 } input1);
	}

  @Test
  public void testReversed() {
    int[] input1 = { };
    assertArrayEquals(new int[]{ }, ArrayExamples.reversed(input1));
  }
}

```
