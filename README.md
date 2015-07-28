# Equals-Ex


package raj;

import java.util.*;


public class raj{

public static void main(String args[]){  
  Student s1=new Student(101,"hari",23);  
  Student s2=new Student(102,"srini",21);  
  Student s3=new Student(103,"ajay",25);  
  Student s4=new Student(105,"loo",29);
  ArrayList<Student> al=new ArrayList<Student>();
  al.add(s1); 
  al.add(s2);  
  al.add(s3);  
  boolean b=al.equals(new Student(105,"loo",29));
  System.out.println(b); 
 Iterator<Student> itr=al.iterator();  
  while(itr.hasNext()){  
    Student st=(Student)itr.next();  
    System.out.println(st.rollno+" "+st.name+" "+st.age);  
  }  
 }  
}  
