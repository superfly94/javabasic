# javabasic



    import java.util.Scanner;


     public class objects {

	public static void main(String[] args) {
		
        int weight;
		double rate;
		
		
		System.out.print("Please enter your weight");
		weight=new Scanner(System.in).nextInt();
		
		{
			if (weight<=2) {
				rate=1.10;	
			}
			else if ((weight>=2)&& (weight<=6)){
				rate=2.20;


			}
			else if ((weight>=6)&&(weight<=10)) {
				rate=3.70;

			}
			else if (weight <= 10) {
				
				rate=4.80;
			}
			else {
				rate=4.80;
			}
                  System.out.printf("Your cost per 500 miles would be $%.2f",rate);
			
		
		}

			
 }
}	
	
	
	
	
	
	
	
	

