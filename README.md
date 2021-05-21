class A
{
	int a;
	A()
	{
		System.out.println("Im default constructor");
	}
}
class B extends A
{
	B()
	{
		super();
		System.out.println("Im in class B");
	}
}

class Jala 
{
	public static void main(String[] args){
		B b = new B();
			 
	}
}
