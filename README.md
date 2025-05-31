# Repo-29
Calculate average marks of five subjects
//Calculate average marks of five
import java.util.Scanner;
class average{
    public static void main(String[] args){
    int a,b,c,d,e;
    System.out.println("Enter marks of five subjects");
    Scanner r = new Scanner(System.in);
    a=r.nextInt();
    b=r.nextInt();
    c=r.nextInt();
    d=r.nextInt();
    e=r.nextInt();
    int sum=  a+ b+ c+ d+ e;
    System.out.println("Total marks");
     double avg = sum/5.0;
    System.out.println("Average marks:" + avg);
    }
}
