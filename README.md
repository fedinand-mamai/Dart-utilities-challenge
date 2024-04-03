void main() {
  // Task 1: Function to add two numbers
  int addNumbers(int a, int b) {
    return a + b;
  }
  print('Task 1:');
  print(addNumbers(8, 4)); // Example usage
  
  // Task 2: Print numbers from 1 to 10 using a for loop
  void printNumbers() {
    print('\nTask 2:');
    for (int i = 1; i <= 10; i++) {
      print(i);
    }
  }
  printNumbers();
  
  // Task 3: Switch statement for string values
  void switchStatement() {
    print('\nTask 3:');
    String country = 'France';
    switch (country) {
      case 'USA':
        print('United States of America');
        break;
      case 'France':
        print('French Republic');
        break;
      default:
        print('Unknown country.');
    }
  }
  switchStatement();
  
  // Task 4: Print numbers from 20 to 10 using a while loop
  void printNumbersWhile() {
    print('\nTask 4:');
    int i = 20;
    while (i >= 10) {
      print(i);
      i--;
    }
  }
  printNumbersWhile();
  
  // Task 5: Check if a number is even or odd using if-else statement
  void checkEvenOdd(int num) {
    print('\nTask 5:');
    if (num % 2 == 0) {
      print('$num is even.');
    } else {
      print('$num is odd.');
    }
  }
  checkEvenOdd(12); // Example number
  
  // Task 6: Find the largest number in a list
  void findLargestNumber(List<int> numbers) {
    print('\nTask 6:');
    int max = numbers[0];
    for (int i = 1; i < numbers.length; i++) {
      if (numbers[i] > max) {
        max = numbers[i];
      }
    }
    print('The largest number is: $max');
  }
  findLargestNumber([25, 17, 39, 8, 55]); // Example list of numbers
  
  // Task 7: Use try-catch block to catch an exception
  void exceptionHandling() {
    print('\nTask 7:');
    try {
      int result = 15 ~/ 0; // Division by zero to trigger exception
      print('Result: $result'); // This line will not be executed
    } catch (e) {
      print('Error: $e'); // Output the caught exception
    }
  }
  exceptionHandling();
}
