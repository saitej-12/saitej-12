import java.util.Scanner;

public class Experiment_6
{
	public static void main(String args[])
	{
		int a[];

		Scanner sc = new Scanner(System.in);
		System.out.println("Enter the size");
		int n = sc.nextInt();

		a = new int[n];

		System.out.println("Enter the array elements");		
		for(int i=0;i<n;i++)
		   a[i] = sc.nextInt();

		System.out.println("\n Before sorting...");
		display(a,n);
		
		mergepass(a,0,n-1);

		System.out.println("\n After sorting...");
		display(a,n);
	}

	public static void mergepass(int a[], int lb,int ub)
	{
		int mid;
		if(lb!=ub)
		{
			mid = (lb+ub)/2;
			mergepass(a,lb,mid); 
			mergepass(a,mid+1,ub); 
			mergeSort(a,lb,mid,ub);
		}
	}

	public static void mergeSort(int a[], int lb,int mid,int ub)
	{
		int i; 
		int j; 
		int k; 
		int temp[];
		temp = new int[20];
	
		i = lb;
		j = mid+1;
		k = lb;
		while((i<=mid) && (j<=ub))
		{
			if(a[i] <= a[j])
			{
				temp[k] = a[i];
				k++; i++;
			}
			else
			{
				temp[k] = a[j];
				k++; j++;
			}		
		} 
		
		while(i<=mid)
		{
			temp[k] = a[i];
			k++; i++;
		}	
		while(j<=ub)
		{
			temp[k] = a[j];
			k++; j++;		
		}
		for(i=lb;i<=ub;i++) 	
			a[i] = temp[i];
	}

	public static void display(int a[],int n)
	{
		for(int i=0;i<n;i++)
		 System.out.print(a[i]+"   ");
	}
}
