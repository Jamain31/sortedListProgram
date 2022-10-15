# sortedListProgram
Java program that uses a linked list to insert and remove items. 

import java.util.LinkedList;


public class sortedListProgram {
	/**
	 * Program: Linked List States
	 * Author: Jamain Hughes
	 * Course: CPT307
	 * Instructor: Prof.Marquez
	 * Date:10/03/2022
	 */

	public static void main(String[] args) {
		LinkedList<String> states = new LinkedList<String>();
		//List
		states.add("Alabama");
		states.add("Alaska");
		states.add("Arizona");
		states.add("Arkansas");
		states.add("California");
		states.add("Colorado");
		states.add("Connecticut");
		states.add("Delarware");
		states.add("Florida");
		states.add("Georgia");
		states.add("Hawaii");
		states.add("Idaho");
		states.add("Illinois");
		states.add("Indiana");
		states.add("Iowa");
		states.add("Kansas");
		
		System.out.println("The original list consist of" + states);
		
		states.add("Kansas");
		states.add("Kentucky");
		states.add("Louisiana");
		
		System.out.println("Your updates list consist of" + states);
		
		states.removeFirst();
		states.remove(2);
		
	    
	    System.out.println("Your updated list consist of states" + states);
		
		System.out.println("-----------------");
		System.out.println("Sorted Linked List of States");
		System.out.println("Jamain Hughes");
		System.out.println("CPT307");
		System.out.println("Prof.Marquez");
		System.out.println("10/3/2022");
		
		

	}

}
![sortedlistprogramscreenshot](https://user-images.githubusercontent.com/108758588/195988931-df6e9e4b-389c-4062-aa4b-0fb994961272.png)
