# Fibonacci-to-the-Kth-number
Finds the kth(number you choose) Fibonacci number for you


public class nameOne
{


	public static void main (String [] args)
	{
  
  
  
		int numberK = 10;
		int [] array1 = new int[numberK];
		
		for(int i =0; i<=numberK-1 ; i++)
		{
			if(i<=1){
				array1[i]= 1;
			}
			else{
				array1[i] = (array1[i-2])+(array1[i-1]);
			}
		}
		
		System.out.println("Fibonacci Sequence: " + array1[numberK-1]);
	}
}

