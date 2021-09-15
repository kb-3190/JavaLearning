import java.util.Scanner;

class Main {
  public static void main(String[] args) {
    Scanner scanner = new Scanner(System.in);
    System.out.println("数値1: ");
    int num1 = scanner.nextInt();

    System.out.println("数値2: ");
    int num2 = scanner.nextInt();

    System.out.println("計算方法: 1. + , 2. - , 3. × , 4. / ");
    int calc = scanner.nextInt();

    int result = calculate(num1, num2, calc);

    System.out.println("結果: " + result);
  }

  static int calculate(int num1, int num2, int calc) {
      switch (calc) {
        case 1 :
          return num1 + num2;
        case 2 :
          return num1 - num2;
        case 3 :
          return num1 * num2;
        default :
          return num1 / num2;
      }
  }
}
