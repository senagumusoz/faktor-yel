# faktoriyel
package çalışmalar;

import java.util.Scanner;

public class faktoriyel {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		Scanner input=new Scanner(System.in);
		int fakt=1;
		System.out.println("sayi gir");
		int sayi=input.nextInt();
		if(sayi<=0)
		{
			System.out.println("lutfen 0 veya daha büyük sayi gir:");
			return;
		}
		for(int i=1;i<=sayi;i++)
		{
			fakt=i*fakt;
			
		}
		System.out.println("faktor:"+fakt);
	}

}
