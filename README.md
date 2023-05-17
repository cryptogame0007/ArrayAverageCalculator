# ArrayAverageCalculator
ArrayAverageCalculator
public class ArrayAverageCalculator {
    public static void main(String[] args) {
        int[] array = {1, 2, 3, 4, 5};
        double average = calculateArrayAverage(array);
        System.out.println("Среднее значение элементов массива: " + average);
    }

    public static double calculateArrayAverage(int[] array) {
        int sum = 0;
        for (int number : array) {
            sum += number;
        }
        return (double) sum / array.length;
    }
}
