

public class testt
{
    int x, y;
  public static void main(String args[])
    {
        testt t = new testt();
        System.out.println(t.x + " " + t.y);
    }
}


public class c {  
		 int speedlimit=90;
		void run(){  
		 speedlimit=400;  
		 System.out.println(speedlimit);
		 }  
		 public static void main(String args[]){  
		 c obj=new c();  
		 obj.run();  
		 }  
		
public class b{ 
		void sum(int a,int b)
		{System.out.println(a+b);
		}  
		 void sum(int a,int b,int c)
		 {System.out.println(a+b+c);
		 }  
		  public static void main(String args[])
		  {  
		b obj=new b();  
		obj.sum(10,10,10);  
		obj.sum(20,20);   
		}  
		    

}
public class st {
	int t,e,m,s,ss;
	void add(int m1,int m2,int m3,int m4,int m5)
	{
		t=m1;
		e=m2;
		m=m3;
		s=m4;
		ss=m5;
	int total=t+e+m+s+ss;
	
	System.out.println("total:"+total);
	float result=total/5;
	System.out.println("ans"+result);
	}
	public static void main(String args[])
	{
		st obj=new st();
		obj.add(45,67,43,44,44);
	}
	

}
	
