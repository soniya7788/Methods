
_________________________________________________________CODE_______________________________________________________________
public class Methods {
	
	//*************** Create method to print your name ***************
	
	public void printname(String name)
	{
		System.out.println(name);
	}
	
	//************** Create method to add two numbers ***************
	
	public void add(int a, int b)
	{
		int c = a+b;
		System.out.println("Addition of "+a+" and "+b+" is "+c);
	}
	
	//*************** Create method to check even or odd ***************
	
	public void EvenOdd(int num)
	{
		if(num%2==0)
			System.out.println(num+" is even number");
		else
			System.out.println(num+" is odd number");
	}
	
	//*************** Create method to find square of number ***************
	
	public void square(int num)
	{
		System.out.println("Square of "+num+" is "+num*2);
	}
	
	//*************** Create method to return largest of two numbers ***************
	
	public void findLarge(int num1, int num2)
	{
	    if(num1>num2)
	    	System.out.println(num1+" is greater than "+num2);
	    else
	    	System.out.println(num2+" is greater than "+num1);
	}
		
	public static void main(String args[])
	{
		Methods m = new Methods();
		
	    m.add(10, 20);
	    m.printname("Soniya");
	    m.EvenOdd(10);
	    m.findLarge(3, 5);
	    m.square(4);
	}
	}
  _________________________________________________________OUTPUT_______________________________________________________________

Addition of 10 and 20 is 30
Soniya
10 is even number
5 is greater than 3
Square of 4 is 8

