# TheGame_Project
import java.util.Scanner;
public class Heros {
	
	String name,team,job;
	int hp,mp;
	int atk,def,matk,mdef;
	
	public Heros(){
		name = "Default";
		job = "Novice";
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
	public void Printteam(){
		System.out.println("Team Name : "+team);
	}
	public int randomteam(){
		double r;
		int random;
		r = Math.random()*10;
		random = (int)r;
		return random;
	}
	public int randomHeros(){
		double r;
		int randomHeros;
		r = (Math.random()*7)+1;
		randomHeros = (int)r;
		return randomHeros;
	}
}
