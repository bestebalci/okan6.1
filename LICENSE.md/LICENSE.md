package okan6;
import java.util.Scanner;
public class okan62 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int sene, senecase;
		
		Scanner input = new Scanner (System.in);
		System.out.println("Lütfen 4 haneli bir sene girin");
		sene = input.nextInt();
		senecase =  sene %12;
		switch (senecase) {
		case 0:
			System.out.println("Maymun yılı"); break;
		case 1:
			System.out.println("Horoz yılı"); break;
		case 2:
			System.out.println("Kopek yılı"); break;
		case 3:
			System.out.println("Domuz yılı"); break;
			
		case 4:
			System.out.println("Fare yılı"); break;
		case 5:
			System.out.println("Boga yılı"); break;
			
		case 6:
			System.out.println("Kaplan yılı"); break;
		case 7:
			System.out.println("Tavsan yılı"); break;
			
		case 8:
			System.out.println("Ejderha yılı"); break;
		case 9:
			System.out.println("yilan yılı"); break;
		case 10:
			System.out.println("At yılı"); break;
		case 11:
			System.out.println("Kuzu yılı"); break;
			
			
			
			
			
		}

	}

}
