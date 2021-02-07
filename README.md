# mycaptain
Develope by vishnu
public class HelloWorld {
	
	private int name;
	
	public static void main(String[] args) {
		
		Scanner sc =new Scanner(System.in);
		int n = sc.nextInt();
		sc.close();
		
		name(); //static functions 
		
		HelloWorld helloWorld = new HelloWorld();
		helloWorld.math(); // non static function 
		
		HelloWorld arp = new HelloWorld();
		int t=arp.math();
		System.out.println(t);
		
		System.out.println("Hi !" +n );
		
	} 
	
  //	void - > return type of a function
	
	public static void name() {
		int sum= 1+2;
		System.out.println("Hi");
	}
	
	public int math() {
		System.out.println("hi"); //hi
		return 2;
	}
	
}
