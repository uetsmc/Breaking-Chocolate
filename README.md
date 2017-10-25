# Breaking-Chocolate
CodeWars Breaking Chocolate Problem Solution

public class Chocolate{

  public static int breakChocolate(int n, int m) {

  int area = n * m;
  int solution = area - 1;

    if(solution < 0){
        return 0;
} else {
    return solution;
    }
  }
}
