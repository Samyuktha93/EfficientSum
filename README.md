# EfficientSum.java
public class EfficientSum {
  public static void main(String[] args) {
    int[] numbers = {1, 2, 3, 4, 5};
    int sum = calculateSum(numbers);
    System.out.println("Sum: " + sum);
  }
  public static int calculateSum(int[] numbers) {
    int sum = 0;
    for (int num : numbers) {
      sum += num;
    }
    return sum;
  }
}
