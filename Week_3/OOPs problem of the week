/*
Create an abstract class Compartment to represent a rail coach. Provide an abstract function notice in this class.

public abstract String notice();

Derive FirstClass, Ladies, General, Luggage classes from the compartment class.
Override the notice function in each of them to print notice message that is suitable to the specific type of  compartment.

Create a class TestCompartment.Write main function to do the following:
Declare an array of Compartment of size 10.
Create a compartment of a type as decided by a randomly generated integer in the range 1 to 4.
Check the polymorphic behavior of the notice method.
[i.e based on the random  number genererated, the first compartment can be Luggage, the second one could be Ladies and so on..]
 */
import java.util.Random;
abstract class Compartment
    {
            public abstract String notice();
    }
class FirstClass extends Compartment
{
    public String notice()
    {
        return"FirstClass";
    }
}
class Ladies extends Compartment
{
    public String notice()
    {
        return"Ladies";
    }
}
class General extends Compartment
{
    public String notice()
    {
        return"General";
    }
}
class Luggage extends Compartment
{
    public String notice()
    {
        return"Luggage";
    }
}
 public class TestCompartment {
    public static void main(String[] args) {
        int number;
        Compartment arr[] = new Compartment[10];
        Random obj = new Random();
        for (var i =0; i< arr.length;i++)
        {
            number = 1+obj.nextInt(4);
            switch (number)
            {
                case 1:
                    arr[i] = new FirstClass();
                    System.out.println(arr[i].notice());
                    break;
                case 2:
                    arr[i] = new Ladies();
                    System.out.println(arr[i].notice());
                    break;
                case 3:
                    arr[i] = new General();
                    System.out.println(arr[i].notice());
                    break;
                case 4:
                    arr[i] = new Luggage();
                    System.out.println(arr[i].notice());
                    break;
            }
        }

    }
}
