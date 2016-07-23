# JavaSess7Ass4

package Session7;

import java.util.Scanner;

public class Sess7Ass4 {
	
	public static void main(String[] args) {
	
		String[] s={"apple","banana","orange"};
		System.out.println("Enter the string index to read:");
		Scanner read=new Scanner(System.in);
		try{
		int index=read.nextInt();
		System.out.println("String is "+s[index]+" from index "+index);	
		}catch(ArrayIndexOutOfBoundsException e){
			System.out.println("Index out of Bound !!!");
		}
	}
}
