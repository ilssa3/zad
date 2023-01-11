package meowww;

import java.util.Scanner;

public class arrneotricatelni {
	
public static void sortdown(int []arr) {
		
		int buf = 0;	
		
		for (int i = 0 ; i < arr.length ; i++){
			for (int j = i+1 ; j < arr.length ; j++)  { 
				if (arr[i] < arr[j])
			
		  {buf=arr[i];arr[i]=arr[j];arr[j]=buf;
		  
		  	}
		  }
		}
	System.out.print("podredba 'namalqvasht red'= ");
		for(int i = 0 ; i < arr.length ; i++)
			System.out.print(arr[i]+" ;");
	}
	

	
	public static void sortup(int []arr) {
		
		int buf = 0;	
		
		for (int i = 0 ; i < arr.length-1 ; i++){
			for (int j = i+1 ; j < arr.length ; j++)  { 
				if (arr[j] < arr[i])
			
		  {buf=arr[i];arr[i]=arr[j];arr[j]=buf;
		  
		  	}
		  }
		}
		System.out.print("podredba 'narastvasht red'= ");
			for(int i = 0 ; i < arr.length ; i++)
				System.out.print(arr[i]+" ;");
	}
	
	
	
	public static void poloj (int []arr) {
		Scanner sc = new Scanner (System.in);
		
					int sum = 0;
					boolean trigger = false;
		for (int i = 0 ; i < arr.length; i++) {
			if (arr[i]<0 && trigger == false) sum +=arr[i];
			else { if (trigger == false) {System.out.println("1vi neotr.el = "+arr[i]);trigger = true; }}
			
			
			
		}		System.out.println("sumata na elementite predi 1viq neotricatelen = "+sum);		
}

			//-----------------------------------
			
			public static void output(int []arr) {
				
		Scanner sc = new Scanner (System.in);
				
				for (int i = 0 ; i < arr.length; i++) {System.out.println("arr["+i+"] = "+arr[i]);		
				}
			}
			
			
			
			public static void input(int []arr) {
				Scanner sc = new Scanner (System.in);
				
				int br = 0;
				
				for (int i = 0 ; i < arr.length; i++) {System.out.print("arr["+i+"] = ");
					arr[i] = sc.nextInt();br++;
					
				}System.out.println("broq na chislata = "+br);
			}
			
			

	public static void main(String[] args) {
		
		Scanner sc = new Scanner (System.in);
		int n = sc.nextInt();
		
		int []arr = new int[n];		
		
						input(arr);
		System.out.println(" ");
						output(arr);
		System.out.println(" ");
						poloj(arr);
		System.out.println(" ");
						sortup(arr);
		System.out.println(" ");
						sortdown(arr);
		
		
	}

}
