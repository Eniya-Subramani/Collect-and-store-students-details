# Collect-and-store-students-details
import java.util.Scanner;
class Student1{
String name;
int age;
float m1,m2,m3,m4,m5,total,average;
public void inputDetails(){
Scanner sc = new Scanner(System.in);
System.out.print(&quot;Enter Name: &quot;);
name = sc.nextLine();
System.out.print(&quot;Enter Age: &quot;);
age = sc.nextInt();
System.out.print(&quot;Enter Tamil Mark: &quot;);

m1= sc.nextFloat();
System.out.print(&quot;Enter English Mark: &quot;);
m2 = sc.nextFloat();
System.out.print(&quot;Enter Maths Mark: &quot;);
m3 = sc.nextFloat();
System.out.print(&quot;Enter Science Mark: &quot;);
m4 = sc.nextFloat();
System.out.print(&quot;Enter Social Science Mark:&quot;);
m5 = sc.nextFloat();
total=m1+m2+m3+m4+m5;
average=total/5;
}
public void displayDetails(){
System.out.println(&quot;\n--------STUDENT DETAILS--------&quot;);
System.out.println(&quot;Student Name: &quot; + name);
System.out.println(&quot;Student Age: &quot; + age);
System.out.println(&quot;Tamil: &quot; + m1);
System.out.println(&quot;English: &quot; + m2);
System.out.println(&quot;Maths: &quot; + m3);
System.out.println(&quot;Science: &quot; + m4);
System.out.println(&quot;Social Science: &quot; + m5);
System.out.println(&quot;Total marks scored: &quot; + total);
System.out.println(&quot;Average: &quot; + average);
}
}
public class objectandinstance {
public static void main(String[]args){
Student1 s1 = new Student1();
s1.inputDetails();
s1.displayDetails();
}
}
OUTPUT:

Enter Name: Hema.M
Enter Age: 18
Enter Tamil Mark: 98
Enter English Mark: 96
Enter Maths Mark: 93
Enter Science Mark: 95
Enter Social Science Mark:90
--------STUDENT DETAILS--------
Student Name: Hema.M
Student Age: 18
Tamil: 98.0
English: 96.0
Maths: 93.0
Science: 95.0
Social Science: 90.0
Total marks scored: 472.0
Average: 94.4
