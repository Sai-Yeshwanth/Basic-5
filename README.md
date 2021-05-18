class Man{
	String name;
	public void details(String name)
	{
		System.out.println("Man name is: " + name);
	}
}
public class Jala {

	public static void main(String[] args) {
		
		Man m = new Man();
		m.details("Sai Yeshwanth");//calling method to print name
	}

}
