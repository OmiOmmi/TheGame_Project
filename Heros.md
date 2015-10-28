# TheGame_Project
import java.util.Scanner;
public class Heros {
	
	String name,team;
	int hp,mp;
	int atk,def,matk,mdef;
	
	public Heros(){
		name = "Default";
		hp = 1;
		mp = 1;
		atk = 1;
		def = 1;
		matk = 1;
		mdef = 1;
	}
	
	public void InputName(){
		Scanner sc = new Scanner(System.in);
		System.out.print("Your hero name : ");
		name = sc.nextLine();
	}
	public void InputTeamName(){
		Scanner sc = new Scanner(System.in);
		System.out.print("Team name : ");
		team = sc.nextLine();
	}

}
