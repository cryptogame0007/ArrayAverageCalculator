  public static double calculateArrayAverage(int[] array) {
        int sum = 0;
        for (int number : array) {
            sum += number;
        }
        return (double) sum / array.length;
    }
}
