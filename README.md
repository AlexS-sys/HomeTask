# HomeTask
package HomeTask;

public class TaskThree
{
    public static void main(String[] args)
    {
    int a = 1, b = 50;
    System.out.println("Task one:");
    while (a < b)
        {
        a++;
        if (a % 3 ==0)
            {
            System.out.println(a);
            }
        }
    System.out.println("Task two:");
    int sum = 0;
    for (int x = 1; x <= 100; x++)
    {sum += x;
    }
    System.out.println("Сумма = " + sum);
    }

}
