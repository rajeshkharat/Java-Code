



//Prime & non prime Numbers from 1 to 100

public class ass6{
	public static void main (String []args)
	{
		int c=0,d=0;
		for(int j=1;j<=100;j++){
			int i,temp=1;
		
		for(i=2;i<j;i++){
			if(j%i==0){
				temp=0;
				
				break;
			}
		}
		if(temp==1){
			c++;
			System.out.println(j+" is prime number!");
		}
		else{
			d++;
			System.out.println(j+" is not a prime number !");	
		}
		}
		System.out.println(d+" Non Prime Numbers");
		
		System.out.println(c+" Prime Numbers");
	}
}
