# ReverseOrder
 This application returns an integer in reverse order
 public class Application{
	
	public static void main(String []args){
		Reverse obj = new Reverse();
		Reverse obj1 = new Reverse();
		Reverse obj2 = new Reverse();
		System.out.println(obj.reverse(123));
		System.out.println(obj1.reverse(0));
		System.out.println(obj2.reverse(100000));
	
	}
 }
 public class Reverse{
	private String str="";
 
	public String reverse(int val){
		if(val ==0){
		return "";}
		else{
			while(val>0){
			str += val%10;
			val /=10;
			}
		}
		
	return str;}
 }
