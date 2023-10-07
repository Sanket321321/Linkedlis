package collections.com;


import java.util.Collections;
import java.util.LinkedList;
import java.util.NoSuchElementException;

public class LinkedArrayLIstDemo {

	public static void main(String[] args) throws NoSuchElementException  {
		// TODO Auto-generated method stub
		LinkedList<Integer> arraylist =  new LinkedList<Integer>();
		   
		   //add method
		   arraylist.add(12);
		   arraylist.add(20);
		   arraylist.add(40);
		   arraylist.add(50);
		   arraylist.add(60);
		   arraylist.add(60);
		   
		   
		   System.out.println("arraylist element:");
		   System.out.println(arraylist);
		   
		   //remove methood 
		   arraylist.remove(0);
		   System.out.println("after remove element of 0 index list is"+arraylist);
		   
		   //get method 
		   int num = arraylist.get(2);
		   System.out.println(num);
		   
		   //contain method
		   System.out.println(arraylist.contains(40));
		   
		   //set method
		   arraylist.set(0, 15);
		   System.out.println("now list is:\n"+arraylist);
		   
		  //indexof method
		   System.out.println("2 index element is"+ arraylist.indexOf(40));
		   
		   //size method
		   System.out.println(arraylist.size());
		   
		   //isempty method
		   System.out.println(arraylist.isEmpty());
		   
		   //hashcode method
		   System.out.println(arraylist.hashCode());
		   
		   //lastindexof method
		   System.out.println(arraylist.lastIndexOf(60));
		   
		   //sort method
		   Collections.sort(arraylist);
		   System.out.println(arraylist);
		   
		   //foreach loop
		   for(int i : arraylist){
				System.out.println(i);
				}
		   
		   //addfirst method 
		   arraylist.addFirst(1000);
		   
		   //addlast method
		   arraylist.addLast(5000);
		   System.out.println(arraylist);
		   
		  
		   
		   //getfirst method
		   System.out.println("first element is list is:"+ arraylist.getFirst());
		   
		   //getlast
		   System.out.println("last element in the list is:"+ arraylist.getLast());
		   
		   //remove lst method
		   int first = arraylist.removeFirst();
		   System.out.println("remove element is:"+first);
		   
		   //remove last element
		   int last = arraylist.removeLast();
		   System.out.println("remove element is:"+last);
		   
		   //clear method
		   arraylist.clear();
		   System.out.println("after clear method:"+arraylist);
	}

}
