
import java.util.*;
class Project1 
{
	public static void main(String... args)
{
		int arr[][][]= {
				{{60,50,62},{43,81,71}},
				{{35,81,92},{54,45,38}}
				};
			int sum=0;
    		for(int i=0;i<arr.length;i++)  
                {
		System.out.println("Department No. "+(i+1));
                for(int j=0;j<arr[i].length;j++)
                {
		System.out.println("Student No. "+(j+1));
		for (int k=0; k<arr[i][j].length;k++)
		{
                System.out.print(arr[i][j][k]+"\t"); 
		sum+=arr[i][j][k];    
                }
System.out.println();
                }System.out.println(sum);
 
               }
}


}
