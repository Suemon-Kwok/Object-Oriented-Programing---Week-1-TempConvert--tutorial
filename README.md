/*
Object oriented programming Lab 1 question 5

Complete the main method in the TempConvert class to convert a temperature from Celsius to Fahrenheit by
1.	Declaring the double-typed variable celsius = 31.5
2.	Printing the formatted output value of celsius to the console
3.	Declaring the double-typed variable fahrenheit = celsius * 9/5 + 32
4.	Printing the formatted output value of fahrenheit to the console

For example:
Test	Result
TempConvert.main(new String[]{})

	celsius = 31.5
fahrenheit = 88.7




public class TempConvert
{
   public static void main(String[] args)
   {
    //declare celsius = 31.5;
    //print celsuis = ...
    //declare fahrenheit = celsius * 9/5 + 32;
    //print fahrenheit
   }
}
*/

public class TempConvert 
{
	public static void main(String[] args)
	{
		double celsius = 31.5;
		System.out.println("celsius = " + celsius);
		double fahrenheit = celsius * 9 / 5 + 32;
		System.out.println("fahrenheit = " + fahrenheit);
	}	
}
