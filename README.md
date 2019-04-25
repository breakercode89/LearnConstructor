# LearnConstructor
package JavaTutorial;

public class FirstProgram {
	String myName;
	int myAge;

	FirstProgram(String name, int n) {
		this.myName = name;
		this.myAge = n;
	}

	void display() {
		System.out.println("My name is " + myName + " and my age is " + myAge);

	}

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		FirstProgram obj1 = new FirstProgram("coder", 33);
		FirstProgram obj2 = new FirstProgram("decoder", 77);
		obj1.display();
		obj2.display();
	}

}
