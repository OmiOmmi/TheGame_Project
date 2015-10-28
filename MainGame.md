# TheGame_Project
import java.util.Scanner;
public class MainGame {

	public static void main(String[] args) {
		
		Scanner scan = new Scanner(System.in);
		Heros Heros1 = new Heros();
		Heros Heros2 = new Heros();

		System.out.println("---------- !!! Start Game !!! ----------");
		System.out.println("Create your team");
		// Create team1 
		System.out.println("---------------  Team 1 ----------------");
		Heros1.InputTeamName();
		Heros Herosteam1[] = new Heros[3];
		for(int i = 0;i<=2;i++){
			Herosteam1[i] = new Heros();
			Herosteam1[i].InputName();
		}
		System.out.println("----------------------------------------");
		System.out.println("Team name : "+Heros1.team);
		for(int i = 0;i<=2;i++){
			System.out.println("Hero name :"+Herosteam1[i].name);
		}
		System.out.println("----------------------------------------");		
		
		// Create team2
		System.out.println("---------------  Team 2 ----------------");
		Heros2.InputTeamName();
		Heros Herosteam2[] = new Heros[3];
		for(int i = 0;i<=2;i++){
			Herosteam2[i] = new Heros();
			Herosteam2[i].InputName();
		}
		System.out.println("----------------------------------------");
		System.out.println("Team name : "+Heros2.team);
		for(int i = 0;i<=2;i++){
			System.out.println("Hero name :"+Herosteam2[i].name);
		}
		System.out.println("----------------------------------------");
	}

}
