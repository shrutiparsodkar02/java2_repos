# java2_repos
it is my second repository(public repos)<br>
in these i will add code for calculator <br>
//take two number input,give choices to perform operations<br>
import java.util.Scanner;
import java.util.*;
import java.io.*;
class calculator{
    public static void main(String[] args) {
        int n1,n2,ch,cal;
        Scanner sc =new Scanner(System.in);
        System.out.println("enter first number");
        n1=sc.nextInt();
        System.out.println("enter second number");
        n2=sc.nextInt();
        System.out.println("enter choice for operations ");
        System.out.println("choice 1:addition");
        System.out.println("choice 2 :substraction");
        System.out.println("choice 3:multiplication");
        System.out.println("choice 4:division");
        System.out.println("choice 4:modulas");
        ch = sc.nextInt();
        if(ch==1){
            cal=n1+n2;
            System.out.println("addition =: "+cal);
        }
        else if(ch==2){
            cal=n1-n2;
            System.out.println("substraction="+cal);

        }
        else if(ch==3){
            cal=n1*n2;
            System.out.println("multiplication="+cal);

        } 
        else if(ch==4){
            cal=n1/n2;
            System.out.println("division="+cal);

        } 
       else{
        cal=n1%n2;
        System.out.println("remainder="+cal);
       }


        

    }
}
