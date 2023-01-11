package meowww;

import java.util.Scanner;

public class arrmethminmax1 {
	
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
	
	//-----------------------------------
	
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
	
	//-----------------------------------
	
	
	public static void minmax(int []arr) {
		Scanner sc = new Scanner(System.in);
		
		int min; int max;
		max = arr[0];min = arr[0];
		
		for(int i = 0; i < arr.length; i++) 
	{
		if(arr[i] > max) max = arr[i];
		if(arr[i] < min) min = arr[i];
	}
	
		System.out.println("MAXIMALNATA STOINOST OT MASIVA = " + max);
		System.out.println("MINIMALNATA STOINOST OT MASIVA = " + min);
	}
	

	//-----------------------------------
	
	public static void sredno (int []arr) {
		Scanner sc = new Scanner (System.in);

			int br = 0;int sb = 0;int brsr=0;int sr=0;
				
				for (int i = 0 ; i < arr.length; i++) {
					br++;sb = sb +arr[i];
				} sr = sb /br;
				
				
				System.out.println("sredno aritm. = "+sr);
				
				for (int i = 0 ; i < arr.length; i++) {
					
					if (arr[i]>sr)brsr++;
				}System.out.println("broi cifri nad srednoto = "+brsr);
				
			}

			//-----------------------------------
			
			public static void output(int []arr) {
				
		Scanner sc = new Scanner (System.in);
				
				for (int i = 0 ; i < arr.length; i++) {System.out.println("arr["+i+"] = "+arr[i]);		
				}
			}
			
			
			//-----------------------------------
			
			public static void input(int []arr) {
				Scanner sc = new Scanner (System.in);
				
				int br = 0;
				
				for (int i = 0 ; i < arr.length; i++) {System.out.print("arr["+i+"] = ");
					arr[i] = sc.nextInt();br++;
					
				}System.out.println("broq na chislata = "+br);
			}
			
			
			//-----------------------------------
			
			public static void main(String[] args) {
				Scanner sc = new Scanner (System.in);
				int a = sc.nextInt();
				
				int []arr = new int[a];		
				
				
				input(arr);
System.out.println(" ");
				output(arr);
System.out.println(" ");
				sredno(arr);
System.out.println(" ");
				minmax(arr);
System.out.println(" ");
				sortup(arr);		
System.out.println(" ");
				sortdown(arr);				
			}

		}
